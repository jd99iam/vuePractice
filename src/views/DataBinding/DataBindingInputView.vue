<template>
  <div>
    <input v-model="userName" />
    <div>{{ userName }}</div>
    <br />
    <input v-model="num1" />+<input v-model="num2" />=<span>{{
      num1 + num2
    }}</span
    ><br />
    <input v-model.number="num3" />+<input v-model.number="num4" />=<span>{{
      num3 + num4
    }}</span
    ><br />
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      userName: '',
      num1: 0,
      num2: 0,
      num3: 0,
      num4: 0
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}
</script>
