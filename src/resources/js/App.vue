<template>
  <div>{{ hello }}</div>
</template>

// lang="ts"だとエラーが出る
<script>
import { ref } from "vue";
export default {
  setup() {
      const hello = ref(
          "Hello From TypeScript"
      )
      return {
          hello
      }
  },
};
</script>
