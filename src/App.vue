<script setup>
import AppHeader from './components/AppHeader.vue';
import  AppFooter  from './components/AppFooter.vue'
import AppHome from './components/AppHome.vue'
import AppProject from './components/AppProject.vue'
import AppPricing from './components/AppPricing.vue'


</script>

<template>
 <AppHeader />
 <main class="container mx-auto mx-32 ">
   <AppHome />
   <AppProject />
   <AppPricing/>
  </main>
 <AppFooter />
</template>

<style scoped>

</style>
