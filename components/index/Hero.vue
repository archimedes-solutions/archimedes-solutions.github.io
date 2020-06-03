<template>
  <div class="hero">
    <div class="hero__content d-flex">
      <v-layout fill-height justify-center align-center>
        <v-flex shrink>
          <h1 class="display-2">Archimedes Solutions</h1>
        </v-flex>
      </v-layout>
    </div>
  </div>
</template>

<script>
  export default {
    name: "Hero"
  }
</script>

<style lang="scss">
  .hero {
    background: url('../../assets/imgs/background.jpg');
    background-size: cover;
    background-position: bottom;
    min-height: 100vh;

    &__content {
      height: 100vh;
      color: white;
      background-color: rgba(0, 0, 0, 0.7);
    }
  }
</style>
