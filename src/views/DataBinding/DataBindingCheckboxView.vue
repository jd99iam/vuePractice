<template>
  <div>
    <div>
      <input type="radio" id="html" value="HTML" v-model="favLang" />
      <label for="html">HTML</label>
    </div>
    <div>
      <input type="radio" id="css" value="css" v-model="favLang" />
      <label for="css">css</label>
    </div>
    <div>
      <input type="radio" id="js" value="js" v-model="favLang" />
      <label for="js">js</label>
    </div>
    <br />
    <div>
      {{ favLang }}
    </div>
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      favLang: ''
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}
</script>
