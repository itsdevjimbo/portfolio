<template>
  <main class="bg-fixed ">
    <Onboarding />
    <About />
    <Skill />
  </main>
</template>   

<script>
import Onboarding from '@/components/Onboarding';
import About from '@/components/About';
import Skill from '@/components/Skill';
export default {
  components: {
    Onboarding,
    About,
    Skill
  },
}
</script>
<style scoped>
    main {
        background-image: url('~@/assets/main-bg.jpg');
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center;
    }
</style>