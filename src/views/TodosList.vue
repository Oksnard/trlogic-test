<template lang="pug">
  .home
    img(
      alt="Vue logo"
      src="../assets/logo.png"
    )
</template>

<script>
import Vue from 'vue'
import Component from 'vue-class-component'

@Component
export default class TodosList extends Vue {
  count = 0

  increment() {
    this.count++
  }

  decrement() {
    this.count--
  }
}
</script>

<style lang="stylus">
.home
	background pink
</style>
