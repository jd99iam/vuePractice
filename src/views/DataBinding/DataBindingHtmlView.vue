<template>
<div>
    <div>{{ userHtml }}</div>
    <div v-html="userHtml"></div>
</div>
</template>
<script>

export default {
  components: {},
  data() {
    return {
      userHtml: '<p>this is HTML tag</p>'
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}
</script>
