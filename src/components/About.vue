<template>
    <div class="py-12 bg-gray-50">
        <div class="flex flex-col max-w-7xl mx-auto px-4">
            <SectionHeader title="about me" />
            <div class="mt-12 flex flex-row space-x-4">
                <div class="flex-1">
                    Image here
                </div>
                <div class="flex-1 bg-white shadow-md rounded p-6">
                    <h1 class="text-lg mb-6">
                        Hello visitor!
                    </h1>
                    <p class="text-justify">
                        Hi! I am Jimbo Magusib developer from Philippines. 
                        Full stack web and mobile app developer with 3 years of experience.
                        I am the lead developer / project maintainer of e-commerce website. I am also the lead / maintener frontend
                        developer of an education system website. I have developed 3 mobile apps; an app for real estate, an app for educator
                        and a core app for students. I have experience working with a team (local and international).
                    </p>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
import SectionHeader from '@/components/SectionHeader';
export default {
    components: {
        SectionHeader
    }
}
</script>
<style scoped>
    p {
        text-indent: 24px;
    }
</style>