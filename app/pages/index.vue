<template>
  <h1 class="text-4xl font-black">HomePage</h1>
  <NuxtLink href="/about">About</NuxtLink>
  {{ counter }}
  <button @click="counter++">click</button>
</template>

<script lang="ts" setup>
const counter = useState<number>("count", () => 0);

counter.value;
useHead({
  title: "My Awesome Website",
});
</script>
