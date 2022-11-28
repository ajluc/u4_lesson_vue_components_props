<template>
  <div>
    <h3>{{msg1}}</h3>
    <h3>{{msg2}}</h3>
  </div>
</template>

<script>
  export default {
    name: 'YouDoComp2',
    props: ['msg1', 'msg2']
  }
</script>

<style>
  h3 {
    color: #80CBC4;
  }
</style>