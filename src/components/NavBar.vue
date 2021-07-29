<template>
  <div class="flex flex-row justify-between my-5 mx-5 text-blue-900 lg:mx-15">
    <div class="flex flex-row items-center">
      <img class="w-10 mr-2" alt="mj logo" src="../assets/logo.svg" />
      <p class="mx-3 font-semibold">Jdaoudi Mehdi</p>
    </div>
    <div class="flex flex-row items-center">
      <router-link class="mxl-2" to="/">Home</router-link>
      <router-link class="ml-2" to="/about">About</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "NavBar",
};
</script>