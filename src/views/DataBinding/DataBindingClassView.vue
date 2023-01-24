<template>
  <div>
    <div :class="{ 'text-red': true }">test1</div>
    <br />
    <div :class="{ 'text-red': true, 'back-black': true }">test2</div>
    <br />
    <div :class="{ 'text-red': goRed, 'back-black': goBlack }">test3</div>
    <br />
    <button @click="backChange">change BackGround!</button>
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      goRed: true,
      goBlack: false
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {
    backChange() {
      if (this.goBlack === false) {
        this.goBlack = true
      } else {
        this.goBlack = false
      }
    }
  }
}
</script>
<style scoped>
.text-red {
  color: red;
}
.back-black {
  background: black;
}
</style>
