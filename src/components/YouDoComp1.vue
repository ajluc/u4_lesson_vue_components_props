<template>
  <div>
    <h3>{{ msg }}</h3>
  </div>
</template>

<script>
  export default {
    name: 'YouDoComp1',
    props: {
      msg: {
        type: String,
        required: true
      }
    }
  }
</script>

<style>
  h3 {
    color: #80CBC4;
  }
</style>