<template>
    <div id="section-two">
        <div class="text-center">
            <p
                class="font-serif font-black text-3xl lg:text-7xl md:text-4xl text-black-400 text-opacity-75"
            >As Real Reviewer.</p>
        </div>
        <div class="movies">
            <iframe
                width="560"
                height="315"
                src="https://www.youtube.com/embed/r3G_KOdr2v4?controls=0"
                title="YouTube video player"
                frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen
            ></iframe>
            <iframe
                width="560"
                height="315"
                src="https://www.youtube.com/embed/r3G_KOdr2v4?controls=0"
                title="YouTube video player"
                frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen
            ></iframe>
        </div>
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
#section-two {
}

#section-two > div.text-center {
    background-color: yellow;
    padding: 25vh 0;
    -webkit-clip-path: polygon(0 25%, 100% 0%, 100% 75%, 0% 100%);
    clip-path: polygon(0 25%, 100% 0%, 100% 75%, 0% 100%);
}

.movies {
    display: flex;
    justify-content: space-around;
}
</style>
