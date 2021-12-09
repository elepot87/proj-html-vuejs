<template>
  <div class="big-container">
    <header class="d-flex">
      <div class="left d-flex align-items-center">
        <img
          :src="require(`@/assets/images/logo-svg.svg`)"
          alt="logo"
          class="logo-header"
        />
      </div>
      <div class="right d-flex justify-content-end align-items-center">
        <ul class="main-menu d-flex">
          <li class="menu-item"><a href="#">Home</a></li>
          <li class="menu-item"><a href="#">Culinary History</a></li>
          <li class="menu-item"><a href="#">Our Team</a></li>
          <li class="menu-item"><a href="#">Our Menu</a></li>
          <li class="menu-item"><a href="#">Takeout</a></li>
          <li class="menu-item"><a href="#">Bulletin</a></li>
          <li class="menu-item"><a href="#">Reservations</a></li>
          <li class="menu-item">
            <a href="#"><i class="fas fa-shopping-cart"></i></a>
          </li>
        </ul>
      </div>
    </header>
    <section class="hero d-flex">
      <div class="hero-left">prova</div>
      <div class="hero-right">
        <!-- <img
          :src="require(`@/assets/images/slider52x.jpg`)"
          alt="sfondo-hero"
          class="img-hero"
        /> -->
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped lang="scss">
@import "@/styles/header";
</style>
