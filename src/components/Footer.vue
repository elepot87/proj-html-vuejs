<template>
  <footer>
    <section class="footer-main">
      <div class="info-footer d-flex justify-content-center align-items-center">
        <img
          :src="require(`@/assets/images/logo-svg.svg`)"
          alt="logo"
          class="logo-footer"
        />
        <p class="text-footer">
          Quam eu proin sit massa condimentum. Volutpat non pulvinar aliquet
          nunc. Quam eu proin sit massa condimentum.
        </p>
        <ul class="icon-list d-flex">
          <li
            class="icon-item"
            v-for="(link, index) in footerIcons"
            :key="`link-footer-icon-${index}`"
          >
            <a href="#"><i :class="link.nameIcon" class="icon-footer"></i></a>
          </li>
          <!-- <li class="icon-item">
            <a href="#"><i class="fab fa-twitter icon-footer"></i></a>
          </li>
          <li class="icon-item">
            <a href="#"><i class="fab fa-youtube icon-footer"></i></a>
          </li>
          <li class="icon-item">
            <a href="#"><i class="fab fa-instagram icon-footer"></i></a>
          </li>
          <li class="icon-item">
            <a href="#"><i class="fab fa-linkedin-in icon-footer"></i></a>
          </li> -->
        </ul>
      </div>
    </section>
    <section class="copyright text-center">
      © Copyright 2012 - 2019 | Avada Theme by
      <a href="#">ThemeFusion</a>
      | All Rights Reserved | Powered by
      <a href="#">WordPress</a>
    </section>
  </footer>
</template>

<script>
export default {
  name: "Footer",
  data() {
    return {
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

<style scoped lang="scss">
@import "@/styles/footer";
</style>
