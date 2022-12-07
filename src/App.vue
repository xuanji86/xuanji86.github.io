<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <RouterView></RouterView>
  </header>

  <main>
    <div class="tab"> Education </div>
    <div class = "Education">
      <h2> Iowa State University </h2>
      <h3> Computer Science </h3>
      <h3> GPA: 3.48 </h3>
      <h3> Expected Graduation: May 2023 </h3>
    </div>
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.tab {
  font-size: 1.5rem;
  font-weight: 500;
  text-align: left;
  margin: 0 auto;
  padding: 1rem 0;
}

</style>
