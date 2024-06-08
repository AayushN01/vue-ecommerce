<script>
import { RouterLink, RouterView } from 'vue-router'
import HeaderComponent from './components/Layouts/HeaderComponent.vue'
import TopNavComponent from './components/Layouts/TopNavComponent.vue'

export default {
  components:{
    HeaderComponent,
    TopNavComponent
  }

}

</script>

<template>
  <TopNavComponent></TopNavComponent>
  <HeaderComponent />
 <RouterView />
</template>
