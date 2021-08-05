<template>
  <div class="home">
    <HeaderShayna />
    <HeroShayna />
    <WomanShayna />
    <InstaShayna />
    <PartnerLogoShayna />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src

import HeaderShayna from "@/components/HeaderShayna.vue";
import HeroShayna from "@/components/HeroShayna.vue";
import WomanShayna from "@/components/WomanShayna.vue";
import InstaShayna from "@/components/InstaShayna.vue";
import PartnerLogoShayna from "@/components/PartnerLogoShayna.vue";
import FooterShayna from "@/components/FooterShayna.vue";

export default {
  name: "Home",
  components: {
    HeaderShayna,
    HeroShayna,
    WomanShayna,
    InstaShayna,
    PartnerLogoShayna,
    FooterShayna,
  },
};
</script>
