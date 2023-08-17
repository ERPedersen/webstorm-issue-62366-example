<template>
  <div>
    {{ foo.bar }}
  </div>
</template>

<script setup lang="ts">
const foo: Ref<{bar: string}> = ref({bar: 'baz'})
</script>


































