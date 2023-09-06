<script setup lang="ts">
  const items = [{ message: 'Foo' }, { message: 'Bar' }]
</script>

<template>
  <ul>
    <li v-for="item in items" v-bind:key="item.message">
      {{ item.message }}
    </li>
  </ul>
</template>
