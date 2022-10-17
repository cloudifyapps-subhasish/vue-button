<script>
import { defineComponent } from 'vue';
import SgVueButton from '@/sg-vue-button.vue';

export default defineComponent({
  name: 'ServeDev',
  components: {
    SgVueButton
  }
});
</script>

<template>
  <div id="app">
    <sg-vue-button />
  </div>
</template>
