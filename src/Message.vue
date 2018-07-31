<template>
  <div>
    <h1> Welcome To Golang Blog</h1>
    <app-input></app-input>
  </div>
</template>

<script>
    import Input from './Input.vue';

    export default {
        components: {
            'app-input': Input
        }
    }
</script>
