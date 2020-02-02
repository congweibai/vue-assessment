<template>
  <div class="challenge">
    <h1>Bug Challenge 3</h1>
    <!-- start with capital 'M', should be 'm' -->
    <component-2 :msg='msg' />
    <component-3 />
  </div>
</template>

<script>
  import Component2 from '@/components/Component2';
  import Component3 from '@/components/Component3';

  export default {
    name: 'Challenge2',
    components: {
      Component2,
      Component3
    },
    data() {
      return {
        msg: [
          'Congrats you have discovered the issue',
          'Don\'t forget to commit this solution'
        ]
      }
    }
  }
</script>
