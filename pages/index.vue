<template lang="pug">
div
  .jumbotron.jumbotron-fluid.bg-children
    .container.text-center
      h1.display-4 すべてのアウトローな子ども達へ
      p.lead 常識は自分で作る、
  #intro.bg-white
    .container
      .row
        .col-sm-12.col-md-10.offset-md-1.text-center
          h2.mb-4 「わっちゃ」とは
          p 学校にいけない子供たちを持つ親御さんの不安を取り除く第一歩として「働き稼ぐ力をつける」学校です。
          p 既存の支援サービスとの大きな違いは「学校に戻ることを目的としない」支援です。<br>そして「働くことで得られる幸せ」を提供し、義務教育に通えない子供たちにも「稼ぐ力」をつけることを目的とします。
  //- #feature.bg-secondary
    .container
      .row.mb-5
        .col-md-12.text-center
          h2 「わっちゃ」の特徴
      .row
        .col-md-4.col-sm-12
          .feature-photo
            img(src="http://placehold.jp/300x300.png", alt="alt" width="200").image-circle
          .feature-content
            h4.text-center 特徴が入ります
            p 本文が入ります本文が入ります本文が入ります本文が入ります
        .col-md-4.col-sm-12
          .feature-photo
            img(src="http://placehold.jp/300x300.png", alt="alt" width="200").image-circle
          .feature-content
            h4.text-center 特徴が入ります
            p 本文が入ります本文が入ります本文が入ります本文が入ります
        .col-md-4.col-sm-12
          .feature-photo
            img(src="http://placehold.jp/300x300.png", alt="alt" width="200").image-circle
          .feature-content
            h4.text-center 特徴が入ります
            p 本文が入ります本文が入ります本文が入ります本文が入ります
  #price
    .container
      .row
        .col-md-4
          .card-deck.mb-3.text-center
            .card.shadow-sm
              .card-header
                h4.my-0.font-weight-normal プラン１
              .card-body
                h1.card-title.pricing-card-title
                  | ￥0 
                  small.text-muted / 月
                ul.list-unstyled.mt-3.mb-4
                  li 10 ユーザーを含む
                  li 2 GBのストレージ
                  li メールサポート
                  li ヘルプセンターへのアクセス
                button.btn.btn-lg.btn-block.btn-primary(type="button") 今すぐ申し込む
        .col-md-4
          .card.shadow-sm.text-center
            .card-header
              h4.my-0.font-weight-normal プラン２
            .card-body
              h1.card-title.pricing-card-title
                | ￥1500 
                small.text-muted / 月
              ul.list-unstyled.mt-3.mb-4
                li 20 ユーザーを含む
                li 10 GBのストレージ
                li 優先メールサポート
                li ヘルプセンターへのアクセス
              button.btn.btn-lg.btn-block.btn-primary(type="button") 今すぐ申し込む
        .col-md-4
          .card.shadow-sm.text-center
            .card-header
              h4.my-0.font-weight-normal プラン１
            .card-body
              h1.card-title.pricing-card-title
                | ￥2900 
                small.text-muted / 月
              ul.list-unstyled.mt-3.mb-4
                li 30 ユーザーを含む
                li 15 GBのストレージ
                li 電話とメールのサポート
                li ヘルプセンターへのアクセス
              button.btn.btn-lg.btn-block.btn-primary(type="button") 今すぐ申し込む
  #apply
    form(action="" method="method")
      .container
        .row
          .col-md-10.offset-md-1.col-sm-12
            .form-group
              label(for="form-name") お名前
              input#form-name.form-control(type="text" placeholder="例）山田　花子")
            .form-group
              label(for="form-child") 子どもの名前
              input#form-child.form-control(type="text" placeholder="例）山田　花子")
            .form-group
              label(for="form-email") メールアドレス
              input#form-email.form-control(type="text" placeholder="例）yamada@example.com")
            .form-footer.text-center.mt-5
              button.btn.btn-primary.btn-lg(type='submit') 送信する
</template>

<style lang="scss" scoped>
.container{
  margin-top: 3em;
  margin-bottom: 3em;
}

.bg-children{
  background-image: url('~assets/img/11070009973.jpg');
  background-repeat: no-repeat;
  background-position: 0 bottom;
  background-size: cover;
  color: #FFF;
  text-shadow: rgba(#000, 0.3);
  height: 500px;
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
  &:before{
    content: "";
    display: block;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(#000, .3);
  }

  & > *{
    position: relative;
    zi: 10px;
  }
}

.bg-secondary{
  background-color: #EEE !important;
  padding-top: 1em;
  padding-bottom: 1em;
}

.image-circle{
  border-radius: 100%;
}

.feature-photo{
  margin-bottom: 1em;
  text-align: center;
}

.feature-content{
  
}

.btn-lg{
  width: 280px;
}

</style>

<script>
export default {}
</script>
