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
          <li class="icon-item">
            <a href="#"><i class="fab fa-facebook-f icon-footer"></i></a>
          </li>
          <li class="icon-item">
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
          </li>
        </ul>
      </div>
    </section>
    <section class="copyright text-center">
      © Copyright 2012 - 2021 | Avada Theme by ThemeFusion | All Rights Reserved
      | Powered by WordPress
    </section>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped lang="scss">
@import "@/styles/footer";
</style>
