<template>
  <div class="big-container">
    <!-- HEADER -->
    <header class="d-flex">
      <!-- sinistra -->
      <div class="left d-flex align-items-center">
        <img
          :src="require(`@/assets/images/logo-svg.svg`)"
          alt="logo"
          class="logo-header"
        />
      </div>
      <!-- destra -->
      <nav class="right d-flex justify-content-start align-items-center">
        <ul class="main-menu d-flex">
          <li
            class="menu-item d-flex"
            v-for="(link, index) in navLinks"
            :key="`link-${index}`"
          >
            <a :href="link.url"
              >{{ link.text }}
              <span class="badge bg-secondary" v-if="link.button !== false"
                >New</span
              >
            </a>
          </li>
          <!-- <li class="menu-item"><a href="#">Culinary History</a></li>
          <li class="menu-item"><a href="#">Our Team</a></li>
          <li class="menu-item"><a href="#">Our Menu</a></li>
          <li class="menu-item">
            <a href="#" class="d-flex"
              >Takeout
              <span class="badge bg-secondary">New</span>
            </a>
          </li>
          <li class="menu-item"><a href="#">Bulletin</a></li>
          <li class="menu-item"><a href="#">Reservations</a></li>
          <li class="menu-item">
            <a href="#"><i class="fas fa-shopping-cart"></i></a>
          </li> -->
        </ul>
      </nav>
    </header>
    <!--    HERO SECTION -->
    <section class="hero d-flex">
      <div class="hero-left">
        <div class="container-subtitle d-flex align-items-center">
          <div class="subtitle">
            <span> the best table in town </span>
          </div>
        </div>
        <div class="container-text">
          <h1>fine dining experience</h1>
          <p>
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Minus,
            iure? Laboriosam rerum non saepe quisquam fuga.
          </p>
          <button class="button-main">explore the menu</button>
        </div>
      </div>
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
  data() {
    return {
      navLinks: [
        {
          text: "Home",
          url: "#",
          button: false,
        },
        {
          text: "Culinary history",
          url: "#",
          button: false,
        },
        {
          text: "Our Team",
          url: "#",
          button: false,
        },
        {
          text: "Our Menu",
          url: "#",
          button: false,
        },
        {
          text: "Takeout",
          url: "#",
          button: true,
        },
        {
          text: "Bulletin",
          url: "#",
          button: false,
        },
        {
          text: "Reservation",
          url: "#",
          button: false,
        },
      ],
    };
  },
};
</script>

<style scoped lang="scss">
@import "@/styles/header";
</style>
