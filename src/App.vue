<template>
  <router-view></router-view>
</template>

<script>
import store from './store/store.js'
import './common/scss/index.scss'

export default {
  store: store,
}
</script>

<style lang="scss">
html {
  height: 100%;
  transition: height 0.5s;
}

body {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
}

#app {
  color: #2c3e50;
  margin-top: -100px;
  max-width: 600px;
  font-family: Source Sans Pro, Helvetica, sans-serif;
  text-align: center;
}

#app a {
  color: #42b983;
  text-decoration: none;
}

.logo {
  width: 100px;
  height: 100px
}
</style>
