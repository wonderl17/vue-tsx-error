<template>
  <div>
    <Test />
  </div>
</template>

<script lang="tsx" setup>
import C1 from "./C1.vue";

const Test = () => {
  return <C1 msg="123" />;
};
</script>
