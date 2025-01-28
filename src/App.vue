<script setup lang="ts">
// import HelloWorld from './components/HelloWorld.vue'
// import Navbar from './components/Navbar.vue'
import SectionContainer from './components/SectionContainer.vue';
import ListContainer from './components/ListContainer.vue';
import TrailerContainer from './components/TrailerContainer.vue';
</script>

<template>
   <SectionContainer title="Trending Now">
    <ListContainer />
   </SectionContainer>
   <SectionContainer title="Latest Trailer" :isBackground=true>
    <TrailerContainer />
   </SectionContainer>
   <SectionContainer title="Whats Popular">
    <ListContainer /> 
   </SectionContainer>
</template>

<style scoped>
/* .logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
} */
</style>
