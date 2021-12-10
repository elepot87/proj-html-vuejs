<template>
  <ul class="main-menu d-flex">
    <li class="menu-item">
      <a href="#">{{ link }}</a>
    </li>
  </ul>
</template>

<script>
export default {
  name: "Menu",
  props: {
    link: String,
    textButton: String,
  },
};
</script>

<style></style>
