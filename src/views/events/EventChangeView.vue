<template>
  <div>
    <div @click="clickTest($event)">클릭하세요</div>
    <br />
    <button type="button" class="btn btn-primary">Primary</button>
    <br />
    <button type="button" class="btn btn-primary">Primary</button>
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {}
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {
    clickTest(event) {
      console.log(event.target)
    }
  }
}
</script>
