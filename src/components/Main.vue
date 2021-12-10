<template>
  <main>
    <section class="message-chef d-flex">
      <div class="left col-6">
        <div class="text1">
          <span class="highlighted">HAC TELLUS, FELIS RISUS AT</span>
          mattis mattis. Eget euismod semper eget tortor, donec amet, blandit.
          Tristique facilisi faucibus elementum feugiat in nam in feugiat. Ipsum
          odio etiam duis facilisis amet vulputate.
        </div>
        <div class="title">
          food is our common ground, a universal experience.
        </div>
        <div class="text2">
          Tristique tempus condimentum diam donec. Condimentum ullamcorper sit
          elementum hendrerit mi nulla in consequat, ut. Metus, nullam
          scelerisque netus viverra dui.
        </div>
        <img
          :src="require(`@/assets/images/signature-200x172.jpg`)"
          alt="signature-chef"
        />
      </div>
      <div class="right col-6">
        <div
          class="container-image d-flex justify-content-center align-items-end"
        >
          <!-- <img
            :src="require(`@/assets/images/info22x.jpg`)"
            alt="chef cucina"
            class="img-chef"
          /> -->
          <div class="caption">california rolls - $22</div>
        </div>
      </div>
    </section>
  </main>
</template>

<script>
export default {
  name: "Main",
};
</script>

<style scoped lang="scss">
@import "@/styles/main";
</style>
