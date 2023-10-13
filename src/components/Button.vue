<template>
  <button>
    <slot>
      <span>{{ props.label }}</span>
    </slot>
  </button>
</template>

<script setup lang='ts'>
const props = withDefaults(defineProps<{
  label: string | number
}>(), {

});
</script>
