<template>
  <h1>job details page</h1>
  <p>The job id is {{ $route.params.id }}</p>
</template>

<script>
export default {
  props: ["id"],
  // data() {
  //   return {
  //     id: this.params.id,
  //   };
  // },
};
</script>

<style></style>
