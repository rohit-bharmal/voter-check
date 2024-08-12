<template>
  <div class="container">
    <div class="">
      <div class="input-container">
        <label for="input-box">आपले नाव शोधा: </label>
        <pf-text-input id="input-box" type="search" placeholder="मतदारयादीत आपले नाव शोधा"></pf-text-input>
      </div>
      <div class="img-wrapper">
        <img src="../assets/mla.JPG" alt="">
      </div>
    </div>
  </div>
</template>

<script>
import '@patternfly/elements/pf-text-input/pf-text-input.js';
</script>

<style scoped>
.container {
  max-width: 1440px;
  margin: 0 auto;
}

.input-container {
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 2rem auto;
}

pf-text-input {
  --pf-c-form-control--Width: 500px;
  --pf-c-form-control--Height: 36px;
}

.img-wrapper {
  display: flex;
  align-items: center;
  justify-content: center;
}

img {
  width: 800px;
  height: 800px;
}

@media (max-width: 768px) {
  .img-wrapper {
    display: none;
  }
}
</style>