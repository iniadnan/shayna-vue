<template>
  <div class="home">
    <HeaderShayna />
    <CarouselShayna />
    <Carousel2Shayna />
    <InstaShayna />
    <IklanShayna />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from '@/components/HeaderShayna.vue'
import CarouselShayna from '@/components/CarouselShayna.vue'
import Carousel2Shayna from '@/components/Carousel2Shayna.vue'
import InstaShayna from '@/components/InstaShayna.vue'
import IklanShayna from '@/components/IklanShayna.vue'
import FooterShayna from '@/components/FooterShayna.vue'

export default {
  name: 'Home',
  components: {
    HeaderShayna,
    CarouselShayna,
    Carousel2Shayna,
    InstaShayna,
    IklanShayna,
    FooterShayna
  }
}
</script>
