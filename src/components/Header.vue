<template>
  <div class="header">
    <h1 class="header__h1">{{title}}</h1>
    <Button text="Add Task"  />
  </div>
</template>

<script>
import Button from "./Button.vue"
export default {
  name: "Header",
  props: {
    title: String
  },
  components: {
    Button
  }
};
</script>

<style scoped lang="scss">
  $clr-black: #000;
  .header{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 15px 20px;
    border-bottom: 1px solid rgba(0,0,0,0.1);

    &__h1{
      font-size: 20px;
      font-weight: 500;
      margin: 0;
      padding: 0;
      color: $clr-black;
      font-weight: 700;
    }
  }
</style>
