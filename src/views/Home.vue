<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <h1>Vue Debug Assessment</h1>
    <p>Finish the bugs on each of the following pages and correct them</p>
    <component-3 />
  </div>
</template>

<script>
  import Component3 from '@/components/Component3';
  export default {
    name: 'home',
    components: {
      Component3
    }
  }
</script>
