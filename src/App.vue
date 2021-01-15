<template>
  <div id="#app">
    <div v-for="item in test" v-bind:key="item">
      <div>
        <h1>{{ item.name }}</h1>
        <h1>{{ item.age }}</h1>
        <h1>{{ item.work }}</h1>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      test: [
        {
          name: "ali",
          age: 200,
          work: "true",
        },
      ],
    };
  },
};
</script>

<style>
</style>
