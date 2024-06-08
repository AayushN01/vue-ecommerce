<script>
    import productImage from '@/assets/images/product.png';

    export default {
        name: 'ProductComponent',
        data(){
            return{
                productImg: productImage
            }
        }
    }
</script>

<template>
    <div class="newArrivalsSection section-padding">
        <div class="section-title section-title-padding">
            <h2 class="text-uppercase text-center">New Arrivals</h2>
        </div>
        <div class="products-section container">
            <div class="product-list">
                <div class="product-item" v-for="item in 4" :key="item">
                    <div class="product-item-img">
                        <img :src="productImg" alt="Product">
                    </div>
                    <div class="product-item-content">
                        <div class="productName">
                            <h6>Hiking Shoe</h6>
                        </div>
                        <div class="productPrice">
                            <p>$500</p>
                        </div>
                        <div class="product-item-btns">
                            <a class="btn btn-primary">Add To Cart</a>
                            <a class="btn btn-primary">View Product</a>
                        </div>
                    </div>

                </div>
            </div>
            <div class="sectionBtn">
                <button class="btn btn-primary">View All Products</button>
            </div>
        </div>
    </div>
</template>