<template>
<div>
    <h1>Hello {{ userName }}</h1>
</div>
</template>
<script>
export default {
  data () {
    return {
      userName: 'Leo Messi'
    }
  }
}
</script>
<style scoped>
.text-red{
    color : red;
}
</style>
