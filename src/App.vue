<template>
  <div>
    <NavigationVue />
    <div>
      <div class="min-h-screen bg-grey bg-cover w-full shadow-md bgImage">
        <div class="bgOpercity">
           <router-view />
        </div>
       
        <FooterVue />
      </div>
    </div>
  </div>
</template>
<script>
import NavigationVue from "./components/Navigation.vue";

import { defineComponent } from "vue";
import FooterVue from "./components/Footer.vue";

export default defineComponent({
  setup() {
    return {};
  },

  components: {
    NavigationVue,
    FooterVue,
  },
});
</script>

<style></style>
