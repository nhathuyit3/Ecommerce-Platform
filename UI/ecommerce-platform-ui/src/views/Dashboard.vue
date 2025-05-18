<template>
  <div class="dashboard-container">
    <search-bar />
    <h3>Dashboard</h3>
  </div>
</template>

<script>
import SearchBar from '../components/SearchBar.vue'
export default {
  name: 'Dashboard',
  components: { 
    'search-bar': SearchBar,
   },
  setup() {
    
  },
}
</script>

<style scoped>
</style>