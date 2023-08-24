<script setup lang="ts">
import Footer from "./Footer.vue";
import FooterLayout from "./FooterLayout.vue";
import HeaderLayout from "./HeaderLayout.vue";
import Header from "./Header.vue";
</script>

<template>
  <Header />
  <HeaderLayout />
  <div class="home-content">
    <p>&mdash; CyberA Platform &mdash;</p>
    <center>
      <img class="main-logo" src="../assets/CyberA.png" />
    </center>
  </div>
  <br />
  <br />
  <FooterLayout />
  <Footer />
</template>

<style scoped>
.main-logo {
  border: white solid 1px;
  border-radius: 15px;
}
.home-content {
  text-align: center;
}

.home-content p {
  color: white;
  padding-top: 125px;
  font-size: 30px;
  font-family: sans-serif;
}
</style>
