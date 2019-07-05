<template>
  <div class="contents">
    <div class="contact">
      <h3>お気軽にご連絡ください！</h3>
      <ul>
        <li><a href="https://twitter.com/fumika78143169" target="_blank" class="twitter"><font-awesome-icon :icon="['fab', 'twitter']" size="5x" /></a></li>
        <li><a href="https://github.com/fumikao" target="_blank" class="github"><font-awesome-icon :icon="['fab', 'github']" size="5x" /></a></li>
      </ul>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.contact {
  margin: 30px;
  h3 {
    text-align: center;
  }
  ul {
    display: flex;
    justify-content: center;
    li {
      margin: 10px;
      &:hover {
        opacity: 0.5;
      }
      .twitter {
        color: #1DA1F2;
      }
      .facebook {
        color: #3B5998;
      }
      .github {
        color: black;
      }
    }
  }
}
</style>