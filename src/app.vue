<template>
  <button @click="count++">
    點我增加
  </button>
  <div>
    {{ count }}
  </div>
</template>

<script>
import { ref } from 'vue';

export default {
  name: 'App',
  setup() {
    const count = ref(0);
    
    return {
      count
    }
  }
}
</script>