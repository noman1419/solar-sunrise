<template>
  <div>
    <navBar></navBar>
    <aboutUs></aboutUs>
    <contactUs></contactUs>
    <fooTer></fooTer>
  </div>
</template>

<script>
import navBar from './components/navBar.vue';
import contactUs from './components/contactUs.vue';
import aboutUs from './components/aboutUs.vue';
import fooTer from './components/fooTer.vue';

export default {
    name: "App",
    components: { navBar, aboutUs, contactUs, fooTer }

}
</script>
