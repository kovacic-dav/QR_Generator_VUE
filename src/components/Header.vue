<template>
  <div class="header">
    <div class="overheading">
      <img
        src="https://www.htl-wels.at/wp-content/uploads/2021/09/htl_logo-768x785.png"
        alt=""
      />
      <div>QR-Code Generator</div>
    </div>
    <h3>The easiest way to create QR Code</h3>
    <div class="subheading">Generate a QR code and download it!</div>
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {},
};
</script>

<style scoped>
.header {
  text-align: center;
}
h3 {
  margin-bottom: 5px;
}
.subheading {
  font-size: 14px;
}
img {
  width: 35px;
}
.overheading {
}
</style>
