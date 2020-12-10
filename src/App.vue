<template>
   <Navbar></Navbar>
   <Hero></Hero>
</template>

<script>
import Navbar from './components/Navbar';
import Hero from './components/Hero';

export default {
  components: {
    Navbar,
    Hero
  }
};
</script>

<style>
  *{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }
</style>
