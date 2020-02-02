<template>
  <div class="challenge">
    <h1>Bug Challenge 1</h1>
    <p>{{ msg }}</p>
    <p>{{ msg2 }}</p>
    <component-3 />
  </div>
</template>

<script>
  import Component3 from '@/components/Component3';

  export default {
    name: 'Challenge1',
    components: {
      Component3
    },
    data() {
      return {
        msg: 'Congrats you have discovered the issue',
        //find escape character miss with ' \' '
        msg2: 'Don\'t forget to commit this solutiom'
      }
    }
  }
</script>
