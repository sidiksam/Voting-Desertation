<template>
  <div class="votingBackground min-h-screen ">
    <div class="container">
      <div class="mx-20 ">
        <div class="pt-24">
          <div class="flex">
            <div class=" w-1/4">
              <p
                class="text-sm py-16 font-semibold text-teal-500 bg-white rounded "
              >
                <span class="bg-gray-300 rounded ml-10 py-3 px-8   "
                  >How it works?</span
                >
              </p>
            </div>
            <div class="bg-white ml-8 rounded py-16 w-full">
              <div>
                <p class="text-lg pl-10 text-gray-800">How to use this Voting Platform</p>
                <div class="text-xs pl-20 text-gray-600 pt-3">
                  <p class="pb-3">
                    - Admin adds an Organization e.g Harvard Campus Election
                  </p>
                  <p class="pb-4">- Admin then adds the Positions in that Organization.</p>
                  <p class="pb-4">- Admin then adds Nominees for those Positions</p>
                  <p>- Then the Voters vote.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
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
