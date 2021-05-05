<template>
  <div id="app">

    <!-- HEADER -->
    <Header/>

    <!-- MAIN -->
    <main>
     <Jumbotron/>
     <Hero/>
     <Buy/>
    </main>

    <!-- FOOTER -->
    <footer>
      <FooterBig/>
      <FooterSmall/>
    </footer>
    
  </div>
</template>


<script>
import Header from '@/components/Header.vue';
import Jumbotron from '@/components/Jumbotron.vue';
import Hero from '@/components/Hero.vue';
import Buy from '@/components/Buy.vue';
import FooterBig from '@/components/FooterBig.vue';
import FooterSmall from '@/components/FooterSmall.vue';

export default {
  name: 'App',
  components: {
    Header,
    Jumbotron,
    Hero,
    Buy,
    FooterBig,
    FooterSmall
  },
};
</script>

<style lang="scss">
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Roboto Condensed', sans-serif;
}

.container {
  max-width: 1200px;
  margin: auto;
}

img {
  max-width: 100%;
}

</style>
