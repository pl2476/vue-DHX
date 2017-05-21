<template>
  <div class="container">
    <grid></grid>
  </div>
</template>

<script>
import grid from './components/grid.vue'

export default {
  name: 'app',
  components: { grid },
  data() {
    return {
    }
  },
  filters: {

  },
  methods: {

  }
}
</script>

<style>
html,
body {
  height: 100%;
  margin: 0;
  padding: 0;
}

.container {
  height: 100%;
  width: 100%;
}
</style>
