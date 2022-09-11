<script setup lang="ts">
import EventChild from './EventChild.vue';
const handlerAny = (v: number) => {};
const handlerStr = (v: string) => {};
</script>

<template>
  <div id="app">
    <div>Hello World</div>
    <EventChild @event-str="handlerStr" @event-any="handlerAny" />
  </div>
</template>
