<template>
  <div class="hello">
    <h1>{{ greeting }}</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      greeting: 'Hello World!',
    };
  },
};
</script>

<style scoped>
.hello {
  font-size: 3rem;
  text-align: center;
}
</style>