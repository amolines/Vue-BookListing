<template>
  <div>
    <h1>{{title}}</h1>
  </div>
</template>

<script>
export default {
  props: {
    name: {
      type: string,
      default: ""
    }
  },
  data() {
    return {
      title: "All Books"
    };
  }
};
</script>

<style scoped>
h1 {
font-weight: normal;
}
</style>