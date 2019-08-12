<template>
  <div id="app" class="small-container">
    <h1>Nacho</h1>

    <nacho-table />
  </div>
</template>

<script>
import NachoTable from './components/NachoTable.vue'

export default {
  name: 'app',
  components: {
    NachoTable,
  }
}
</script>

<style>
button {
  background: #009435;
  border: 1px solid #009435;
}

.small-container {
  max-width: 680px
}
</style>
