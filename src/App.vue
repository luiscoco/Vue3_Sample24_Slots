<template>
  <div id="app">
    <ParentComponent />
  </div>
</template>

<script>
import ParentComponent from "../src/components/ParentComponent.vue";

export default {
  components: {
    ParentComponent,
  },
};
</script>
