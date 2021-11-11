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
    <div class="dc_table">
      <table>
        <thead>
          <tr>
            <th>DC COMICS</th>
            <th>SHOP</th>
            <th>DC</th>
            <th>SITES</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Characters</td>
            <td>Comics</td>
            <td>Movies</td>
            <td>TV</td>
            <td>Games</td>
            <td>Videos</td>
            <td>News</td>
          </tr>
          <tr>
            <td>Shop DC</td>
            <td>Shop DC Coollectibles</td>
          </tr>
        </tbody>
        <tbody>
          <tr>
            <td>Terms Of Use</td>
            <td>Privacy policy (New)</td>
            <td>Ad Choices</td>
            <td>Advertising</td>
            <td>Jobs</td>
            <td>Subscription</td>
            <td>Talent Workshops</td>
            <td>CPSC Certificates</td>
            <td>Ratings</td>
            <td>Shop Help</td>
            <td>Coontact Us</td>
          </tr>
        </tbody>
        <tbody>
          <tr>
            <td>DC</td>
            <td>MAD Magazine</td>
            <td>DC kids</td>
            <td>DC Universe</td>
            <td>DC Power Visa</td>
          </tr>
        </tbody>
      </table>
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
.dc_table {
  background-image: url("../assets/footer-bg.jpg");
}
th {
  color: white;
}

td {
  color: #797979;
}
</style>