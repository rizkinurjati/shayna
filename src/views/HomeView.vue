<template>
  <div class="home">
    <HeaderShayna/>
    <HeroShayna/>
    <BannerShayna/>
    <InstaShayna/>
    <PartnerShayna/>
    <FooterShayna/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

import HeaderShayna from '@/components/HeaderShayna.vue'
import BannerShayna from '@/components/BannerShayna.vue'
import InstaShayna from '../components/InstaShayna.vue'
import PartnerShayna from '@/components/PartnerShayna.vue'
import FooterShayna from '../components/FooterShayna.vue'
import HeroShayna from '@/components/HeroShayna.vue'

export default {
  name: 'HomeView',
  components: {
    HeaderShayna,
    HeroShayna,
    BannerShayna,
    InstaShayna,
    PartnerShayna,
    FooterShayna,
}
}
</script>
