<template>
  <HelloWorld />
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import HelloWorld from './helloWorld.vue'

export default defineComponent({
  name: 'App',
  components: {
    HelloWorld,
  },
})
</script>
