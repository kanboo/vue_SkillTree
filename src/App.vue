<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <router-view/>
    <!-- <the-footer></the-footer> -->
  </div>
</template>

<script>
import TheFooter from '@/components/TheFooter'

export default {
  name: 'App',
  components: {
    TheFooter
  }
}
</script>

<style lang="scss" src="./sass/all.scss"></style>
