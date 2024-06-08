<script>
import { RouterLink, RouterView } from 'vue-router'
import HeaderComponent from './components/Layouts/HeaderComponent.vue'
import TopNavComponent from './components/Layouts/TopNavComponent.vue'
import HeroComponent from './components/HeroComponent.vue'
import ProductComponent from './components/ProductComponent.vue'

export default {
  components:{
    HeaderComponent,
    TopNavComponent,
    HeroComponent,
    ProductComponent
  }

}

</script>

<template>
  <TopNavComponent></TopNavComponent>
  <HeaderComponent />
  <HeroComponent />
  <ProductComponent/>
 <RouterView />
</template>
