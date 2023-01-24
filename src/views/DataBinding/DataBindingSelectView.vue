<template>
  <div>
    <select name="" id="" v-model="selectedData">
      <option value="01">1</option>
      <option value="02">2</option>
      <option value="03">3</option>
      <option value="04">4</option>
    </select>
    <br />
    <div>선택한값 : {{ selectedData }}</div>
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      selectedData: ''
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}
</script>
