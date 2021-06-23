<template>
  <div class="container mx-auto">
    <Top />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Top from './components/Top.vue'

export default defineComponent({
  name: 'App',
  components: {
    Top
  }
})
</script>

<style>
</style>
