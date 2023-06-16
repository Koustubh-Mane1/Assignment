<template>
    <div class = "py-8">
        <div class="">
            <h1 class = "flex justify-center text-4xl font-semibold p-5">News Feed</h1>
        </div>
        <div class = "">
           <div class = "grid grid-rows-3 content-start ">
            <span v-for="n in 3" v-bind:key="n" >
                <div class = "grid justify-items-center">
                 <h1 class = "text-xl"> News Article {{ n }} </h1>
                 <img class = "py-5 w-1/6" src = "../assets/news.svg"/>
             </div>
            
             </span>
           </div>
        </div>
   </div>
</template>
<script>

</script>
<style scoped>

</style>
