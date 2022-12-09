<template>
  <div>
    <h1 class="text-3xl text-purple-600 font-bold">Testing Vue / Vite and Hot Reload by {{ name }}</h1>

    <div class="test-container">
      <p class="test-par">This is inside the container</p>
    </div>

    <p class="test-par">This is outside the container</p>
    <p class="test-par my-ass">Hello</p>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        name: 'Elias Mahfuzul Golam',
      }
    }
  }
</script>

<style lang="postcss" scoped>

.test-container {

  background-color: yellow;
  .test-par {
    color: red;
  }
}



</style>
