<template>
    <div class="h-screen onboarding">
        <div class="flex flex-col items-center justify-center h-full bg-black bg-opacity-75">
            <div class="tracking-widest uppercase text-center max-w-7xl mx flex flex-col items-center">
                <h1 class="text-6xl text-gray-100 font-light mb-6">
                    JIMBO MAGUSIB
                </h1>
                <h2 class="text-2xl text-gray-200 font-extralight flex">
                    FULL STACK WEB DEVELOPER <span class="hidden sm:block mx-6">|</span> MOBILE APP DEVELOPER
                </h2>
                <div class="flex flex-wrap mt-12 items-center">
                    <template
                        v-for="(language, i) in topLanguages"
                        :key="i"
                    >
                        <h3 class="text-xl text-gray-200 font-thin flex mx-3">
                            {{language}}
                        </h3>
                    </template>
                </div>
                <div class="flex flex-wrap mt-3 items-center">
                    <template
                        v-for="(language, i) in languages"
                        :key="i"
                    >
                        <h3 class="text-gray-200 font-thin flex mx-3">
                            {{language}}
                        </h3>
                    </template>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    data: () => ({
        topLanguages: [
            'Laravel',
            'Angular',
            'React Native',
            'VueJs',
        ],
        languages: [
            'PHP',
            'React',
            'Statamic',
            'Javascript',
            'HTML',
            'CSS',
            'SCSS',
            'GIT',
            'Android',
            'IOS'
        ]
    }),
}
</script>
<style scoped>
    .onboarding {
        background-image: url('~@/assets/onboarding-bg.jpg');
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center;
    }
</style>