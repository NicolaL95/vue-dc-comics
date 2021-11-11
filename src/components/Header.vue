<template>
  <header id="site_header">
    <div class="img_container header_format">
      <img src="../assets/dc-logo.png" alt="" />
    </div>
    <nav class="link_container header_format">
      <a href="">CHARACTERS</a> <a href="">COMICS</a> <a href="">MOVIES</a>
      <a href="">TV</a> <a href="">GAMES</a> <a href="">COLLECTIBLES</a>
      <a href="">VIDEOS</a> <a href="">FANS</a> <a href="">NEWS</a>
      <a href="">SHOP</a>
    </nav>
  </header>
</template>

<script>
</script>

<style lang="scss">
#site_header {
  display: flex;
  .header_format {
    width: 50%;
    display: flex;
  }
  .img_container {
    justify-content: center;
    img {
      width: 55px;
      margin: 30px 0 15px;
    }
  }
  .link_container {
    align-items: center;
    a {
      text-decoration: none;
      padding: 15px;
      font-size: 0.9rem;
      color: black;
    }
  }
}
</style>