<template>
    <div v-if="(text1.length + text2.length) > 0">
        <p>{{ text1 }}</p>
        <p>{{ text2 }}</p>
    </div>
</template>

<script>
    export default {
        name: 'Component1',
        data() {
            return {
                text1:"Congrats you have discovered the issue",
                text2:"Don't forget to commit this solution"
                //I would not use string as a varibale name as it is variable type
                // string: null
            }
        }
    }
</script>