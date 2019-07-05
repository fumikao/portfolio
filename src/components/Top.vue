<template>
  <div class="contents">
    <div class="top">
      <h1 class="top__title animated rollIn">Fumika Obayashi's<br>Portfolio</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: 'top'
}
</script>

<style lang="scss" scoped>
.top {
  background-image: url('../assets/flower.jpeg');
  background-size: cover;
  background-attachment: fixed;
  opacity: 0.7;
  width: 100vw;
  min-height: 100vh;
  overflow: hidden;
  &__title {
    color: white;
    font-weight: bold;
    text-align: center;
    letter-spacing: 10px;
    line-height: 80px;
    padding: 20% 0;
  }
}
</style>