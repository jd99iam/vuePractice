<template>
  <div>
    <nav>
      <div style="font-size: 30px">Data Binding</div>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/databinding/string">DataBindingString</router-link> |
      <router-link to="/databinding/html">DataBindingHtml</router-link> |
      <router-link to="/databinding/input">DataBindingInput</router-link> |
      <router-link to="/databinding/select">DataBindingSelect</router-link> |
      <router-link to="/databinding/check">DataBindingCheck</router-link> |
      <router-link to="/databinding/attribute"
        >DataBindingAttribute</router-link
      >
      |
      <router-link to="/databinding/list">DataBindingList</router-link> |
      <router-link to="/databinding/class">DataBindingClass</router-link> |
      <router-link to="/databinding/style">DataBindingStyle</router-link> |
      <hr />
      <div style="font-size: 30px">Event</div>
      <router-link to="/event/click">EventClickView</router-link> |
      <router-link to="/event/change">EventChangeView</router-link> |
      <router-link to="/event/key">EventKeyView</router-link> |
    </nav>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
