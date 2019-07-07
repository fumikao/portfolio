<template>
  <div class="contents">
    <div class="projects">
      <div class="row">
          <div class="col-lg-9 col-md-12"><br>
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
                            <p>（メンテナンス中です。）</p>
                            <p>人生でやりたいこと100のリストを管理・共有できるサイトです。<br>いいね・公開/非公開・ドラッグ&ドロップで並べ替え等の機能があります。</p>
                            <p>使用技術<br>Ruby、Rails、Sass、jQuery、MySQL、Heroku</p>  
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
                            <p>テスト用アカウント<br>Email：test@test.com／Password：testtest</p>
                            <p>使用技術<br>Ruby、Rails、Sass、jQuery、MySQL、AWS</p>
                          </p>
                          <a href="https://github.com/fumikao/chat-space" target="_blank" class="github"><font-awesome-icon :icon="['fab', 'github']" size="2x" /></a>
                      </div>
                  </div>
                </div>
                <div class="card-deck">
                  <div class="card" style="width: 250px;">
                      <div class="card-img-top" style="height: 220px; background: #EEE;">
                        <img src="../assets/portfolio.png"height="220px">
                      </div>
                      <div class="card-body">
                          <h5 class="card-title">
                            <a href="https://fumika-portfolio.firebaseapp.com" target="_blank">Portfolio</a>
                          </h5>
                          <p class="card-text">
                            <p>このサイトです。<br>Homeの背景画像は自分が撮影した写真です。<br>Vue.jsを使ってSPAで構成しました。</p>
                            <p>使用技術<br>Vue.js、Firebase</p>
                          </p>
                          <a href="https://github.com/fumikao/portfolio" target="_blank" class="github"><font-awesome-icon :icon="['fab', 'github']" size="2x" /></a>
                      </div>
                  </div>
                  <div class="card" style="width: 250px;">
                      <div class="card-img-top" style="height: 220px; background: #EEE;"></div>
                      <div class="card-body">
                        <h5 class="card-title">Comming Soon...</h5>
                          <p class="card-text"></p>
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
</style>