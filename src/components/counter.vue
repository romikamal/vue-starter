<script setup lang="ts">
import { ref } from 'vue';

defineProps<{ msg: string }>();

const count = ref(0);
</script>

<template>
    <h1>{{ msg }}</h1>
    <button @click="count--">Count is: {{ count }}</button>
    {{ count }}
    <button @click="count++">Count is: {{ count }}</button>
</template>

<style scoped>
/** styles css */
</style>
