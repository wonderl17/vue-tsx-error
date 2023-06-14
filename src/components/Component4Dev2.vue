<template>
  <div class="">{{ msg }}</div>
</template>

<script lang="ts" setup>
defineProps<{ msg?: string | number }>();
</script>
