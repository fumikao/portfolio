<template>
  <div class="contents">
    <div class="projects">
      <div class="row">
          <div class="projects__content col-lg-9 col-md-12">
              <div class="card-deck">
                  <div class="card" style="width: 250px;">
                      <div class="card-img-top" style="height: 220px; background: #EEE;">
                        <img src="../assets/100dreams.png" height="220px">
                      </div>
                      <div class="card-body">
                          <h5 class="card-title">
                            <a href="https://dreams100.herokuapp.com/" target="_blank">100dreams</a>
                          </h5>
                          <p class="card-text">
                            <p>「人生でやりたいこと100のリスト」を管理・共有できるサイトです。<br>いいね、公開/非公開、ドラッグ&ドロップで並べ替えなどの機能を実装しました。</p>
                            <p><span>テスト用アカウント</span><br>Email：test@test.com／Password：testtest</p>
                            <span>使用技術</span><br>Ruby、Rails、Sass、jQuery、MySQL、Heroku
                          </p>
                          <a href="https://github.com/fumikao/dreams-100" target="_blank" class="github"><font-awesome-icon :icon="['fab', 'github']" size="2x" /></a>
                      </div>
                  </div>
                  <div class="card" style="width: 250px;">
                      <div class="card-img-top" style="height: 220px; background: #EEE;">
                        <img src="../assets/chat-space.png" height="220px">
                      </div>
                      <div class="card-body">
                          <h5 class="card-title">
                            <a href="http://52.196.249.9" target="_blank">Chat Space</a>
                          </h5>
                          <p class="card-text">
                            <p>多人数でチャットができるサイトです。<br>インクリメンタルサーチ、非同期送信、自動更新などの機能を実装しました。</p>
                            <p><span>テスト用アカウント</span><br>Email：test@test.com／Password：testtest</p>
                            <span>使用技術</span><br>Ruby、Rails、Sass、jQuery、MySQL、AWS
                          </p>
                          <a href="https://github.com/fumikao/chat-space" target="_blank" class="github"><font-awesome-icon :icon="['fab', 'github']" size="2x" /></a>
                      </div>
                  </div>
                </div>
                <div class="card-deck">
                  <div class="card" style="width: 250px;">
                      <div class="card-img-top" style="height: 220px; background: #EEE;">
                        <img src="../assets/vue-practice.png"height="220px">
                      </div>
                      <div class="card-body">
                          <h5 class="card-title">
                            <a href="https://fumika-vuejs-practice.firebaseapp.com/" target="_blank">Vue.js Practice</a>
                          </h5>
                          <p class="card-text">
                            <p>Vue.jsに慣れるために小ネタをいくつか作ってサイトにしました。</p>
                            <span>使用技術</span><br>Vue.js、Firebase</p>
                          </p>
                          <a href="https://github.com/fumikao/vue-practice" target="_blank" class="github"><font-awesome-icon :icon="['fab', 'github']" size="2x" /></a>
                      </div>
                  </div>
                  <div class="card" style="width: 250px;">
                    <div class="card-img-top" style="height: 220px; background: #EEE;">
                      <img src="../assets/portfolio.png"height="220px">
                    </div>
                    <div class="card-body">
                      <h5 class="card-title">
                        <a href="https://fumika-portfolio.firebaseapp.com" target="_blank">Portfolio</a>
                      </h5>
                      <p class="card-text">
                        <p>このサイトです。<br>Vue.jsを使ってSPAで構成しました。<br>Homeの背景画像は自分が撮影した写真です。</p>
                        <span>使用技術</span><br>Vue.js、Firebase</p>
                      </p>
                      <a href="https://github.com/fumikao/portfolio" target="_blank" class="github"><font-awesome-icon :icon="['fab', 'github']" size="2x" /></a>
                    </div>
                  </div>
                </div>
                <div class="card-deck">
                  <div class="card" style="width: 250px;">
                      <div class="card-img-top" style="height: 220px; background: #EEE;">
                      </div>
                      <div class="card-body">
                          <h5 class="card-title">
                            Comming Soon...
                          </h5>
                          <p class="card-text">
                          </p>
                      </div>
                  </div>
                  <div class="card" style="width: 250px;">
                      <div class="card-img-top" style="height: 220px; background: #EEE;">
                      </div>
                      <div class="card-body">
                          <h5 class="card-title">
                            Comming Soon...
                          </h5>
                          <p class="card-text">
                          </p>
                      </div>
                  </div>
                </div>
          </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.projects {
  margin: 30px 50px;
  .card {
    min-width: 300px;
    margin: 20px;
  }
  &__content {
    margin: 0 auto;
  }
  a {
    border-bottom: dashed 1px #007bff;
    text-decoration: none;
    font-weight: bold;
    margin: 10px;
  }
  span {
    font-weight: bold;
  }
  .github {
    border: none;
    color: black;
    &:hover {
      opacity: 0.5;
    }
  }
}
</style>