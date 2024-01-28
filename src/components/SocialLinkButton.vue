<script setup lang="ts">
defineProps(["title", "url"]);
</script>

<template>
  <a :href="url" id="socialLinkButton">
    <h4>{{ title }}</h4>
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

#socialLinkButton:hover h4{
  color:black;
}

#socialLinkButton:hover {
  background-color: var(--custom-Green);
}

h4 {
  font-weight: 600;
}

@media screen and (max-width: 375px){
  #socialLinkButton {
    width: 75%;
  }

}
</style>