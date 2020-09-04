<template>
  <div class="votingBackground min-h-screen">
    <div class="container ">
      <div class="mx-20">
        <div class=" text-center pt-10 text-gray-700 text-2xl uppercase">
          <p>Profile</p>
        </div>
        <div class="bg-white py-10 rounded mt-12 ">
          <div v-for="(row, index) in profiles" :key="index" class="flex ">
            <div>
              <p>
                <img
                  class="rounded-full w-40 h-40 object-cover border-4  border-gray-200 shadow-sm  border-solid ml-32"
                  :src="row.photo"
                />
              </p>
            </div>
            <div class="text-sm ml-20 pt-8">
              <p class="text-2xl text-gray-500 pb-2">{{ row.name }}</p>
              <p class="pb-3">
                University:
                <span class="text text-sm">
                  Institute of Public Administration and Management (IPAM)
                  Election</span
                >
              </p>
              <p>Running to Be: <span class="text text-sm ">President</span></p>
            </div>
          </div>
        </div>
        <div class="bg-white mt-16 w-5/6 rounded">
          <div>
            <div class="flex  ml-12 pt-10">
              <p>
                <svg width="32" height="40" viewBox="0 0 24 24" fill="teal">
                  <path
                    d="M13.981,2H6.018c0,0-0.996,0-0.996,1h9.955C14.977,2,13.981,2,13.981,2z M16.968,5c0-1-0.995-1-0.995-1H4.027
	c0,0-0.995,0-0.995,1v1h13.936V5z M18.958,6C18.37,5.408,18.37,5.408,18.37,5.408V7H1.63V5.408c0,0,0,0-0.589,0.592
	C0.452,6.592,0.03,6.75,0.267,8c0.236,1.246,1.379,8.076,1.549,9c0.186,1.014,1.217,1,1.217,1h13.936c0,0,1.03,0.014,1.217-1
	c0.17-0.924,1.312-7.754,1.549-9C19.97,6.75,19.548,6.592,18.958,6z M14,11.997C14,12.551,13.551,13,12.997,13H7.003
	C6.449,13,6,12.551,6,11.997V10h1v2h6v-2h1V11.997z"
                  />
                </svg>
              </p>
              <p class="text-xl pl-8 pt-1 text-gray-500">Biography</p>
            </div>
            <div class="mx-20 text-sm w-1/2 pl-8 p-1 text-gray-600 font-light">
              <P
                >Lorem ipsum dolor sit amet consectetur adipisicing elit. Illum,
                sit iusto odio neque dolorem necessitatibus eveniet sed, quia
                excepturi velit enim quas ab maiores amet ad architecto
                distinctio vero quasi.Vero aperiam voluptatum deserunt inventore
                a ipsa eius ex consequatur, commodi quos omnis excepturi vel
                placeat tempore eaque officia? Totam, nesciunt harum ipsam dolor
                deleniti culpa odit repellat sunt consectetur.</P
              >
            </div>
          </div>
          .
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import { defineComponent } from "vue";

export default defineComponent({
  setup() {
    return {
      profiles: [
        {
          id:1,
          photo:
            "https://lh3.googleusercontent.com/proxy/soZ9QJ6-qReNY-2KC3Qa1HQZq0mkt4pdxgvcrQwVcMuOvDcgusRQPtey5wQ0IV9bAvjwEvX6nFAdLI0PcIcqWGcuYIgVa1px5mJm",
          name: "Frobay College Election",
        },
      ],
    };
  },
  components: {},
});
</script>
