<template>
  <div>
    <div>
      <p class="text-center text-4xl pt-32 font-bold text-white pb-8">Voting</p>
    </div>
    <div class="loginBg min-h-screen">
      <p class="text-center font-medium text-white pt-8 text-2xl pb-6">
        Login
      </p>
      <div class="bg-white flex mx-auto w-1/2 text-sm p-6 rounded">
        <div>Voter</div>
        <div class="pl-64"><input type="radio" /></div>
        <div class="ml-56 ">Nominee</div>
      </div>
      <div class="bg-white flex mx-auto w-1/2 mt-4 text-sm p-4 rounded">
        <input
          type="email"
          name="email"
          placeholder="Email"
          class="w-full focus:outline-none"
        />
      </div>
      <div class="bg-white flex mx-auto w-1/2 mt-4 text-sm p-4 rounded">
        <input
          type="password"
          name="password"
          placeholder="Password"
          class="w-full focus:outline-none"
        />
      </div>
      <div
        class=" flex mx-auto w-1/2 mt-4 text-sm p-3 rounded  border-2 hover:bg-white hover:text-gray-500  duration-500"
      >
        <p class="mx-auto text-white  ">Login</p>
      </div>
      <div
        class=" flex mx-auto w-1/2 mt-4 text-sm p-3 rounded hover:bg-red-800  duration-500 bg-red-600 font-medium "
      >
        <p class="mx-auto text-white  ">Register</p>
      </div>
    </div>
  </div>
</template>
<script>
import { defineComponent } from "vue";

export default defineComponent({
  saetup() {
    return {};
  },
});
</script>
