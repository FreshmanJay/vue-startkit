<template>
  <div id="app">
    <transition name="bounce">
      <router-view></router-view>
    </transition>
  </div>
</template>

<script>
  export default {
    name: 'app',
    components: {},
    data() {
      return {

      }
    },
    methods: {
      init() {

      }
    },
    mounted() {
      this.init()
    },
    watch: {
      $route(to, from) {

      }
    }
  }
</script>

<style lang="scss" scoped>
</style>
