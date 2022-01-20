<template>
  <div id="app">
    <div class="container">
      <!-- search bar -->
      <div class="search-box">
        <input type="text" placeholder="Search...." class="search-bar" />
      </div>

      <div class="weather-wrapper">
        <!-- location & date info -->
        <div class="location-box">
          <div class="location">Taichung</div>
          <div class="date">Octorber 8th 2020</div>
        </div>

        <!-- weather info -->
        <div class="weather-box">
          <div class="temperature">26°C</div>
          <div class="weather">Cloud</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style>
</style>