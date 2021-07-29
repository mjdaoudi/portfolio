<template>
  <NavBar />
  <div class="px-4 mx-auto max-w-screen-2xl">
    <router-view />
  </div>
</template>


<script>
import NavBar from "./components/NavBar.vue";

export default {
  name: "App",
  components: { NavBar },
};
</script>