<template>{{ testId }}</template>

<script lang="ts" setup>
const testId = useRoute().params.profileId;
</script>
