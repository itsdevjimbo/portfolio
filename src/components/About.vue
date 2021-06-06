<template>
    <div class="py-12 bg-gray-50">
        <div class="flex flex-col max-w-7xl mx-auto px-4">
            <SectionHeader title="about me" />
            <div class="mt-36 flex flex-col">
                <div class="flex-1 bg-white shadow-md rounded p-6 relative">
                    <img src="@/assets/me.jpeg" alt="Jimbo Magusib" class="absolute -top-24 inset-x-0 mx-auto w-48 h-48 rounded-full shadow-xl">
                    <p class="text-justify mt-24">
                        <strong>Hi !</strong> I am <strong>Jimbo Magusib</strong> developer from Philippines. 
                        <strong class="uppercase">full stack web and mobile app developer</strong> with 3 years of experience.
                        I am the lead developer / project maintainer of an e-commerce website. I am also the lead / maintener frontend
                        developer of an education system website. I have developed 3 mobile apps; an app for real estate, an app for educator
                        and a core app for students. I have experience working with a team (local and international).
                    </p>
                    <p class="text-justify mt-6">
                        <strong>ITS FUN WRITING CODE.</strong> At home whenever I have time, its either reading a book or learniing new things.
                        I watched tutorials, read articles, answering in stack overflow or reading answers in some interesting topics / issue.
                        I love making a simple project and upload it to git. 
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