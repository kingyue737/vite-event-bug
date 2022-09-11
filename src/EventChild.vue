<script setup lang="ts">
const emit = defineEmits<{
  (e: 'event-str', arg: string): void;
  (e: 'event-any', arg: any): void;
}>();
</script>

<template>
  <div>child</div>
</template>
