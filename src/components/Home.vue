<template>
    <section class="home">
      <div class="container">
        <div class="home-content row">
        <div class="home-content_inner col-12 col-lg-6">
          <span>OUTDOOR EXPLORATION</span>
          <h1 class="home-content_inner-title">Gear for when it actually matters.</h1>
          <p class="home-content_inner-txt">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim
            in eros elementum tristique.</p>
            </div>
        </div>
      </div>
    </section>
</template>
<script>
export default {
  name: 'Navbar',
  //   data() {},
  //   methods: {},
};
</script>

<style lang="scss" scoped>
.home {
  overflow: hidden;
  background: url(../assets/img/mauntin.png)no-repeat center / cover;
  min-height: 640px;
  display: flex;
  align-items: center;
  justify-content: center;

  &-content {
    &_inner{
    span {
      font-size: 14px;
      line-height: 20px;
      text-transform: uppercase;
      color: var(--yellow);
    }

    &-title {
      font-size: 48px;
      line-height: 58px;
      color: var(--white);
      max-width: 416px;
      width: 100%;
    }

    &-txt {
      font-weight: 400;
      font-size: 17px;
      line-height: 25px;
      color: var(--grey);
      max-width: 495px;
      width: 100%;
    }
    }
  }
}
@media (max-width: 425px) {
  .home-content_inner-title{
    font-size: 30px;
    line-height: 40px;
    color: var(--white);
    max-width: 416px;
    width: 100%;
}
.home-content_inner-txt{
    font-weight: 400;
    font-size: 15px;
    line-height: 25px;
    color: var(--grey);
    max-width: 460px;
    width: 100%;
}
}
@media (max-width: 425px){
  .home-content_inner-title {
    font-size: 30px;
    line-height: 40px;
    color: var(--white);
    max-width: 230px;
    width: 100%;
}
.home-content_inner-txt {
    font-weight: 400;
    font-size: 15px;
    line-height: 25px;
    color: var(--grey);
    max-width: 307px;
    width: 100%;
}
}

</style>