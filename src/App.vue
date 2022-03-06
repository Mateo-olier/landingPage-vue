<script setup>
  import Header from "./components/Header.vue";
  import Section1 from './components/Section1.vue'
  import Cards from './components/Cards.vue'

  components: {
    Header;
    Section1;
    Cards;
  }
</script>

<template>
  <div class="container"> 
    <Header />
    <Section1/>
    <Cards />
  </div>
</template>

<style>
@import "./assets/base.css";
</style>
