<template>
  <div class="home">
    <Header title="Task Tracker" />
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Tempora, facilis.</p>
  </div>
</template>

<script>
// @ is an alias to /src

import Header from "../components/Header.vue"
export default {
  name: "HomeView",
  components: {
    Header
  },
};
</script>

<style lang="scss">
  $clr-white: #fff;
  .home{
    background: $clr-white;
    width: 600px;
    margin: 0 auto;
    box-shadow: 5px 5px 50px rgba(0,0,0,0.1);
    border-radius: 6px;
  }
</style>