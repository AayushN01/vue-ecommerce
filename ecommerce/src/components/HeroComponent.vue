<script>
import { RouterLink, RouterView } from 'vue-router'
import heroImage from '@/assets/images/black-shoes.png';

export default{
    name: 'HeroComponent',
    data(){
        return{
            heroImage: heroImage
        }
    }
}
</script>
<template>
    <div class="heroSection">
        <div class="hero-imageSide">
            <img :src="heroImage" alt="Hero">
        </div>
        <div class="hero-contentSide">
            <div class="upper-text p-10">
                <h3 class="text-uppercase">new arrival</h3>
            </div>
            <div class="middle-text p-10">
                <h4 class="text-uppercase">Lether Shoes</h4>
            </div>
            <div class="lower-text">
                <h5 class="text-uppercase p-10"> get extra 50% off</h5>
            </div>
            <div class="hero-btn">
                <button class="btn btn-primary p-10 mt-10">Buy Now</button>
            </div>
        </div>
    </div>
</template>