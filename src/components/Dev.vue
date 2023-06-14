<template>
  <div>
    <Test />
  </div>
</template>

<script lang="tsx" setup>
import Component4Dev2 from "./Component4Dev2.vue";

const C1 = () => {
  return <Component4Dev2 />;
};

const Test = () => {
  return <C1 msg="123" />;
};
</script>

<style lang="scss" scoped>
.icon {
  padding: 10px;
  color: var(--el-color-warning);
}
</style>
