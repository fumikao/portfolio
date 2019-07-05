<template>
  <nav class="header-nav">
    <ul>
      <li><router-link to="/">Home</router-link></li>
      <li><router-link to="/about">About</router-link></li>
      <li><router-link to="/projects">Projects</router-link></li>
      <li><router-link to="/contact">Contact</router-link></li>
    </ul>
  </nav>
</template>

<style lang="scss" scoped>
.header-nav {
  width: 100vw;
  position: fixed;
  z-index: 2;
  background-color: gray;
  opacity: 0.8;
  height: 40px;
  ul {
    display: flex;
    justify-content: center;
    li {
      padding: 0 20px;
      line-height: 40px;
      display: block;
      font-weight: bold;
    }
    a {
      color: white;
      text-decoration: none;
      &:hover {
        opacity: 0.6;
      }
    }
  }
}
</style>