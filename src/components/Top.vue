<template>
  <div class="flex flex-wrap items-center p-16" id="top">
    <div class="w-full md:w-1/2 text-center md:text-right p-8">
      <p>
        <span
          class="font-serif font-black text-3xl lg:text-7xl md:text-4xl text-black-400 text-opacity-75"
        >Oda Lemon</span>
        <span class="font-serif font-black text-3xl lg:text-7xl md:text-4xl text-green-400">e</span>
      </p>
      <p class="font-serif font-black lg:text-2xl md:text-md text-opacity-75">Is Still Alive</p>
    </div>

    <img src="/@assets/face.jpg" class="rounded-full w-full md:w-1/2 p-8" />
  </div>
</template>

<script lang="ts">
import { defineComponent, ImgHTMLAttributes, onMounted } from "vue";
export default defineComponent({
  name: "Top",
  setup() {
  }

});
</script>

<style scoped>
#top {
  /* background-color: yellow; */
  background-image: url("src/assets/lemone_bg.png");
  background-size: 100% 100%;
}
</style>
