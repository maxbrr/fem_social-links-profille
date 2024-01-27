<script setup lang="ts">
defineProps(["title", "url"]);
</script>

<template>
  <a :href="url" id="socialLinkButton">
    <h3>{{ title }}</h3>
  </a>
</template>

<style scoped>
#socialLinkButton {
  width: 85%;
  height: 50px;
  background-color: var(--custom-Grey);
  text-decoration: none;
  color: white;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 10px;
  border-radius: 2mm;
}


</style>