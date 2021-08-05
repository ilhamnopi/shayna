<template>
  <div class="partner-logo">
    <div class="container">
      <carousel class="logo-carousel" :autoplay="true" :nav="false" :dots="false" :margin="30" :responsive="{ 0: { items: 3, nav: false }, 600: { items: 4, nav: false }, 800: { items: 5, nav: false } }">
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/logo-1.png" alt="" />
          </div>
        </div>
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/logo-2.png" alt="" />
          </div>
        </div>
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/logo-3.png" alt="" />
          </div>
        </div>
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/logo-4.png" alt="" />
          </div>
        </div>
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/logo-5.png" alt="" />
          </div>
        </div>
      </carousel>
    </div>
  </div>
</template>

<script>
import carousel from "vue-owl-carousel";
export default {
  name: "PartnerLogoShayna",
  components: {
    carousel,
  },
};
</script>
