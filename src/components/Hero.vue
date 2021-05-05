<template>
  <section class="hero">
      <div class="container boxes">
            <button class="current">Current Series</button>

            <Cards 
                v-for="(product,index) in products" 
                :key="index"
                :details="product"
            />

            <button class="load">Load More</button>
      </div>
  </section>
</template>

<script>
import Cards from '@/components/Cards.vue';
import prodItems from '@/data/prodItems.js';

export default {
    name: 'Hero',
    components: {
        Cards,
    },
    data() {
        return {
            products: prodItems,
        }
    }
}
</script>

<style scoped>
.hero {
    background-color: #1c1c1c;
    padding-top: 60px;
    padding-bottom: 100px;
}

.boxes {
    display: flex;
    flex-wrap: wrap;
    position: relative;
}

button {
    font-weight: bold;
    text-transform: uppercase;
    color: #fff;
    background-color: #0282f9;
    padding: 1rem 4rem;
    border-color: transparent;
    margin: 2rem;
    position: absolute;
}

.load {
    font-size: 18px;
    left: 50%;
    transform: translateX(-50%);
    bottom: -100px; 
}

.current {
    font-size: 22px;
    left: -60px;
    top: -120px;
}

</style>