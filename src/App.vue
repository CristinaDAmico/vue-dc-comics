<template>
  <div id="app">

    <!-- HEADER -->
    <Header/>

    <!-- MAIN -->
    <main>
     <Content/>
     <Buy/>
    </main>

    <!-- FOOTER -->
    <footer>
      <FooterBig/>
    </footer>
    
  </div>
</template>


<script>
import Header from '@/components/Header.vue';
import Content from '@/components/Content.vue';
import Buy from '@/components/Buy.vue';
import FooterBig from '@/components/FooterBig.vue';

export default {
  name: 'App',
  components: {
    Header,
    Content,
    Buy,
    FooterBig,
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
