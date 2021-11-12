<template>
  <footer id="site_footer">
    <div class="button_container footer_format">
      <button>SIGN-UP NOW!</button>
    </div>
    <nav class="link_container footer_format">
      <p>Follow Us</p>
      <a href=""><img src="../assets/footer-facebook.png" alt="" /></a>
      <a href=""><img src="../assets/footer-twitter.png" alt="" /></a>
      <a href=""><img src="../assets/footer-youtube.png" alt="" /></a>
      <a href=""><img src="../assets/footer-pinterest.png" alt="" /></a>
      <a href=""><img src="../assets/footer-periscope.png" alt="" /></a>
    </nav>
  </footer>
</template>

<script>
</script>

<style lang="scss">
#site_footer {
  display: flex;
  background-color: #303030;
  z-index: 2;
  position: relative;
}

.footer_format {
  width: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 20px 0 10px;
  button {
    border: 2px solid #0282f9;
    padding: 7px;
    color: white;
    background-color: transparent;
  }
  p {
    color: #0282f9;
    padding-right: 10px;
  }
  a {
    padding: 7px;
    img {
      height: 25px;
    }
  }
}
</style>