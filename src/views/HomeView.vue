<template>
  <div class="container mx-auto bg-amber-400">
    <MainHeader />
    <PresentationComp oriented="left" />
    <PresentationComp oriented=right />
    <StatsComp />
    <TabsComp />
    <MainFooter />
  </div>
</template>

<script>
// @ is an alias to /src
import MainHeader from '@/components/MainHeader.vue'
import PresentationComp from '@/components/PresentationComp.vue'
import StatsComp from '@/components/StatsComp.vue'
import TabsComp from '@/components/TabsComp.vue'
import MainFooter from '@/components/MainFooter.vue'

export default {
  name: 'HomeView',
  components: {
    MainHeader,
    PresentationComp,
    StatsComp,
    TabsComp,
    MainFooter,
    
  }
}
</script>
