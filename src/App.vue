<template>
  <div>
    <Header></Header>
    <Home></Home>
  </div>
</template>

<script>
  import Header from './components/header/Header.vue';
  import Home from './components/home/Home.vue';
  export default {
    components: {
      'Header': Header,
      'Home': Home,
    },
  }
</script>
