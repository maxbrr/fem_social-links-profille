<script setup lang="ts">
import SocialLinkButton from './SocialLinkButton.vue';
</script>

<template>
  <div id="socialLinkCard">
    <img src="../assets/avatar-jessica.jpeg" id="avatar">
    <h1 id="name">Jessica Randall</h1>
    <h4 id="location">London, United Kingdom</h4>
    <h4 id="punchline">"Front-end developer and avid reader"</h4>
    <div id="socialLinkButtons">
      <SocialLinkButton title="GitHub" url="www.github.com"/>
      <SocialLinkButton title="Frontend Mentor" url="www.github.com"/>
      <SocialLinkButton title="LinkedIn" url="www.github.com"/>
      <SocialLinkButton title="Twitter" url="www.github.com"/>
      <SocialLinkButton title="Instagram" url="www.github.com"/>
    </div>
  </div>
</template>

<style scoped>
#socialLinkCard {
  background-color: var(--custom-DarkGrey);
  width: 480px;
  height: 740px;
  display: flex;
  flex-direction: column;
  align-items: center;
  border-radius: 4mm;
}

#avatar {
  border-radius: 50%;
  width: 100px;
  height: 100px;
  margin-top: 50px;
  margin-bottom: 40px;
}

#name {
  color: white
}

#location {
  color: var(--custom-Green);
  padding-top: 10px;
  padding-bottom: 20px;
}

#punchline {
  color: white;
  font-weight: 400;
  margin-top: 10px;
  margin-bottom: 20px;
}

#socialLinkButtons {
  width: 400px;
  height: 380px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

#socialLinkButtons > * {
  margin-bottom: 10px;
}
</style>
