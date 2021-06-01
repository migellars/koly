<template>
    <Header />
    <Featured />
    <Banner />
    <CTA />
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Header from "./components/Header.vue";
import Banner from "./components/Banner.vue";
import Featured from "./components/Featured.vue";
import CTA from "./components/CTA.vue";
export default {
    name: "App",
    components: {
        // HelloWorld,
        Header,
        Banner,
        Featured,
        CTA
    }
};
</script>

<style></style>
