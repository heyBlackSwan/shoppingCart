<template>
  <div>
    <h1>hello {{ title }}</h1>
  </div>
</template>

<script>
export default {
  name: "app",
  data() {
    return {
      title: "test project"
    };
  }
};
</script>

<style scoped>
h1 {
  color: red;
}
</style>
