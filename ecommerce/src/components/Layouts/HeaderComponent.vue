<script>
import { RouterLink, RouterView } from 'vue-router'

import logoImage from '@/assets/images/logo-new.png';
export default {
    name:'HeaderComponent',
    data(){
        return {
            logo: logoImage
        };
    }
}
</script>

<template>
    <nav>
        <div class="navbar-logo">
            <img :src="logo" alt="Logo">
        </div>
        <div class="navbar-menu">
            <ul class="menuList">
                <li class="menu-item">
                    <router-link to="/">Home</router-link>
                </li>
                <li class="menu-item">
                    <router-link to="/">About</router-link>
                </li>
                <li class="menu-item">
                    <router-link to="/">Shop</router-link>
                </li>
                <li class="menu-item">
                    <router-link to="/">Blogs</router-link>
                </li>
                <li class="menu-item">
                    <router-link to="/">Contact</router-link>
                </li>
            </ul>
        </div>
        <div class="navbar-cart">
            <a href="#">Cart <span>2</span></a>
        </div>
    </nav>
</template>