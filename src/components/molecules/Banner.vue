<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light backgroundImage">
    <img src="../../assets/hibouBanniere.png" class="logoHibou" alt="" />
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
  </nav>
</template>

<script>
export default {
  name: "Banner",
};
</script>

<style scoped>
.backgroundImage {
  background-image: url("../../assets/Book.jpg");
  background-position: center;
  background-size: cover;
  height: 120px;
}
.logoHibou {
  margin: 20px;
  height: 140px;
}
@import "~bootstrap/dist/css/bootstrap.css";
</style>
