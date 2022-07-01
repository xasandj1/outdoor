<template>
  <section class="navigeting">
    <div class="container">
      <div class="navigeting-content">
        <div class="navigeting-content_top">
          <span>Buyer's guides</span>
          <h2 class="navigeting-content_top-title">Navigating our offering.</h2>
          <p class="navigeting-content_top-txt">
            Morbi neque ex, condimentum dapibus congue et, vulputate ut ligula.
            Vestibulum sit amet urna turpis. Mauris euismod elit et nisi
            ultrices, ut faucibus orci tincidunt.
          </p>
        </div>
        <div class="navigeting-content_cards row">
          <div class="navigeting-content_cards-left col-12 col-lg-6 col-md-6 col-sm-6 col-6">
            <img src="../assets/img/maountinesykle.png" alt="" />
            <p class="navigeting-content_cards-left_txt">
              3 climbing accessories for the climber that has everything
            </p>
            <div class="navigeting-content_cards-left_bottom">
              <div class="navigeting-content_cards-left_bottom-left">
                <img src="../assets/img/AlexJenna.png" alt="" />
                <div class="navigeting-content_cards-left_bottom-left_img">
                  <h5
                    class="navigeting-content_cards-left_bottom-left_img-name"
                  >
                    Alex Jenna
                  </h5>
                  <span>QA</span>
                </div>
              </div>
              <div class="navigeting-content_cards-left_bottom-data">
                <p class="navigeting-content_cards-left_bottom-data_txt">
                  October 18, 2021
                </p>
              </div>
            </div>
          </div>
          <div class="navigeting-content_cards-right col-12 col-lg-6 col-md-6 col-sm-6 col-6">
            <img src="../assets/img/Bike.png" alt="" />
            <p class="navigeting-content_cards-right_txt">
              Biking accessories for the beaten path
            </p>
            <div class="navigeting-content_cards-left_bottom">
              <div class="navigeting-content_cards-left_bottom-left">
                <img src="../assets/img/woodie.png" alt="" />
                <div class="navigeting-content_cards-left_bottom-left_img">
                  <h5
                    class="navigeting-content_cards-left_bottom-left_img-name"
                  >
                    Alex Jenna
                  </h5>
                  <span>QA</span>
                </div>
              </div>
              <div class="navigeting-content_cards-left_bottom-data">
                <p class="navigeting-content_cards-left_bottom-data_txt">
                  October 18, 2021
                </p>
              </div>
            </div>
          </div>
          <div class="navigeting-content_cards-btn">
            <a href="" class="navigeting-content_cards-btn_link"
              >Show all buyer's guides
              <img src="../assets/img/pathright.svg" alt=""
            /></a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
</script>

<style lang="scss" scoped>
.navigeting {
  overflow: hidden;
  padding-bottom: 100px;
  &-content {
    &_top {
      &-title {
        font-size: 36px;
        line-height: 43px;
        color: var(--main-color);
      }

      &-txt {
        font-size: 16px;
        line-height: 19px;
        color: var(--main-color);
        max-width: 538px;
        width: 100%;
      }
    }

    &_cards {
      margin-top: 20px;
      width: 100%;

      &-btn {
        display: flex;
        align-items: center;
        justify-content: center;

        &_link {
          font-size: 15px;
          line-height: 21px;
          color: var(--main-color);
          margin-top: 40px;
        }
      }

      &-left {
        img {
          width: 100%;
        }

        &_txt {
          font-size: 20px;
          line-height: 24px;
          color: var(--main-color);
          max-width: 465px;
          width: 100%;
          margin-top: 20px;
        }

        &_bottom {
          display: flex;
          align-items: center;
          justify-content: space-between;
          margin-top: 12px;

          &-data {
            &_txt {
              font-size: 13px;
              line-height: 18px;
              color: var(--main-color);
            }
          }

          &-left {
            display: flex;
            align-items: center;
            justify-content: center;

            &_img {
              margin-left: 12px;

              &-name {
                font-size: 13px;
                line-height: 18px;
                color: var(--main-color);
                width: 100px;
              }
            }
          }
        }
      }

      &-right {
        img {
          width: 100%;
        }

        &_txt {
          font-size: 19px;
          line-height: 24px;
          color: #575445;
          margin-top: 20px;
          min-width: 381px;
          width: 100%;
        }
      }
    }
  }
}
@media (max-width: 768px) {
  .navigeting-content_cards-left_bottom {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-top: 20px;
    margin-bottom: 20px;
  }
}
@media (max-width: 425px) {
    .navigeting-content_top-title{
    font-size: 30px;
    line-height: 43px;
    color: var(--main-color);
}
.navigeting-content_top-txt {
    font-size: 15px;
    line-height: 20px;
    color: var(--main-color);
    max-width: 538px;
    width: 100%;
}
.navigeting-content_cards-left_txt {
    font-size: 15px;
    line-height: 22px;
    color: var(--main-color);
    max-width: 465px;
    width: 100%;
    margin-top: 20px;
}
.navigeting-content_cards-right_txt {
    font-size: 15px;
    line-height: 20px;
    color: #575445;
    margin-top: 20px;
    min-width: 381px;
    width: 100%;
}
}
@media (max-width: 400px) {
  .navigeting-content_cards-left_bottom {
    display: flex; 
    align-items: unset; 
    justify-content: unset; 
    margin-top: 20px; 
    margin-bottom: 20px;
}
}
@media (max-width: 375px) {
  .navigeting-content_top-txt {
    font-size: 12px;
    line-height: 20px;
    color: var(--main-color);
    max-width: 300px;
    width: 100%;
}
}
</style>