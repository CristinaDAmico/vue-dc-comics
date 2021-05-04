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
              <li>
                  <a href="#">characters</a>
              </li>
              <li>
                  <a href="#">comics</a>
              </li>
              <li>
                  <a href="#">movies</a>
              </li>
              <li>
                  <a href="#">tv</a>
              </li>
               <li>
                  <a href="#">games</a>
              </li>
              <li>
                  <a href="#">collectibles</a>
              </li>
               <li>
                  <a href="#">videos</a>
              </li>
               <li>
                  <a href="#">fans</a>
              </li>
               <li>
                  <a href="#">news</a>
              </li>
               <li>
                  <a href="#">shop</a>
              </li>
          </ul>
      </nav>
  </header>

</div>
 
</template>

<script>
export default {
    name: 'Header',
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

li a:hover {
    color: #0282f9;
    border-bottom: 3px solid #0282f9;
}

</style>