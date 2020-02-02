<template>
  <div class="challenge">
    <h1>Bug Challenge 1</h1>
    <p>{{ msg }}</p>
    <p>{{ msg2 }}</p>
  </div>
</template>

<script>
  export default {
    name: 'Challenge1',
    data() {
      return {
        msg: 'Congrats you have discovered the issue',
        //find escape character miss with ' \' '
        msg2: 'Don\'t forget to commit this solutiom'
      }
    }
  }
</script>
