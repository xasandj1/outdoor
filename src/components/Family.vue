<template>
  <section class="family">
    <div class="container">
      <div class="family-content">
        <div class="family-content_top">
          <span>Meet the family</span>
          <h2 class="family-content_top-title">
            What we have in store for you.
          </h2>
          <p class="family-content_top-txt">
            Morbi neque ex, condimentum dapibus congue et, vulputate ut ligula.
            Vestibulum sit amet urna turpis. Mauris euismod elit et nisi
            ultrices, ut faucibus orci tincidunt.
          </p>
        </div>
        <div class="family-content_cards">
          <div class="family-content_cards-card">
            <div class="family-content_cards-card_inner">
              <h3 class="family-content_cards-card_inner-title">Accessories</h3>
              <p class="family-content_cards-card_inner-txt">
                Accessories you didn't know youneeded.
              </p>
              <a href="" class="family-content_cards-card_inner-link"
                >View Accessories <img src="../assets/img/pathright.svg" alt=""
              /></a>
            </div>
          </div>
          <div class="family-content_cards-card">
            <div class="family-content_cards-card_inner">
              <h3 class="family-content_cards-card_inner-title">Accessories</h3>
              <p class="family-content_cards-card_inner-txt">
                Accessories you didn't know youneeded.
              </p>
              <a href="" class="family-content_cards-card_inner-link"
                >View Accessories <img src="../assets/img/pathright.svg" alt=""
              /></a>
            </div>
          </div>
          <div class="family-content_cards-card">
            <div class="family-content_cards-card_inner">
              <h3 class="family-content_cards-card_inner-title">Accessories</h3>
              <p class="family-content_cards-card_inner-txt">
                Accessories you didn't know youneeded.
              </p>
              <a href="" class="family-content_cards-card_inner-link"
                >View Accessories <img src="../assets/img/pathright.svg" alt=""
              /></a>
            </div>
          </div>
          <div class="family-content_cards-card">
            <div class="family-content_cards-card_inner">
              <h3 class="family-content_cards-card_inner-title">Accessories</h3>
              <p class="family-content_cards-card_inner-txt">
                Accessories you didn't know youneeded.
              </p>
              <a href="" class="family-content_cards-card_inner-link"
                >View Accessories <img src="../assets/img/pathright.svg" alt=""
              /></a>
            </div>
          </div>
          <div class="family-content_cards-card">
            <div class="family-content_cards-card_inner">
              <h3 class="family-content_cards-card_inner-title">Accessories</h3>
              <p class="family-content_cards-card_inner-txt">
                Accessories you didn't know youneeded.
              </p>
              <a href="" class="family-content_cards-card_inner-link"
                >View Accessories <img src="../assets/img/pathright.svg" alt=""
              /></a>
            </div>
          </div>
          <div class="family-content_cards-card">
            <div class="family-content_cards-card_inner">
              <h3 class="family-content_cards-card_inner-title">Accessories</h3>
              <p class="family-content_cards-card_inner-txt">
                Accessories you didn't know youneeded.
              </p>
              <a href="" class="family-content_cards-card_inner-link"
                >View Accessories <img src="../assets/img/pathright.svg" alt=""
              /></a>
            </div>
          </div>
        </div>
        <div class="show">
          <a href="" class="show_link"
            >View Accessories <img src="../assets/img/pathright.svg" alt=""
          /></a>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  //name:'Family'
};
</script>
<style lang="scss" scoped>
.family {
  padding: 100px 0;

  &-content {
    &_top {
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;

      &-title {
        font-size: 36px;
        line-height: 43px;
        text-align: center;
        color: var(--main-color);
      }

      &-txt {
        font-size: 16px;
        line-height: 19px;
        text-align: center;
        color: var(--main-color);
        max-width: 538px;
        width: 100%;
      }
    }

    &_cards {
      display: grid;
      grid-gap: 20px;
      grid-template-columns: repeat(3, 4fr);
      margin: 20px 0;

      &-card {
        //width: 33.3%;
        display: flex;
        gap: 20px;
        align-items: center;
        min-height: 450px;

        &:nth-child(1) {
          background: url(../assets/img/famlyimg1.png) no-repeat center / cover;
        }

        &:nth-child(2) {
          background: url(../assets/img/famlyimg2.png) no-repeat center / cover;
        }

        &:nth-child(3) {
          background: url(../assets/img/famlyimg3.png) no-repeat center / cover;
        }

        &:nth-child(4) {
          background: url(../assets/img/famlyimg4.png) no-repeat center / cover;
        }

        &:nth-child(5) {
          background: url(../assets/img/famlyimg5.png) no-repeat center / cover;
        }

        &:nth-child(6) {
          background: url(../assets/img/famlyimg6.png) no-repeat center / cover;
        }

        &_inner {
          display: flex;
          align-items: center;
          justify-content: flex-start;
          flex-direction: column;
          height: 100%;
          width: 100%;
          margin-top: 40px;

          &-title {
            font-size: 28px;
            line-height: 34px;
            text-align: center;
            color: var(--main-color);
          }

          &-txt {
            font-size: 16px;
            line-height: 22px;
            text-align: center;
            color: var(--main-color);
            max-width: 252px;
            width: 100%;
            margin-top: 10px;
          }

          &-link {
            font-size: 15px;
            line-height: 21px;
            color: var(--main-color);
            text-align: center;
            margin-top: 20px;
          }
        }
      }
    }
  }
}
.show {
  display: flex;
  align-items: center;
  justify-content: center;

  &_link {
    font-size: 15px;
    line-height: 21px;
    color: var(--main-color);
  }
}
@media (max-width: 768px) {
  .family-content_cards {
    display: grid;
    grid-gap: 20px;
    grid-template-columns: repeat(2, 2fr);
    margin: 20px 0;
  }
  .family {
    padding: 50px 0;
  }
}
@media (max-width: 425px) {
  .family-content_cards {
    display: grid;
    grid-gap: 20px;
    grid-template-columns: repeat(1, 2fr);
    margin: 20px 0;
  }
  .family-content_top-title {
    font-size: 28px;
    line-height: 40px;
    text-align: center;
    color: var(--main-color);
    margin-top: 10px;
}
}
@media (max-width: 400px) {
  .family-content_top-txt {
    font-size: 16px;
    line-height: 19px;
    text-align: center;
    color: var(--main-color);
    max-width: 340px;
    width: 100%;
}
.family-content_cards-card {
    display: flex;
    gap: 20px;
    align-items: center;
    min-height: 400px;
}
}
@media (max-width: 375px) {
  .family-content_top-title {
    font-size: 25px;
    line-height: 40px;
    text-align: center;
    color: var(--main-color);
    margin-top: 10px;
}
}
</style>