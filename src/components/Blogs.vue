<template>
    <div class = "h-auto overflow-hidden">
         <div class="py-8">
            <h1 class = "flex justify-center text-4xl font-semibold">Blogs</h1>
         </div>
         <div>
            <div class = "grid grid-rows-3">
              <div>
                <h1 class = "flex justify-center p-5 text-3xl pb-8">Placement Preparation</h1>
              <div class = "grid grid-cols-4 gap-5 ">
                <span v-for="n in 7" v-bind:key="n" >
                   <div class = "grid justify-items-center">
                    <h1 class = "text-sm"> Blog number {{ n }} </h1>
                    <img class = "py-5 w-1/6" src = "../assets/blog.svg"/>
                </div>
               
                </span>
              </div>
              </div>


              <div>
                <h1 class = "flex justify-center text-3xl pb-8 pt-5">Placements</h1>
                <div class = "grid grid-cols-4 gap-5">
                    <span v-for="n in 7" v-bind:key="n" >
                       <div class = "grid justify-items-center">
                        <h1 class = "text-xl"> Blog number {{ n }} </h1>
                        <img class = "py-5 w-1/6" src = "../assets/blog.svg"/>
                    </div>
                   
                    </span>
                  </div>
              </div>

              <div>
                <h1 class = "flex justify-center text-3xl pb-8 pt-5">Placement Advice</h1>
                <div class = "grid grid-cols-4 gap-5">
                    <span v-for="n in 7" v-bind:key="n" >
                       <div class = "grid justify-items-center">
                        <h1 class = "text-xl"> Blog number {{ n }} </h1>
                        <img class = "py-5 w-1/6" src = "../assets/blog.svg"/>
                    </div>
                   
                    </span>
                  </div>
              </div>
             
            </div>
         </div>
    </div>
</template>
<script>

</script>
<style scoped>

</style>
