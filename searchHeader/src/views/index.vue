<template>
  <div class="index">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: "index",
  data() {
    return {
      
    };
  },
};
</script>

<style scoped>
.index {
  width: 100%;
  height: calc(100% - 45px);
}
</style>
