<template>
  <div>
    <ChildComponent>
      <template #header>
        <h2>This is the header content</h2>
      </template>
      <template #content>
        <p>This is the content</p>
      </template>
    </ChildComponent>
  </div>
</template>

<script>
import ChildComponent from "./ChildComponent.vue";

export default {
  components: {
    ChildComponent,
  },
};
</script>
