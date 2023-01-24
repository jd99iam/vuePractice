<template>
  <div>
    <select name="" id="">
      <option value="city.code" :key="city.code" v-for="city in cities">
        {{ city.title }}
      </option>
    </select>
    <br />
    <select name="" id="">
      <option value="city.code" :key="i" v-for="(city, i) in cities">
        {{ city.title }} , {{ i }}
      </option>
    </select>
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      cities: [
        { title: '서울', code: '01' },
        { title: '부산', code: '02' },
        { title: '인천', code: '03' }
      ]
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}
</script>
