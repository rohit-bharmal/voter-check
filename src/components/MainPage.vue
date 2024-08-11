<template>
  <div class="container">
    <div class="">
      <div class="input-container">
        <label for="input-box">Search here: </label>
        <pf-text-input id="input-box" type="text" placeholder="Add your name here"></pf-text-input>
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
}
</style>