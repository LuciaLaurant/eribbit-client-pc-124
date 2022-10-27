<template>
  <p>456</p>
  <div id="app">
    123
    <p>{{store.state.username}}</p>
  </div>
</template>

<script>
import {
  useStore
} from 'vuex'
export default {
  name: 'App',
  setup() {
    const store = useStore()
    // console.log(store.state.username)
    return { store }
  }
}
</script>

<style lang="less">

</style>
