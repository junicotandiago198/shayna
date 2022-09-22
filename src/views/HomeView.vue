<template>
  <div class="home">
    <HeaderShayna />
    <HeroShayna />
    <WomenShayna />
    <IstaShayna />
    <PartnerShayna />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue';
import HeaderShayna from '@/components/HeaderShayna.vue';
import HeroShayna from '@/components/HeroShayna.vue';
import WomenShayna from '@/components/WomenShayna.vue';
import IstaShayna from '../components/IstaShayna.vue';
import PartnerShayna from '../components/PartnerShayna.vue';
import FooterShayna from '../components/FooterShayna.vue';

export default {
  name: 'HomeView',
  components: {
    HeaderShayna,
    HeroShayna,
    WomenShayna,
    IstaShayna,
    PartnerShayna,
    FooterShayna,
  },
};
</script>