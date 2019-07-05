<template>
  <div class="contents">
    <div class="projects">
      <b-card class="mb-3">
        <div class="project">
          <div class="project__image">
            <img src="../assets/100dreams.png" width="400px" height="300px">
          </div>
          <div class="project__text">
            <p><a href="" target="_blank">100dreams</a><a href="https://github.com/fumikao/dreams-100" target="_blank" class="github"><font-awesome-icon :icon="['fab', 'github']" size="2x" /></a></p>
            <p>人生でやりたいこと100のリストを管理・共有できるサイトです。<br>非同期通信・公開/非公開・ドラッグ&ドロップで並べ替えができます。</p>
            <p>テスト用アカウント<br>Email：／Password：</p>
            <p>使用技術<br>Ruby、Rails、Sass、jQuery、MySQL、Heroku</p>
          </div>
        </div>
      </b-card>

      <b-card class="mb-3">
        <div class="project">
          <div class="project__image">
            <img src="../assets/chat-space.png" width="400px" height="300px">
          </div>
          <div class="project__text">
            <p><a href="http://52.196.249.9" target="_blank">Chat Space</a><a href="https://github.com/fumikao/chat-space" target="_blank" class="github"><font-awesome-icon :icon="['fab', 'github']" size="2x" /></a></p>
            <p>多人数でチャットができるサイトです。<br>インクリメンタルサーチ、非同期送信、自動更新などの機能を実装しました。</p>
            <p>テスト用アカウント<br>Email：test@test.com／Password：testtest</p>
            <p>使用技術<br>Ruby、Rails、Sass、jQuery、MySQL、AWS</p>
          </div>
        </div>
      </b-card>

      <b-card class="mb-3">
        <div class="project">
          <div class="project__image">
            <img src="../assets/portfolio.png" width="400px" height="300px">
          </div>
          <div class="project__text">
            <p><a href="" target="_blank">Portfolio</a><a href="https://github.com/fumikao/portfolio" target="_blank" class="github"><font-awesome-icon :icon="['fab', 'github']" size="2x" /></a></p>
            <p>このサイトです。<br>Homeの背景画像は自分が撮影した写真です。<br>Vue.jsを使ってSPAで構成しました。</p>
            <p>使用技術<br>Vue.js、Firebase</p>
          </div>
        </div>
      </b-card>

      <b-card class="mb-3">
        Comming Soon...
      </b-card>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.projects {
  margin: 30px 50px;
  a {
    border-bottom: dashed 1px #007bff;
    text-decoration: none;
    font-weight: bold;
    margin: 10px;
  }
  .github {
    border: none;
    color: black;
    &:hover {
      opacity: 0.5;
    }
  }
}

.project {
  display: flex;
  justify-content: space-between;
  &__text {
    margin: 10px;
    text-align: center;
  }
}
</style>