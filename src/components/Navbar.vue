<template>
  <header class="header">
    <nav class="header-nav">
      <div class="container">
        <div class="header-nav__content">
          <a href="#!" class="logo"
            ><img src="../assets/img/logo.svg" alt="logo"
          /></a>
          <ul class="header-nav__content-list">
            <li><a href="" class="header-nav__content-list_link">Shop</a></li>
            <li>
              <a href="" class="header-nav__content-list_link">About us</a>
            </li>
            <li>
              <a href="" class="header-nav__content-list_link">Our team</a>
            </li>
            <li>
              <a href="" class="header-nav__content-list_link"
                >Buyer's guides</a
              >
            </li>
            <li>
              <a href="" class="header-nav__content-list_link">Categories</a>
            </li>
            <div class="header-nav__content-list_btns">
              <button>Buy template</button>
              <button>
                <img src="../assets/img/shopicon.svg" alt="" />Cart
                <span>0</span>
              </button>
            </div>
          </ul>
          <div class="header-nav__content-menu">
            <div class="header-nav__content-menu_t"></div>
            <div class="header-nav__content-menu_m"></div>
            <div class="header-nav__content-menu_b"></div>
          </div>
        </div>
      </div>
    </nav>
  </header>
</template>
<script>
export default {
  
};
</script>
<style lang="scss">
.header {
  overflow: hidden;
  position: sticky;
  top: 0;
  left: 0;
  width: 100%;
  z-index: 999;
  background: var(--white);
  &-nav {
    &__content {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 18px 0;

      &-list {
        display: flex;
        align-items: center;
        justify-content: space-between;

        li {
          margin: 0 14px;
        }

        &_link {
          font-weight: 400;
          font-size: 18px;
          color: var(--dark);
        }

        &_btns {
          display: flex;
          align-items: center;
          justify-content: center;
          margin-left: 26px;

          button {
            margin: 0 10px;
            height: 44px;
            padding: 10px 18px;
            background: var(--main-color);
            border: none;
            font-weight: 400;
            font-size: 16px;
            color: var(--white);
            display: flex;
            align-items: center;
            border-radius: 6px;

            img {
              margin-right: 8px;
            }

            span {
              background: var(--white);
              border-radius: 9px;
              padding: 0 3px;
              font-weight: 400;
              font-size: 14px;
              line-height: 18px;
              color: var(--main-color);
              margin-left: 8px;
            }
          }
        }
      }
    }
  }
}
@media (max-width: 1024px) {
  .header-nav__content-list_link {
    font-weight: 400;
    font-size: 15px;
    color: var(--dark);
  }
  .header-nav__content-list_btns button {
    margin: 0 2px;
  }
  .home-content {
    display: flex;
    align-items: center;
    justify-content: center;
  }
}
@media (max-width: 768px) {
  .header-nav__content-list {
    display: none;
    align-items: center;
    justify-content: space-between;
  }
  .header-nav__content-menu {
    display: flex;
    align-items: center;
    flex-direction: column;
    position: absolute;
    top: 35%;
    right: 0;
    &_t {
      &::after {
        content: "";
        width: 30px;
        height: 5px;
        background: var(--main-color);
        color: var(--main-color);
        position: absolute;
        right: 0;
        top: 0;
      }
    }
    &_m {
      &::after {
        content: "";
        width: 30px;
        height: 5px;
        background: var(--main-color);
        color: var(--main-color);
        position: absolute;
        right: 0;
        top: 8px;
      }
    }
    &_b {
      content: "";
      width: 30px;
      height: 5px;
      background: var(--main-color);
      color: var(--main-color);
      position: absolute;
      right: 0;
      top: 17px;
    }
  }
  .suscribe-content_right {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    margin-top: 25px;
  }
  .suscribe-content_left {
    display: flex;
    align-items: center;
    justify-content: center;
  }
}
</style>