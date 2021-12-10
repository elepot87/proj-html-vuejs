<template>
  <main>
    <!-- Section 1 Messaggio chef -->
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
    <!-- Section 2 Features -->
    <section class="features d-flex px-200">
      <div class="col-left text-center">
        <img :src="require(`@/assets/images/sushi-1.png`)" alt="icona sushi" />
        <h3 class="title-feature">the best table in town</h3>
        <div class="separator"></div>
        <p class="text-feature">
          Sed aenean egestas ut aliquam turpis mauris, molestie. Vitae tellus
          tempor sem id tempus neque, tellus turpis turpis. Morbi tortor id
          gravida.
        </p>
        <button class="button-secondary">explore the menu</button>
      </div>
      <div class="col-center text-center">
        <img :src="require(`@/assets/images/sushi-2.png`)" alt="icona sushi" />
        <h3 class="title-feature">perfect for groups</h3>
        <div class="separator"></div>
        <p class="text-feature">
          Quam eu proin sit massa condimentum. Volutpat non pulvinar aliquet
          nunc. Orci elementum in aliquet a gravida vivamus aliquam turpis
          vitae.
        </p>
        <button class="button-secondary">make a reservation</button>
      </div>
      <div class="col-right text-center">
        <img :src="require(`@/assets/images/sushi-3.png`)" alt="icona sushi" />
        <h3 class="title-feature">fresh produce everyday</h3>
        <div class="separator"></div>
        <p class="text-feature">
          Hendrerit amet, volutpat leo non, commodo maecenas scelerisque
          tincidunt. Morbi vulputate morbi purus quisque sit sagittis orci
          elementum.
        </p>
        <button class="button-secondary">learn more about us</button>
      </div>
    </section>
    <!-- Section 3 Immagine+CTA-->
    <section class="image-cta d-flex">
      <div class="image-cta-left"></div>
      <div class="image-cta-right">
        <div class="container-subtitle d-flex align-items-center">
          <div class="subtitle">
            <span> fine dining exeprience </span>
          </div>
        </div>
        <div class="container-text">
          <h1>the best table in town</h1>
          <p>
            Pellentesque vitae viverra risus, sagittis. Venenatis ridiculus
            scelerisque nisi in urna nulla.
          </p>
          <button class="button-main">explore the menu</button>
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
