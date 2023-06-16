<template>
    <div>
        <div class="py-8">
           <h1 class = "flex justify-center text-4xl font-semibold">Jobs</h1>
        </div>
        
           <div class = "grid grid-cols-3 justify-items-center h-1/2">

            <span v-for="n in 3" v-bind:key="n" >
                <div class = "grid justify-items-center">
                 <h1 class = "text-xl"> Job number {{ n }} </h1>
                 <img class = "py-5 w-1/6" src = "../assets/job.svg"/>
             </div>
            
             </span>
            
           </div>
          <hr/> 
       
   </div>
</template>
<script>

</script>
<style scoped>

</style>
