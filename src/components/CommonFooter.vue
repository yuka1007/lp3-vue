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
        <small class="footer-last">Copyright 2019 estra inc. All Rights Reserved.</small>
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
  color: white;
}
.header-logo{
  margin: 0 0 0 8%;
  color: white;
}

.header-nav ul {
  display: flex;
  margin: -12% 50% -5% 45%;
  padding: 5% 5% 10% 5%;
  text-decoration: none;
  color: white;
  margin-right: 20%;

}

.header-nav a {
  padding: 5% 0%;
  color: white;
  margin-right: 10%;
  text-decoration: none;
  margin-right: 20%;
}

.header-nav li {
  text-decoration: none;
  margin-right: 10%;
  display: flex;
}
  
.footer-last {
  margin: 0 30%; 
}

</style>