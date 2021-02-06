<template>
  <div>App</div>
  <div>{{ msg }}</div>
</template>

<script lang='ts'>
import { defineComponent } from 'vue'
export default defineComponent({
  name: 'Home',
  props: {
    msg: String
  }
})

</script>
