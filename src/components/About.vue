<template>
  <section class="about">
    <div class="container">
      <img
        src="../assets/img/CombinedShape.png"
        alt=""
        class="about__img before"
      />
      <div class="about-content">
        <div class="row">
          <div class="about-content_left col-12 col-xxl-6 col-lg-8 col-md-6 col-sm-3 col-3">
            <img src="../assets/img/about.png" alt="" class="about-content_left-img" />
          </div>
          <div class="about-content_right col-12 col-xxl-6 col-lg-4 col-md-6 col-sm-3 col-3">
            <span>Who are we?</span>
            <h2 class="about-content_right-title">A bit about us.</h2>
            <p class="about-content_right-txt">
              We are an outdoor gear company focused on Lorem ipsum dolor sit
              amet, consectetur adipiscing elit. Nullam scelerisque aliquam odio
              et faucibus. Nulla rhoncus feugiat eros quis consectetur. Morbi
              neque ex, condimentum dapibus congue et.
            </p>
            <a href="" class="about-content_right-link"
              >Read more <img src="../assets/img/pathright.svg" alt=""
            /></a>
          </div>
        </div>
      </div>
    </div>
    <img
      src="../assets/img/CombinedShape.png"
      alt=""
      class="about__img after"
    />
  </section>
</template>
<script>
export default {
  data() {
    return {
        menubtn:[
            {}
        ]
    }
  },
  
};
</script>
<style lang="scss" scoped>
.about {
  padding: 100px 0 130px;
  &-content {
    &_right {
      display: flex;
      justify-content: center;
      flex-direction: column;

      &-title {
        font-size: 36px;
        line-height: 43px;
        color: var(--main-color);
      }

      &-txt {
        font-size: 16px;
        line-height: 25px;
        color: var(--main-color);
        max-width: 384px;
        width: 100%;
      }

      &-link {
        font-size: 15px;
        line-height: 21px;
        color: var(--main-color);
        margin-top: 20px;
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
      bottom: -10%;
      left: 9%;
      z-index: -2;
    }
  }
}
@media (max-width: 768px) {
  .about-content_left {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }
  .about-content_right{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    margin-top: 30px;
}
.about{
    padding: 50px 0 50px;
}
.about__img.before {
    top: -12%;
    left: 35%;
}
}
@media (max-width: 425px) {
    .about-content_left-img{
        width: 100%;
    }
    .about__img.before {
    display: none;
}
}
@media (max-width: 400px) {
  .about-content_left-img {
    width: 80%;
}
.about-content_right-txt {
    font-size: 16px;
    line-height: 25px;
    color: var(--main-color);
    max-width: 268px;
    width: 100%;
}
}
@media (max-width: 375px) {
  .about__img{
    display: none;
  } 
}
</style>