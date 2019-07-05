<template>
  <div class="contents">
    <div class="contact">
      <h3>お気軽にご連絡ください！</h3>
        <ul>
          <li>
            <a href="https://twitter.com/fumika78143169" target="_blank" class="twitter"><font-awesome-icon :icon="['fab', 'twitter']" size="2x" />@fumika78143169</a>
          </li>
          <li>
            <p class="mail"><font-awesome-icon :icon="['fas', 'envelope']" size="2x" />  fumika.obayashi@gmail.com</p>
          </li>
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
    border: 1px dashed gray;
    margin: 20px auto;
    padding: 30px;
    li {
      margin: 10px;
    a {
      text-decoration: none;
    }
    .twitter {
      color: #1DA1F2;
      &:hover {
        opacity: 0.5;
      }
    }
    .mail {
      color: #DB4437;
    }
    }
  }
}
</style>