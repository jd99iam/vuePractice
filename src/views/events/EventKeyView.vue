<template>
  <div>
    <input type="text" v-model="inputText" @keyup.enter="consoleLog" />
    <button @click="consoleLog">console-log</button>
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      inputText: ''
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {
    consoleLog() {
      console.log(this.inputText)
    },
    checkEnter(event) {
      if (event.keyCode === 13) {
        this.consoleLog()
      }
    }
  }
}
</script>
