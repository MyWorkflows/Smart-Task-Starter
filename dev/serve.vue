<script lang="ts">
import { defineComponent } from 'vue';
import SmartTaskComponent from '@/smart-task-component.vue';

export default defineComponent({
  name: 'ServeDev',
  components: {
    SmartTaskComponent
  }
});
</script>

<template>
  <div id="app">
    <SmartTaskComponent />
  </div>
</template>
