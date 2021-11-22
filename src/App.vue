<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from "./components/HelloWorld.vue";

function wave() {
  console.log("Hello World!");
}
</script>

<template>
  <div class="mainContainer">
    <div class="dataContainer">
      <div class="header">👋 Hey there!</div>

      <div class="bio">
        I am Louis and I worked in CyberSecurity and learning web3 so that's
        pretty cool right? Connect your Ethereum wallet and wave at me!
      </div>

      <button class="waveButton" @click="wave">Wave at Me</button>
    </div>
  </div>
</template>

<style></style>
