<template lang="pug">
div
  .jumbotron.jumbotron-fluid.bg-children
    .container.text-center
      h1.display-5.mb-5 子どもの「好き」を知っていますか？
      p.lead 「好きを見つけ、働き、稼ぐ力をつける学校」。<br>新しいタイプの学校「わっちゃ」がまもなく開講します。
  #intro.bg-white
    .container
      .row
        .col-sm-12.col-md-10.offset-md-1.text-center
          h2.mb-4 「わっちゃ」とは
          p 学校にいけない子供たちを持つ親御さんの不安を取り除く第一歩として「働き稼ぐ力をつける」学校です。
          p 既存の支援サービスとの大きな違いは「学校に戻ることを目的としない」支援です。<br>そして「働くことで得られる幸せ」を提供し、義務教育に通えない子供たちにも「稼ぐ力」をつけることを目的とします。
  #feature.bg-secondary
    .container
      .row.mb-5
        .col-md-12.text-center
          h2 子どもが体験できること
      .row
        .col-md-4.col-sm-12
          .feature-photo
            img(src="http://placehold.jp/300x300.png", alt="alt" width="200").image-circle
          .feature-content.text-center
            h4 １次産業
            p 農業、林業
        .col-md-4.col-sm-12
          .feature-photo
            img(src="http://placehold.jp/300x300.png", alt="alt" width="200").image-circle
          .feature-content.text-center
            h4 2次産業
            p 製造、建設
        .col-md-4.col-sm-12
          .feature-photo
            img(src="http://placehold.jp/300x300.png", alt="alt" width="200").image-circle
          .feature-content.text-center
            h4 3次産業
            p サービス、小売
  #price
    .container
      .row
        .col-md-6.col-sm-12.offset-md-3
          .text-center
            .card.shadow-sm
              .card-header
                h4.my-0.font-weight-normal 授業料
              .card-body.text-center
                h1.card-title.pricing-card-title 10,000円
                  small （税別）
                  small.text-muted / 月
                ul
                  li 入学金　10,000円
                    small （税別）
                button.btn.btn-lg.btn-danger(type="button") 今すぐ申し込む
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
