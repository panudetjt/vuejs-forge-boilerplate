<script setup lang="ts"></script>
<template>
  <button
    class="inline-block p-2 bg-teal-300 rounded drop-shadow"
    v-bind="$attrs"
  >
    <slot></slot>
  </button>
</template>
