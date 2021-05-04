<template>
<div class="container">

    <header>
        <!-- logo -->
      <a href="#">
          <img src="../assets/img/dc-logo.png" alt="logo">
      </a>
        <!-- navigazione -->
      <nav>
          <ul>
              <li v-for="(link, index) in links" :key="index">
                  <a :class="{ active: link.current }" :href="link.url">{{ link.text }}</a>
              </li>
          </ul>
      </nav>
  </header>

</div>
 
</template>

<script>
export default {
    name: 'Header',
    data() {
        return {
           links: [
               { text: 'characters', url: '/', current: false },
               { text: 'comics', url: '/', current: true },
               { text: 'movies', url: '/', current: false },
               { text: 'tv', url: '/', current: false },
               { text: 'games', url: '/', current: false },
               { text: 'collectibles', url: '/', current: false },
               { text: 'videos', url: '/', current: false },
               { text: 'fans', url: '/', current: false },
               { text: 'news', url: '/', current: false },
               { text: 'shop', url: '/', current: false },
           ] 
        }
    }
}
</script>

<style scoped>

header {
    height: 80px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

a img {
    width: 50px;
}

ul {
    display: inline-flex;
    text-transform: uppercase;
    list-style: none;
}

li a {
    font-size: 12px;
    font-weight: 700;
    padding-bottom: 1.8rem;
    margin-right: 2rem;
    text-decoration: none;
    color: #1c1c1c;
    cursor: pointer;
}

li:last-child a {
    margin-right: 0;
}

li a:hover,
li a.active {
    color: #0282f9;
    border-bottom: 3px solid #0282f9;
}

</style>