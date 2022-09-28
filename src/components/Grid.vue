<template>
  <div>Yo</div>
  <div v-for="(row, index) in data" :key="index">
    Row {{ index }}: {{ row }}
  </div>
</template>

<script lang="ts">
const data = [
  [0, 0, 1, 0, 0],
  [0, 0, 1, 0, 0],
  [1, 1, 1, 1, 1],
  [0, 0, 1, 0, 0],
  [0, 0, 1, 0, 0],
];

export default {
  setup() {
    return { data };
  },
};
</script>
