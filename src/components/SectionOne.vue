<template>
    <div id="section-one">
        <div class="text-center">
            <p
                class="font-serif font-black text-3xl lg:text-7xl md:text-4xl text-black-400 text-opacity-75"
            >On Your Mind.</p>
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
#section-one {
}

#section-one > div {
    padding: 25vh;
}
</style>
