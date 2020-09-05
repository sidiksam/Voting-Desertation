<template>
  <div class="bg-white">
    <div class="container">
      <div class="mx-16">
        <div class="flex justify-between items-center ">
          <div class="flex items-center">
            <router-link  class="font-serif text-3xl py-8 px-4 text-gray-700 hover:text-teal-400 transition duration-500" to="/"
              ><div
                
              >
                Voting
              </div></router-link
            >
            <router-link  active-class="text-teal-500" class=" text-gray-500" to="/"
              ><div class="px-8 pt-2 text-xs uppercase">
                Home
              </div></router-link
            >
            <router-link active-class="text-teal-500"  class="text-gray-500" to="/work"
              ><div
                class="pt-2 -8 uppercase text-xs hover:text-teal-400 "
              >
                How It Works
              </div></router-link
            >
          </div>

          <div class="flex pt-2 items-center">
            
                
            
            <router-link to="/register"
              ><div class="ml-3">
                <button
                  class="loginBg px-4 py-2 rounded mr-3  text-white uppercase text-sm font-medium hover:bg-teal-600 duration-500 focus:outline-none"
                >
                  Register as a voter
                </button>
              </div></router-link
            >
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { defineComponent, ref } from 'vue';
    
export default defineComponent ({
  
  setup(){
    return{

    }
  }
})
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
