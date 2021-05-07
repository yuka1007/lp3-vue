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
  color: white;
}

.top-footer {
  background: rgb(14, 13, 13);
  text-align: center;
  color: white;
}
.header-logo{
  text-align: left;
  margin: 0 0 0 8%;
  color: white;
}

.header-nav a {
  color: white;
}

  .header-nav li{
    display: inline-block;
    margin: 0 8% 0 2%;
    color:#fff;
  }
  
.flex {
  display: flex;
}


</style>