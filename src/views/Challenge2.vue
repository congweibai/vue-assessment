<template>
  <div class="challenge">
    <h1>Bug Challenge 2</h1>
    <component-1 />
    <component-3 />

  </div>
</template>

<script>
  import Component1 from '@/components/Component1';
  import Component3 from '@/components/Component3'

  export default {
    name: 'Challenge2',
    components: {
      Component1,
      Component3
    },
    data() {
      return {
        msg: 'Congrats you have discovered the issue',
      }
    }
  }
</script>
