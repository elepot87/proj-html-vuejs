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
    <!-- Section 4 Recensioni -->
    <section class="reviews">
      <h1 class="title text-center">What critics are saying about us</h1>
      <div class="separator my-5"></div>
      <div class="review-big d-flex">
        <div class="col-left">
          <img
            :src="require(`@/assets/images/blog72x.jpg`)"
            alt="recensione1"
          />
        </div>
        <div class="col-right">
          <div class="container-text">
            <div class="subtitle">maggie stewart</div>
            <h1>new york times</h1>
            <div class="container-icons-reviews">
              <i class="fas fa-star icon-reviews"></i>
              <i class="fas fa-star icon-reviews"></i>
              <i class="fas fa-star icon-reviews"></i>
              <i class="fas fa-star icon-reviews"></i>
              <i class="fas fa-star icon-reviews"></i>
            </div>
            <div class="separator-reviews"></div>
            <div class="text">
              <p>
                Non arcu mauris tortor ultrices mollis tellus euismod fermentum.
                Habitant amet tincidunt id sapien accumsan sed at.
              </p>
              <p>
                Mmalesuada ullamcorper amet. Pretium pretium dignissim nisi.
              </p>
            </div>

            <button class="button-main">read full article</button>
          </div>
        </div>
      </div>
      <div class="reviews-small d-flex">
        <div class="col-left d-flex align-items-center justify-content-center">
          <div class="container-text">
            <div class="subtitle">mary maxey</div>
            <h1>the guardian</h1>
            <div class="container-icons-reviews">
              <i class="fas fa-star icon-reviews"></i>
              <i class="fas fa-star icon-reviews"></i>
              <i class="fas fa-star icon-reviews"></i>
              <i class="fas fa-star icon-reviews"></i>
              <i class="fas fa-star icon-reviews"></i>
            </div>
            <div class="separator-reviews"></div>
            <div class="text">
              <p>
                Non arcu mauris tortor ultrices mollis tellus euismod fermentum.
                Habitant amet tincidunt id sapien accumsan sed.
              </p>
            </div>
            <button class="button-transparent">read full article</button>
          </div>
        </div>
        <div class="col-right d-flex align-items-center justify-content-center">
          <div class="container-text">
            <div class="subtitle">patrick monroe</div>
            <h1>globe and mail</h1>
            <div class="container-icons-reviews">
              <i class="fas fa-star icon-reviews"></i>
              <i class="fas fa-star icon-reviews"></i>
              <i class="fas fa-star icon-reviews"></i>
              <i class="fas fa-star icon-reviews"></i>
              <i class="fas fa-star icon-reviews"></i>
            </div>
            <div class="separator-reviews"></div>
            <div class="text">
              <p>
                Vivamus magna justo, lacinia eget consectetur sed, convallis at
                tellus. Nulla porttitor accumsan tincidunt.
              </p>
            </div>
            <button class="button-transparent">read full article</button>
          </div>
        </div>
      </div>
    </section>
    <!-- Section 5 Immagine full width -->
    <section
      class="img-full-width d-flex justify-content-center align-items-end"
    >
      <div class="caption">kung pao chicken - $32</div>
    </section>
    <!-- Section 6 News & Promotion -->
    <section class="news-promotions">
      <h1 class="title text-center">Latest news &amp; promotions</h1>
      <div class="separator my-5"></div>
      <div class="wrapper-news-promotions d-flex">
        <!-- Col sx -->
        <div class="col-left">
          <div class="content-reveal-wrapper">
            <div class="content-reveal">
              <a href="#">
                <i class="fas fa-link"></i>
              </a>
              <div class="title">the best coffee in town</div>
              <div class="category">news</div>
            </div>
          </div>
          <div class="info text-center">
            <div class="title-news">the best cooffe in town</div>
            <div class="info-news">
              By admin | January 7th, 2020 | Categories: News
            </div>
          </div>
        </div>
        <!-- Col center -->
        <div class="col-center">
          <div class="content-reveal-wrapper">
            <div class="content-reveal">
              <a href="#">
                <i class="fas fa-link"></i>
              </a>
              <div class="title">discover our new menu</div>
              <div class="category">news</div>
            </div>
          </div>
          <div class="info text-center">
            <div class="title-news">discover our new menu</div>
            <div class="info-news">
              By admin | January 7th, 2020 | Categories: News
            </div>
          </div>
        </div>
        <!-- Col dx -->
        <div class="col-right">
          <div class="content-reveal-wrapper">
            <div class="content-reveal">
              <a href="#">
                <i class="fas fa-link"></i>
              </a>
              <div class="title">we now accept square!</div>
              <div class="category">news</div>
            </div>
          </div>
          <div class="info text-center">
            <div class="title-news">we now accept square!</div>
            <div class="info-news">
              By admin | January 7th, 2020 | Categories: News
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Section 7 Take out -->
    <section class="takeout">
      <section class="image-cta d-flex">
        <div class="image-cta-left"></div>
        <div class="image-cta-right">
          <div class="container-subtitle d-flex align-items-center">
            <div class="subtitle">
              <span> enjoy your meal at home </span>
            </div>
          </div>
          <div class="container-text">
            <h1>takeout now available</h1>
            <p>
              Pellentesque vitae viverra risus, sagittis. Venenatis ridiculus
              scelerisque nisi in urna nulla.
            </p>
            <button class="button-main">
              <i class="fas fa-car mx-2"></i>
              view take out menu
            </button>
          </div>
        </div>
      </section>
    </section>
    <!-- Section 8 Menu -->
    <section class="menu d-flex">
      <!-- Col sx -->
      <div class="col-left">
        <h3 class="title-menu">hors d'oeuvres</h3>
        <!-- Lista piatti -->
        <ul class="menu-list">
          <!-- Menu item -->
          <li class="menu-item">
            <div class="main-info">
              <h4 class="plate-name">ahi salmon nigiri</h4>
              <div class="price">$48</div>
            </div>
            <p class="description">
              Eget vulputate vitae quis rutrum blandit sed. Quam nulla sit
              lacinia.
            </p>
          </li>
          <!-- Menu item -->
          <li class="menu-item">
            <div class="main-info">
              <h4 class="plate-name">umi masu salad</h4>
              <div class="price">$21</div>
            </div>
            <p class="description">
              Mollis ornare sit sapien, sodales. Cursus duis proin semper
              quisque.
            </p>
          </li>
          <!-- Menu item -->
          <li class="menu-item">
            <div class="main-info">
              <h4 class="plate-name">temaki with crab</h4>
              <div class="price">$32</div>
            </div>
            <p class="description">
              Ac vel, risus ornare senectus placerat duis amet dictumst tellus.
            </p>
          </li>
          <!-- Menu item -->
          <li class="menu-item">
            <div class="main-info">
              <h4 class="plate-name">california rolls</h4>
              <div class="price">$22</div>
            </div>
            <p class="description">
              Ac vel, risus ornare senectus placerat duis amet dictumst tellus.
            </p>
          </li>
        </ul>
      </div>
      <!-- Col center -->
      <div class="col-center">
        <h3 class="title-menu">main course</h3>
        <!-- Lista piatti -->
        <ul class="menu-list">
          <!-- Menu item -->
          <li class="menu-item">
            <div class="main-info">
              <h4 class="plate-name">braised abalone</h4>
              <div class="price">$52</div>
            </div>
            <p class="description">
              Mollis ornare sit sapien, sodales. Cursus duis proin semper
              quisque.
            </p>
          </li>
          <!-- Menu item -->
          <li class="menu-item">
            <div class="main-info">
              <h4 class="plate-name">twice cooked pork</h4>
              <div class="price">$21</div>
            </div>
            <p class="description">
              Ac vel, risus ornare senectus placerat duis amet dictumst tellus.
            </p>
          </li>
          <!-- Menu item -->
          <li class="menu-item">
            <div class="main-info">
              <h4 class="plate-name">kung pao chicken</h4>
              <div class="price">$32</div>
            </div>
            <p class="description">
              Quis duis sit dictum aliquam a velit enim. Tellus in sit augue
              aliquam.
            </p>
          </li>
          <!-- Menu item -->
          <li class="menu-item">
            <div class="main-info">
              <h4 class="plate-name">char siu &amp; sushis</h4>
              <div class="price">$48</div>
            </div>
            <p class="description">
              Feugiat rhoncus ipsum tristique purus diam, et dolor molestie.
            </p>
          </li>
        </ul>
      </div>
      <!-- Col-right -->
      <div class="col-right">
        <h3 class="title-menu">desserts</h3>
        <!-- Lista piatti -->
        <ul class="menu-list">
          <!-- Menu item -->
          <li class="menu-item">
            <div class="main-info">
              <h4 class="plate-name">chocolate ball cake</h4>
              <div class="price">$13</div>
            </div>
            <p class="description">
              In pellentesque in felis massa vehicula. In sed euismod ut.
            </p>
          </li>
          <!-- Menu item -->
          <li class="menu-item">
            <div class="main-info">
              <h4 class="plate-name">lime pie with crust</h4>
              <div class="price">$14</div>
            </div>
            <p class="description">
              Mollis ornare sit sapien, sodales. Cursus duis proin semper
              quisque.
            </p>
          </li>
          <!-- Menu item -->
          <li class="menu-item">
            <div class="main-info">
              <h4 class="plate-name">raspberry pear cake</h4>
              <div class="price">$18</div>
            </div>
            <p class="description">
              Eget vulputate vitae quis rutrum blandit sed. Quam nulla sit.
            </p>
          </li>
          <!-- Menu item -->
          <li class="menu-item">
            <div class="main-info">
              <h4 class="plate-name">caf&eacute; au lat</h4>
              <div class="price">$6</div>
            </div>
            <p class="description">
              Eget vulputate vitae quis rutrum blandit sed. Quam nulla sit.
            </p>
          </li>
        </ul>
      </div>
    </section>
    <!-- Section 9 Piatto in evidenza -->
    <section class="highlight-plate">
      <div class="container-info d-flex justify-content-center">
        <div class="info-plate d-flex">
          <h3 class="name-plate">braised abalone</h3>
          <div class="price">$52</div>
        </div>
        <div class="separator"></div>
        <p class="description-plate">
          Pretium accumsan porttitor viverra leo gravida mollis imperdiet.
          Fringilla nibh pharetra sociis leo amet.
        </p>
        <button class="button-main">view in the menu</button>
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
