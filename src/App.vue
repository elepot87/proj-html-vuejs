<template>
  <div id="app">
    <Header :navLinksNew="navLinks" />
    <Main />
    <Footer :navFooterIcons="footerIcons" />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Main from "@/components/Main.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer,
  },
  data() {
    return {
      navLinks: [
        {
          text: "Home",
          url: "#",
          button: false,
          icon: false,
        },
        {
          text: "Culinary history",
          url: "#",
          button: false,
          icon: false,
        },
        {
          text: "Our Team",
          url: "#",
          button: false,
          icon: false,
        },
        {
          text: "Our Menu",
          url: "#",
          button: false,
          icon: false,
        },
        {
          text: "Takeout",
          url: "#",
          button: true,
          icon: false,
        },
        {
          text: "Bulletin",
          url: "#",
          button: false,
          icon: false,
        },
        {
          text: "Reservation",
          url: "#",
          button: false,
          icon: false,
        },
        {
          text: "",
          url: "#",
          button: false,
          icon: true,
        },
      ],
      footerIcons: [
        {
          nameIcon: "fab fa-facebook-f",
          visibility: true,
        },
        {
          nameIcon: "fab fa-twitter",
          visibility: true,
        },
        {
          nameIcon: "fab fa-youtube",
          visibility: true,
        },
        {
          nameIcon: "fab fa-instagram",
          visibility: true,
        },
        {
          nameIcon: "fab fa-linkedin-in",
          visibility: true,
        },
      ],
    };
  },
};
</script>

<style lang="scss">
@import "@/styles/global";
@import "@/styles/custom.scss";
@import "../node_modules/bootstrap/scss/bootstrap.scss";
</style>
