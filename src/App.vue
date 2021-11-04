<template>
  <div class>
    <Top />
    <SectionOne />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Top from './components/Top.vue'
import SectionOne from './components/SectionOne.vue'
export default defineComponent({
  name: 'App',
  components: {
    Top,
    SectionOne
  }
})
</script>

<style>
html {
  /* background-color: yellow; */
}
</style>
