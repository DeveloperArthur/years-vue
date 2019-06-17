<template>
  <div id="app">
    <app-years></app-years>    
  </div>
</template>

<script>
import years from './components/yeas.vue';

export default {
  data () {
    return {
      idade: 0
    }
  },
  components: {
    AppYears: years
  }
}
</script>

<style>
</style>
