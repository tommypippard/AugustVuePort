<script setup>
import Navigation from './components/navigation.vue'
import Spotify from './components/spotify.vue'
import Clock from './components/clock.vue'
</script>

<template>
<Navigation></Navigation>
<div class="col-12">
  <div class="row">
    <div class="col-lg-3 col-12">
      <Clock></Clock>
      <Spotify></Spotify>
    </div>
    <div class="col-lg-9 col-12">
      <h1>DEVELOPER<br/>ILLUSTRATOR<br/>WEB DEVELOPER</h1>
    </div>
  </div>
</div>
</template>

<style scoped>
h1 {
  font-size:20rem;
}
</style>
