<template>
  <div>
    <input type="text" v-bind:value="readOnlyInput" readonly /><br />
    <img :src="imgSrc" alt="" /><br />
    <input type="text" v-model="txt" />
    <button :disabled="txt === ''">검색하기</button>
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      readOnlyInput: 'messi',
      imgSrc:
        'https://item.kakaocdn.net/do/493188dee481260d5c89790036be0e66effd194bae87d73dd00522794070855d',
      txt: ''
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}
</script>
