<template>
  <section class="suscribe">
    <div class="container">
      <img
        src="../assets/img/CombinedShape.png"
        alt=""
        class="suscribe__img before"
      />
      <div class="suscribe-content row">
        <div class="suscribe-content_left col-12 col-lg-6 col-md-6 col-sm-6 col-6">
          <img src="../assets/img/book2.png" alt="" class="suscribe-content_left-img"/>
        </div>
        <div class="suscribe-content_right col-12 col-lg-6 col-md-6 col-sm-6 col-6">
          <span>Some light reading</span>
          <h2 class="suscribe-content_right-title">
            Subscribe to our magazine today.
          </h2>
          <p class="suscribe-content_right-txt">
            We are an outdoor gear company focused on Lorem ipsum dolor sit
            amet, consectetur adipiscing elit. Nullam scelerisque aliquam odio
            et faucibus. Nulla rhoncus feugiat eros quis consectetur. Morbi
            neque ex, condimentum dapibus congue et.
          </p>
          <div class="suscribe-content_right_btn">
            <a href="" class="suscribe-content_right_btn-link"
              >Read more <img src="../assets/img/pathright.svg" alt=""
            /></a>
          </div>
        </div>
      </div>
    </div>
    <img
      src="../assets/img/CombinedShape.png"
      alt=""
      class="suscribe__img after"
    />
  </section>
</template>
<script>
export default {
  // name:subscribe,
};
</script>
<style lang="scss" scoped>
.suscribe {
  padding: 100px 0;

  &-content {
    display: flex;
    align-items: center;

    &_right {
      &-title {
        font-size: 36px;
        line-height: 43px;
        color: var(--main-color);
        max-width: 295px;
        width: 100%;
      }

      &-txt {
        font-size: 16px;
        line-height: 19px;
        color: var(--main-color);
        max-width: 384px;
        width: 100%;
      }

      &_btn {
        margin-top: 20px;

        &-link {
          font-size: 15px;
          line-height: 21px;
          color: var(--main-color);
        }
      }
    }
  }

  &__img {
    position: absolute;

    &.before {
      top: -22%;
      left: 35%;
    }

    &.after {
      bottom: -6%;
      left: 9%;
    }
  }
}
@media (max-width: 768px) {
  .suscribe {
    padding: 50px 0;
  }
  .suscribe__img.before {
    top: -13%;
    left: 35%;
    z-index: -2;
}
}
@media (max-width: 425px) {
    .suscribe-content_left-img{
        width: 100%;
    }
    .footer-bottom-txt {
    font-size: 10px;
    line-height: 20px;
    color: #FFFFFF;
}
.suscribe__img.after {
    bottom: -6%;
    left: 9%;
    display: none;
}
.suscribe__img.before {
    bottom: -6%;
    left: 9%;
    display: none;
}
}
@media (max-width: 400px) {
  .suscribe {
    padding: 0px 0;
}
.suscribe-content_right-txt[data-v-5e3e561c] {
    font-size: 16px;
    line-height: 19px;
    color: var(--main-color);
    max-width: 287px;
    width: 100%;
}
}
</style>