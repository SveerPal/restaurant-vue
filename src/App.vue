<template>
<img alt="Vue logo" src="./assets/img/logo.png">
<router-view />
<!--<Signup />-->
</template>

<script>
//import Signup from './components/Signup.vue'

export default {
    name: 'App',
    components: {
        // Signup
    }
}
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    /* margin-top: 60px;*/
}
body {
    margin: 0px;
}
</style>
