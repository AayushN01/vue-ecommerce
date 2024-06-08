<script>
import { RouterLink, RouterView } from 'vue-router'
import HeaderComponent from './components/Layouts/HeaderComponent.vue'
import TopNavComponent from './components/Layouts/TopNavComponent.vue'
import HeroComponent from './components/HeroComponent.vue';

export default {
  components:{
    HeaderComponent,
    TopNavComponent,
    HeroComponent
  }

}

</script>

<template>
  <TopNavComponent></TopNavComponent>
  <HeaderComponent />
  <HeroComponent />
 <RouterView />
</template>
