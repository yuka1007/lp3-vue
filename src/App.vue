
<template>
  <div id="app">
    <CommonHeader></CommonHeader>
     <div id="firstview">
      <p class="catchcopy">機械ではできない仕事を</p>
      <div class="news-flex">
        <div class="news-content">
          <p class="news_date">2019/01/01</p>
          <p class="news_title">
            ニュースタイトルがここには入ります。3月の決算報告書
          </p>
        </div>
        <div class="news-icon">news</div>
      </div>
    </div>
    <main>
      <div class="mission">
        <div class="mission-content">
          <h2 class="mission_title">
            お客様のために進化する成長企業であり続ける
          </h2>
          <p class="mission_text">
            顧客主導型サービスを提供する企業として、お客様の会社経営に必要なサービスと情報を提供し続ける企業支援会社を目指します。企業が現在直面している「勝ち残るため」の戦略を提供できる会社として、ホームページをはじめ、各種マーケティングをご提供いたします。
          </p>
          <a href="" class="common-btn mission-btn">ミッション詳細</a>
        </div>
        <div class="mission-img">
          <img src="./assets/mission-img.jpg" alt="" width="400" height=""/>
        </div>
      </div>
      <div class="service">
        <h2 class="service-title section-title">service</h2>
        <div class="service-content">
          <div class="service-img">
            <img src="./assets/service2.jpg" alt="" width="600" height="400"/>
          </div>
          <div class="service-content_inner">
            <h3 class="mgb-15">web制作事業</h3>
            <p class="mgb-15">コーチングのミッション</p>
            <p class="mgb-15">
              ユーザーが求める物を分析し、ユーザビリティを備えた最適なサイトを提供。建設業から美容、ブライダル、飲食店まで多種多様な業種の制作実績があります
            </p>
            <a href="" class="common-btn service-btn">サービス詳細</a>
          </div>
        </div>
        <div class="service-content">
          <div class="service-img service-img_second">
            <img src="./assets/service1.jpg" alt="" width="600" height="400"/>
          </div>
          <div class="service-content_inner service-content_inner-second">
            <h3 class="mgb-15">web制作事業</h3>
            <p class="mgb-15">コーチングのミッション</p>
            <p class="mgb-15">
              ユーザーが求める物を分析し、ユーザビリティを備えた最適なサイトを提供。建設業から美容、ブライダル、飲食店まで多種多様な業種の制作実績があります
            </p>
            <a href="" class="common-btn service-btn">サービス詳細</a>
          </div>
        </div>
      </div>
      <div class="company">
        <div class="recruit-company flex">
          <div class="recruit-company_size company-img">
            <h2 class="company-title section-title">
              company<br /><span>会社概要</span>
            </h2>
          </div>
          <div class="recruit-company_size recruit-img">
            <h2 class="company-title section-title">
              recruit<br /><span>採用情報</span>
            </h2>
          </div>
        </div>
      </div>
      <div class="faq">
        <h2 class="faq-title">FAQ</h2>
        <p class="faq-title-jp">良くある質問</p>
      </div>
      <div class="contact">
        <h2 class="contact-title section-title">
          contact<br /><span>お問い合わせ</span>
        </h2>
        <p class="contact-subtitle section-title">
          お気軽にお問い合わせください。
        </p>
        <p class="contact-text">
          資料請求・お問い合わせなどなんでも気軽にお問い合わせください。お仕事のご連絡もお問い合わせページに飛んでいただいて、入力フォームにご記入お願いいたします。
        </p>
        <a href="" class="common-btn contact-btn">お問い合わせへ</a>
      </div>
    </main>

    <CommonFooter></CommonFooter>
  </div>
</template>

<script>
import CommonHeader from "./components/CommonHeader.vue";
import CommonFooter from "./components/CommonFooter.vue";
export default {
  components: {
    CommonHeader,
    CommonFooter
  }
};
</script>

<style scoped>
html, body, div, span, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
abbr, address, cite, code,
del, dfn, em, img, ins, kbd, q, samp,
small, strong, sub, sup, var,
b, i,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, figcaption, figure,
footer, header, hgroup, menu, nav, section, summary,
time, mark, audio, video {
  margin:0;
  padding:0;
  border:0;
  outline:0;
  font-size:100%;
  vertical-align:baseline;
  background:transparent;
}

body {
  line-height:1;
}

article,aside,details,figcaption,figure,
footer,header,hgroup,menu,nav,section {
  display:block;
}

nav ul {
  list-style:none;
}

blockquote, q {
  quotes:none;
}

blockquote:before, blockquote:after,
q:before, q:after {
  content:'';
  content:none;
}

a {
  margin:0;
  padding:0;
  font-size:100%;
  vertical-align:baseline;
  background:transparent;
}

/* change colours to suit your needs */
ins {
  background-color:#ff9;
  color:#000;
  text-decoration:none;
}

/* change colours to suit your needs */
mark {
  background-color:#ff9;
  color:#000;
  font-style:italic;
  font-weight:bold;
}

del {
  text-decoration: line-through;
}

abbr[title], dfn[title] {
  border-bottom:1px dotted;
  cursor:help;
}

table {
  border-collapse:collapse;
  border-spacing:0;
}

/* change border colour to suit your needs */
hr {
  display:block;
  height:1px;
  border:0;
  border-top:1px solid #cccccc;
  margin:1em 0;
  padding:0;
}

input, select {
  vertical-align:middle;
}
/*ここまでがリセットcss*/

#firstview {
  height: 100px;
  background: (./assets/eyecatch.jpg);
  background-size: cover;
  background-position: center;
  position: center;
  z-index: 999;
}

.catchcopy {
  position: absolute;
  top: 50%;
  left: 10%;
  font-size: 60px;
  font-style: italic;
  font-weight: bold;
  color: #fff;
  line-height: 1;
}

/*------------------------*/
/*         news           */
/*------------------------*/
.news {
  position: absolute;
  bottom: 0;
  right: 0;
  width: 50%;

}
.news-content {
  background: #fff;
  width: 80%;
  height: 70px;
}

.news_date {
  padding-left: 5px;
}

.news_title {
  padding: 0 15px;
  margin: 100px 20px 10px 200px,
}
.news-icon {
  background: #000;
  width: 20%;
  height: 70px;
  line-height: 70px;
  text-align: center;
  color: #fff;
  z-index: 9;
}
.news-flex {
  margin: -200px -100px 0 800px;
  z-index: 999;
  position: relative;
}


/*------------------------*/
/*         mission        */
/*------------------------*/

.mission {
  position: relative;
  background: #000;
  margin: 40px 0 50px 0;
  z-index: 9;
  height: 500px; 
}

.mission-content {
  padding: 10% 0 60% 20%;
  box-sizing: border-box;
  width: 70%;
}

.mission_title,
.mission_text {
  margin-bottom: 30px;
  color: #fff;
  position: relative;
  z-index: 10;
}

.mission_title {
  font-size: 30px;
}

/*ここのマージンでミッションの黒の幅変わる*/
.mission-img {
  text-align:right;
  width: 300px;
  height: 60px;
  margin: -70% 10% 30% 50%;
  position: relative;
}

.mission-btn {
  color:black;
  background: white;
  border: 1px solid #fff;
  padding: 15px;
  text-decoration: none;
}

/*------------------------*/
/*         service        */
/*------------------------*/
.service {
  background: #e5e5e5;
  padding: 100px 100px 400px 0; 
}

.service-title {
  text-align: center;
  padding: 20px 0 0 0;
  font-size: 40px;
}

.service-content {
  position: relative;
  padding-bottom: 5%;
}

.service-img {
  width: 80px;
}

.service-img_second {
  margin: 0% 500% 0% 1%;
}

.service-content_inner {
  position: absolute;
  top: 5%;
  left: 50%;
  background: #fff;
  width: 45%;
  height: 70%;
  padding: 5% 10% 5% 10%;
  box-sizing: border-box;
}

.service-content_inner-second {
  left: 10%;
  background: #fff;
  margin: 15px 10px 10px 5px;
  display:block;

}

.service-img_second {
  position: absolute;
  left: 45%;
}

.service-btn {
  border: 1px solid #000;
  margin: 30px 30px 20px 0;
  color: black;
  padding: 10px;
  text-decoration: none;
  
}

/*------------------------*/
/*        recruit         */
/*------------------------*/
.company {
  margin: 25% 2%;
}

.recruit-company {
  display: flex;
}

.recruit-company_size {
  width: 48%;
  height: 300px;
  position: relative;
}

.company-img {
  background: url(./assets/company.jpeg)center/cover no-repeat;
}

.recruit-img {
  background: url(./assets/recruit.jpg)center/cover no-repeat;
}

.company-title {
  text-align: center;
  color: #fff;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.company-title span {
  color: #fff;
}

/*------------------------*/
/*        faq             */
/*------------------------*/
.faq {
  width: 70%;
  background: #000;
  margin: 0 auto 10%;
  padding: 50px;
}

.faq-title,
.faq-title-jp {
  display: inline-block;
  color: #fff;
}

.faq-title {
  font-size: 40px;
  width: 10%;
}

.faq-title-jp {
  font-size: 20px;
  width: 80%;
  text-align: center;
}

/*------------------------*/
/*        contact         */
/*------------------------*/
.contact {
  background: url(./assets/contact-bg.jpg) center/cover no-repeat;
  padding: 10%;
  margin: 10% 0 0 0;
}

.contact-title,
.contact-title span,
.contact-subtitle,
.contact-text {
  color: #fff;
  text-align: center;
}

.contact-title,
.contact-subtitle,
.contact-text {
  margin-bottom: 40px;
}

.contact-btn {
  text-align: center;
  margin: 360px;
  background: none;
  border: 1px solid #fff;
  color: #fff;
  padding: 10px;
  text-decoration: none;
}

</style>
