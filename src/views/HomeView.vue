<template>
  <div class="home">
    <HeaderComp />
    <HeroComp />
    <WomanComp />
    <InstaComp />
    <PartnerComp />
    <FooterComp />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderComp from "@/components/HeaderComp.vue";
import HeroComp from "@/components/HeroComp.vue";
import WomanComp from "@/components/WomanComp.vue";
import InstaComp from "@/components/InstaComp.vue";
import PartnerComp from "@/components/PartnerComp.vue";
import FooterComp from "@/components/FooterComp.vue";

export default {
  name: "HomeView",
  components: {
    HeaderComp,
    HeroComp,
    WomanComp,
    InstaComp,
    PartnerComp,
    FooterComp,
  },
};
</script>
