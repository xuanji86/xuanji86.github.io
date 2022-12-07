<script setup lang="ts">
import HelloWorld from '../components/HelloWorld.vue'
</script>
<template>
    <header>
    <img alt="Photo" class="Photo" src="../assets/Photo.jpg" width="300" height="300" />
      <div class="wrapper">
        <HelloWorld msg="Anji Xu's Personal Page" />
      </div>
    </header>
  
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

.Photo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .Photo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>