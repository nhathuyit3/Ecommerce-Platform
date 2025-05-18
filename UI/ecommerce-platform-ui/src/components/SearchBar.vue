<template>
  <div class="search-bar-container">
    <div class="icon-search"></div>
    <div class="text-search">
      <p>Search here...</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SearchBar',
  setup() {
    
  },
}
</script>

<style scoped>
.search-bar-container {
  display: flex;
  flex-direction: row;
  width: 100%;
  height: auto;
}
</style>