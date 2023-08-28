<script>
export default {
  data() {
    return {
      currentYear: new Date().getFullYear(),
    };
  },
};
</script>

<template>
  <div class="footer">
    <p>
      &copy; Copyright {{ currentYear }} All right reserved. CyberA Platform.
      <span style="color: white; font-size: 23px"
        ><i class="bi bi-arrow-up-square-fill"></i
      ></span>
    </p>
  </div>
</template>

<style scoped>
.footer {
  padding: 15px;
}
.footer p {
  color: white;
  text-align: center;
  font-family: sans-serif;
  font-weight: bold;
}
</style>
