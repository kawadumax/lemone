<template>
  <div class>
    <Top />
    <SectionOneVue />
    <SectionTwoVue />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Top from './components/Top.vue'
import SectionOneVue from './components/SectionOne.vue'
import SectionTwoVue from './components/SectionTwo.vue'
export default defineComponent({
  name: 'App',
  components: {
    Top,
    SectionOneVue,
    SectionTwoVue
  }
})
</script>

<style>
html {
  /* background-color: yellow; */
}
</style>
