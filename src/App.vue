<template>
  <div id="app">
    <hnav/>
    <transition name="fade">
      <router-view/>
    </transition>
    <footer>
      <div class="copyright-box">© 2019 fumika</div>
    </footer>
  </div>
</template>

<script>
import Header from '@/components/Header'
export default {
  name: 'App',
  components: {
    hnav: Header
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.fade-enter-active {
  transition: opacity 1s ease-in
  }
.fade-leave-active {
  transition: opacity .1s ease-out
}
.fade-enter, .fade-leave-to {
  opacity: 0
}

</style>
