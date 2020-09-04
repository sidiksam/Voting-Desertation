<template>
  <div class="bg-white">
    <div class="container">
      <div class="mx-40">
        <div class="flex justify-between items-center ">
          <div class="flex items-center">
            <router-link to="/"
              ><div
                class="font-serif text-3xl py-8 px-4 text-gray-700 hover:text-teal-400 transition duration-500"
              >
                Voting
              </div></router-link
            >
            <router-link to="/"
              ><div class="px-8 pt-2 text-xs uppercase text-teal-400">
                Home
              </div></router-link
            >
            <router-link to="work"
              ><div
                class="pt-2 -8 uppercase text-xs text-gray-500 hover:text-teal-400 "
              >
                How It Works
              </div></router-link
            >
          </div>

          <div class="flex pt-2 items-center">
            
                
            
            <router-link to="register"
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

<script></script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
