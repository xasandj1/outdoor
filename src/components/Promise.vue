<template>
  <section class="promise">
    <div class="container">
      <img
        src="../assets/img/Combined-ShapeLeft.png"
        alt=""
        class="promise__img after"
      />
      <div class="promise-content">
        <div class="promise-content_top">
          <span>Our promise</span>
          <h2 class="promise-content_top-title">
            Setting the bar for our products.
          </h2>
          <p class="promise-content_top-txt">
            Morbi neque ex, condimentum dapibus congue et, vulputate ut ligula.
            Vestibulum sit amet urna turpis. Mauris euismod elit et nisi
            ultrices, ut faucibus orci tincidunt.
          </p>
        </div>
        <div class="promise-content_cards row">
          <div class="promise-content_cards-card col-12 col-lg-4 col-md-4 col-sm-3 col-3">
            <img src="../assets/img/promisimg.svg" alt="" />
            <h3 class="promise-content_cards-card_title">
              Sustainable sourcing
            </h3>
            <p class="promise-content_cards-card_txt">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              Suspendisse varius enim in eros elementum tristique.
            </p>
          </div>
          <div class="promise-content_cards-card col-12 col-lg-4 col-md-4 col-sm-3 col-3">
            <img src="../assets/img/primisngimg2.png" alt="" />
            <h3 class="promise-content_cards-card_title">Lifetime warranty</h3>
            <p class="promise-content_cards-card_txt">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              Suspendisse varius enim in eros elementum tristique.
            </p>
          </div>
          <div class="promise-content_cards-card col-12 col-lg-4 col-md-4 col-sm-3 col-3">
            <img src="../assets/img/primisngimg4.png" alt="" />
            <h3 class="promise-content_cards-card_title">All-terrain tested</h3>
            <p class="promise-content_cards-card_txt">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              Suspendisse varius enim in eros elementum tristique.
            </p>
          </div>
        </div>
        <div class="promise-content_cards row">
          <div class="promise-content_cards-card col-12 col-lg-4">
            <img src="../assets/img/primisngimg1.png" alt="" />
            <h3 class="promise-content_cards-card_title">Premium materials</h3>
            <p class="promise-content_cards-card_txt">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              Suspendisse varius enim in eros elementum tristique.
            </p>
          </div>
          <div class="promise-content_cards-card col-12 col-lg-4">
            <img src="../assets/img/primisngimg3.png" alt="" />
            <h3 class="promise-content_cards-card_title">Designed by you</h3>
            <p class="promise-content_cards-card_txt">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              Suspendisse varius enim in eros elementum tristique.
            </p>
          </div>
          <div class="promise-content_cards-card col-12 col-lg-4">
            <img src="../assets/img/primisngimg5.png" alt="" />
            <h3 class="promise-content_cards-card_title">Quality assured</h3>
            <p class="promise-content_cards-card_txt">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              Suspendisse varius enim in eros elementum tristique.
            </p>
          </div>
        </div>
        <img
          src="../assets/img/CombinedShapeRight.png"
          alt=""
          class="promise__img before"
        />
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: "Promise",
};
</script>
<style lang="scss" scoped>
.promise {
  background: rgb(238, 230, 230);
  position: relative;
  //height: 835px;
  padding: 100px 0;

  &-content {
    &_top {
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;

      &-title {
        font-size: 40px;
        line-height: 43px;
        text-align: center;
        color: var(--main-color);
      }

      &-txt {
        font-size: 20px;
        line-height: 23px;
        text-align: center;
        color: var(--main-color);
        max-width: 538px;
        width: 100%;
      }
    }

    &_cards {
      display: flex;
      align-items: center;
      margin-top: 70px;

      &-card {
        display: flex;
        align-items: center;
        flex-direction: column;

        img {
          margin-bottom: 10px;
        }

        &_title {
          font-size: 20px;
          line-height: 24px;
          text-align: center;
          color: var(--main-color);
          margin-bottom: 10px;
        }

        &_txt {
          font-size: 14px;
          line-height: 20px;
          text-align: center;
          color: var(--main-color);
          max-width: 287px;
          width: 100%;
        }
      }
    }
  }

  &__img {
    position: absolute;

    &.before {
      top: 47%;
      left: -24%;
    }

    &.after {
      top: -15%;
      right: -22%;
    }
  }
}

@media (max-width: 1440px) {
  .promise__img.after {
    top: -15%;
    right: -2%;
  }
}
@media (max-width: 1024px) {
  .promise__img.after {
    top: -15%;
    right: 0%;
  }
  .promise__img.before {
    top: 47%;
    left: 0%;
  }
}
@media (max-width: 768px) {
  .promise-content_cards {
    display: flex;
    align-items: center;
    margin-top: 30px;
  }
  .promise__img.after {
    top: -4%;
    right: 0%;
  }
  .promise {
    background: rgb(238, 230, 230);
    position: relative;
    padding: 50px 0;
  }
  .promise__img.before {
    top: 68%;
    left: 0%;
  }
}
@media (max-width: 425px) {
  .promise__img.after {
    top: -4%;
    right: 0%;
    display: none;
  }
  .promise__img.before {
    display: none;
  }
}
@media (max-width: 425px) {
  .promise-content_top-title {
    font-size: 30px;
    line-height: 43px;
    text-align: center;
    color: var(--main-color);
    margin-top: 10px;
  }
  .promise-content_top-txt[data-v-f8e234ca] {
    font-size: 15px;
    line-height: 20px;
  }
  .about-content_right-title{
    font-size: 30px;
    line-height: 43px;
    color: var(--main-color);
}
.about-content_right-txt {
    font-size: 14px;
    line-height: 24px;
    color: var(--main-color);
    max-width: 384px;
    width: 100%;
}
}
@media (max-width: 400px) {
  .promise-content_top-txt {
    font-size: 13px;
    line-height: 20px;
}
.promise-content_top-title {
    font-size: 25px;
    line-height: 43px;
    text-align: center;
    color: var(--main-color);
    margin-top: 10px;
}
.promise-content_cards-card {
    display: flex;
    align-items: center;
    flex-direction: column;
    margin-bottom: 20px;
}
}
</style>