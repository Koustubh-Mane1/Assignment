<script setup>
import HelloWorld from './components/NavBar.vue'
import Blogs from './components/Blogs.vue'
import NewsFeed from './components/NewsFeed.vue'
import Jobs from './components/Jobs.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <div class = "font-Oswald">
  <HelloWorld />
  <div class = "grid grid-cols-5">
    <Blogs class = "col-span-4"/>
    <NewsFeed/>

  </div>
  
 
  <Jobs/>
  <Footer/>
</div>
</template>

<style >

</style>
