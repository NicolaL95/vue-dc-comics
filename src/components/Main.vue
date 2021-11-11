<template>
  <main id="site_main">
    <div class="content">
      <p class="content_here">--&#62; Content goes here &#60;--</p>
    </div>
    <div class="generic_bg">
      <div class="generic_container">
        <div class="generic_content">
          <img src="../assets/buy-comics-digital-comics.png" alt="" />
          <p>Digital Comics</p>
        </div>
        <div class="generic_content">
          <img src="../assets/buy-comics-merchandise.png" alt="" />
          <p>DC MERCHANDISE</p>
        </div>
        <div class="generic_content">
          <img src="../assets/buy-comics-subscriptions.png" alt="" />
          <p>SUBSCRIPTION</p>
        </div>
        <div class="generic_content">
          <img src="../assets/buy-comics-shop-locator.png" alt="" />
          <p>COMIC SHOP LOCATOR</p>
        </div>
        <div class="generic_content">
          <img src="../assets/buy-dc-power-visa.svg" alt="" />
          <p>DC POWER VISA</p>
        </div>
      </div>
    </div>
    <div class="bg_table">
      <div class="dc_table">
        <div class="table">
          <p class="table_title">DC COMICS</p>
          <p class="table_link">Characters</p>
          <p class="table_link">Comics</p>
          <p class="table_link">Movies</p>
          <p class="table_link">TV</p>
          <p class="table_link">Games</p>
          <p class="table_link">Videos</p>
          <p class="table_link">News</p>
        </div>

        <div class="table">
          <p class="table_title">SHOP</p>
          <p class="table_link">Shop DC</p>
          <p class="table_link">Shop DC Collectibles</p>
        </div>

        <div class="table">
          <p class="table_title">DC</p>
          <p class="table_link">Terms Of Use</p>
          <p class="table_link">Privacy policy (New)</p>
          <p class="table_link">Ad Choices</p>
          <p class="table_link">Advertising</p>
          <p class="table_link">Jobs</p>
          <p class="table_link">Subscription</p>
          <p class="table_link">Talent Workshops</p>
          <p class="table_link">CPSC Certificates</p>
          <p class="table_link">Ratings</p>
          <p class="table_link">Shop Help</p>
          <p class="table_link">Coontact Us</p>
        </div>

        <div class="table">
          <p class="table_title">SITES</p>
          <p class="table_link">DC</p>
          <p class="table_link">MAD Magazine</p>
          <p class="table_link">DC kids</p>
          <p class="table_link">DC Universe</p>
          <p class="table_link">DC Power Visa</p>
        </div>
      </div>
      <div class="logo_container">
        <img class="logo" src="../assets/dc-logo-bg.png" alt="" />
      </div>
    </div>
  </main>
</template>

<script>
</script>

<style lang="scss">
.content_here {
  background-color: #1c1c1c;
  color: white;
  font-size: 1.3rem;
  padding: 40px 200px;
}

.generic_container {
  display: flex;
  justify-content: center;
  padding: 30px 0;
  position: relative;
  z-index: 2;
}

.generic_bg {
  background-color: #0282f9;
}

.generic_content {
  display: flex;
  align-items: center;
  color: white;
  font-size: 0.9rem;
  padding-right: 60px;
  img {
    height: 40px;
  }
  p {
    padding-left: 10px;
  }
}
.bg_table {
  background-image: url("../assets/footer-bg.jpg");
  position: relative;
}
.table_title {
  color: white;
  padding-bottom: 10px;
}

.dc_table {
  padding: 30px 0 0 200px;
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  height: 300px;
  width: 25%;
}
.table {
  width: 160px;
  padding-bottom: 15px;
  p {
    width: 160px;
  }
}
.table_link {
  color: #797979;
}
.logo_container {
  position: absolute;
  z-index: 1;
  right: 25rem;
  bottom: -4rem;
  img {
    width: 27rem;
    z-index: 1;
  }
}
</style>