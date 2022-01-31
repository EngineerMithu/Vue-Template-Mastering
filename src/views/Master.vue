<template>
 <header-section></header-section>
 <router-view></router-view>
 <leter-section></leter-section>
 <footer-section></footer-section>
</template>

<script>
import HeaderSection from '../components/frontend/Header.vue';
import LeterSection from '../components/frontend/Newsletter.vue';
import FooterSection from '../components/frontend/Footer.vue';
export default {
    name: "Master",
    components: { HeaderSection,LeterSection,FooterSection},
};
</script>

<style lang="">
    
</style>