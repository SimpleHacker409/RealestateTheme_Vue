<template>
  <div id="app" class="w-full h-screen">
   <LandingPage/>
   <ClientBrand/>
   <Aboutus/>
   <CarouselComponent/>
   <Populartrading/>
   <RecentProperty/>
   <ClientSay/>
   <SubscribeCard/>
   <FooterComponent/>
  </div>
</template>

<script>
import { data } from 'browserslist'
import HelloWorld from './components/HelloWorld.vue'
import LandingPage from './components/LandingPage.vue'
import Aboutus from './components/AboutUs.vue'
import ClientBrand from './components/ClientBrand.vue'
import Populartrading from './components/PopularTrading.vue'
import RecentProperty from './components/RecentProperty.vue'
import ClientSay from './components/ClientSay.vue'
import SubscribeCard from './components/SubscribeCard.vue'
import FooterComponent from './components/FooterComponent.vue'
import CarouselComponent from './components/CarouselComponent.vue'

export default {
  name: 'App',
  components: {
    LandingPage,
    Aboutus,
    ClientBrand,
    Populartrading,
    RecentProperty,
    ClientSay,
    SubscribeCard,
    FooterComponent,
    CarouselComponent,
  }
}
</script>

<style>

</style>
