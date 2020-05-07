<template>
  <div class="home">
    <HeaderShayna />
    <HeroShayna />
    <WomanShayna />
    <InstaShayna />
    <PartnerShayna />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from '@/components/HeaderShayna.vue';
import HeroShayna from '@/components/HeroShayna.vue';
import WomanShayna from '@/components/WomanShayna.vue';
import InstaShayna from '@/components/InstaShayna.vue';
import PartnerShayna from '@/components/PartnerShayna.vue';

export default {
  name: 'Home',
  components: {
    HeaderShayna,
    HeroShayna,
    WomanShayna,
    InstaShayna,
    PartnerShayna
  }
}
</script>
