<template>
  <div>
    <div>
      <p class="text-center text-4xl pt-32 font-bold text-white pb-8">Voting</p>
    </div>
    <div class="loginBg pb-12">
      <p class="text-center font-medium text-white pt-8 text-2xl pb-6">
        Register
      </p>
      <div class="bg-white flex mx-auto w-1/2 mt-4 text-sm p-4 rounded">
        <input
          type="text"
          name="text"
          placeholder="Full Name"
          class="w-full focus:outline-none"
        />
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
          type="text"
          name="text"
          placeholder="Username"
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
      <div class="bg-white flex mx-auto w-1/2 mt-4 text-sm p-4 rounded">
        <input
          type="password"
          name="password"
          placeholder="Confirm Password"
          class="w-full focus:outline-none"
        />
      </div>
      <div
        class=" flex mx-auto w-1/2 mt-12 text-sm p-3 rounded  border-2 text-white hover:bg-white hover:text-gray-500  duration-500"
      >
        <p class="mx-auto   ">Login</p>
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
