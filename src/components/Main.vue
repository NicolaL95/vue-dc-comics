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
export default {
  data() {
    return {
      comics: [
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
          price: "$19.99",
          series: "Action Comics",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
          price: "$3.99",
          series: "American Vampire 1976",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
          price: "$16.99",
          series: "Aquaman",
          type: "graphic novel",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
          price: "$2.99",
          series: "Batgirl",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
          price: "$3.99",
          series: "Batman",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
          price: "$2.99",
          series: "Batman Beyond",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
          price: "$3.99",
          series: "Batman/Superman",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
          price: "$4.99",
          series: "Batman/Superman Annual",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
          price: "$5.99",
          series: "Batman: The Joker War Zone",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
          price: "$6.99",
          series: "Batman: Three Jokers",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
          price: "$4.99",
          series: "Batman: White Knight Presents: Harley Quinn",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
          price: "$16.99",
          series: "Catwoman",
          type: "graphic novel",
        },
      ],
    };
  },
};
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
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
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