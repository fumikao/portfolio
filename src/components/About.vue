<template>
  <div class="contents">
    <div class="about">
      <div class="about__intro">
        <img src="../assets/profile.jpeg" width="100px" height="100px">
        <h3>大林 史佳</h3>
      </div>
      <div class="about__bottom">
        <div class="about__bottom--profile">
          <b-card title="自己紹介" sub-title="">
            <hr>
            <b-card-text>
              はじめまして。大林史佳<a href="https://twitter.com/fumika78143169" target="_blank">(@fumika78143169)</a>と申します。<br>
              岡山県出身、1993年生まれの26歳です。
            </b-card-text>
            <b-card-text>
              京都大学文学部卒業後、大手証券会社の地方総合職として、地元岡山で証券営業を4年間していました。
            </b-card-text>
            <b-card-text>
              もっと自分の強みを活かして楽しい人生にしたい！と一念発起し、上京。<br>プログラミングスクールにてWebエンジニアになるべく学習中です。
            </b-card-text>
            <b-card-text>
              趣味：旅行、カメラ、音楽(クラシック) etc...
            </b-card-text>
            <ul>
              <li><a href="https://fumika23.hatenablog.com/" target="_blank" class="card-link"><font-awesome-icon :icon="['fas', 'blog']" />  Blog</a></li>
              <li><a href="https://www.instagram.com/fu__o/" target="_blank" class="card-link"><font-awesome-icon :icon="['fab', 'instagram']" />  Instagram</a></li>      
            </ul>
          </b-card>
        </div>
        <div class="about__bottom--skill">
          <b-card title="学習中の技術" sub-title="">
            <b-card-text>
              <b-table striped :items="items"></b-table>
            </b-card-text>
          </b-card>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        items: [
          { skill: "HTML&CSS" },
          { skill: "JavaScript/jQuery" },
          { skill: "Ruby/Rails" },
          { skill: "Vue.js" },
          { skill: "MySQL" },
          { skill: "AWS" }
        ]
      }
    }
  }
</script>

<style lang="scss" scoped>
.about {
  margin: 30px;
  &__intro {
    height: 150px;
    margin: 20px;
    img {
      border-radius: 50%;
    }
    h3 {
      line-height: 70px;
    }
  }
  &__bottom {
    margin: 20px;
    &--profile {
      margin-bottom: 10px;
      min-height: 300px;
    }
    &--skil {
      min-height: 300px;
    }
  }
}
</style>