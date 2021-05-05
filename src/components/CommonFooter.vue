<template>
  <footer class="top-footer">
        <div class="footer-bar">
          <div class="flex">
            <h1 class="header-logo">estra inc.</h1>
            <nav class="header-nav">
              <ul>
                <li><a href="#">home</a></li>
                <li><a href="#">about</a></li>
                <li><a href="#">service</a></li>
                <li><a href="#">works</a></li>
                <li><a href="#">price</a></li>
                <li><a href="#">contact</a></li>
              </ul>
            </nav>
          </div>
        </div>
        <small>Copyright 2019 estra inc. All Rights Reserved.</small>
      </footer>
</template>

<style scoped>
.footer-bar {
  height: 70px;
  line-height: 70px;
}

.top-footer {
  background: rgb(14, 13, 13);
  text-align: center;
  color: white;
}
.header-logo{
  text-align: left;
  margin: 0 0 0 5%;
}

  .header-nav li{
    display: inline-block;
    margin-left: 70px;
    color:#fff;
  }
  
.flex {
  display: flex;
}

  .catchcopy {
    top: 50%;
    left: 50%;
    width: 80%;
    text-align: center;
    transform: translate(-50%, -50%);
  }
  .news {
    width: 100%;
  }
  .mission-content {
    padding: 10% 0;
    margin: 0 auto;
  }
  .service-content_inner {
    width: 60%;
    left: 10%;
  }
  .service-img {
    width: 70%;
    margin-left: 30%;
  }
  .service-img_second {
    margin: 0 30% 0 0;
  }
  .service-content_inner-second {
    left: 30%;
  }
  .service-content {
    margin: 0 auto;
  }
  .service-content_inner {
    width: 90%;
    position: inherit;
    background: rgba(12, 12, 12, 0.8);
    left: 5%;
  }
  .service-img {
    width: 90%;
    margin: 0 auto;
  }
  .recruit-company_size {
    width: 100%;
  }
  .faq-title {
    font-size: 30px;
  }
  .top-footer {
    margin: 0;
    width: 100%;
    text-align: center;
  }
</style>