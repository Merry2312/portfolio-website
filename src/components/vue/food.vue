<template>
  <div>
    <ul>
      <li v-for="item in food">
        {{ item }}
      </li>
    </ul>
    <v-btn>
      Button
    </v-btn>
    <v-icon icon="mdi-plus"></v-icon>
  </div>
</template>

<script setup lang="ts">
const food = ["Pizza", "French fries", "Spaghetti"];
</script>