<template>
  <div class="footer-bottom">
      <div class="container">
            <button>Sign-up now!</button>
            <div>
                <ul>
                    <li>
                        <a href="#">follow us</a>
                    </li>
                    <li>
                        <a href="#"><img src="../assets/img/footer-facebook.png" alt="facebook"></a>
                    </li>
                    <li>
                        <a href="#"><img src="../assets/img/footer-twitter.png" alt="twitter"></a>
                    </li>
                    <li>
                        <a href="#"><img src="../assets/img/footer-youtube.png" alt="youtube"></a>
                    </li>
                    <li>
                        <a href="#"><img src="../assets/img/footer-pinterest.png" alt="pinterest"></a>
                    </li>
                    <li>
                        <a href="#"><img src="../assets/img/footer-periscope.png" alt="periscope"></a>
                    </li>
                </ul>
            </div>
      </div>
  </div>
</template>

<script>
export default {
    name: 'FooterSmall',
}
</script>

<style scoped>
.footer-bottom {
    padding: 2rem 0;
    background-color: #303030;
}

.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

/* button */
button {
    font-size: 16px;
    font-weight: 700;
    text-transform: uppercase;
    padding: 1rem;
    color: #fff;
    background-color: #303030;
    border: 2px solid #0282f9;
    cursor: pointer;
}

button:hover {
    opacity: 0.5;
}

ul {
    display: flex;
    list-style: none;
    align-items: center;
}

li a {
    text-transform: uppercase;
    text-decoration: none;
    margin-right: 1.5rem;
    cursor: pointer;
}

li:last-child a {
    margin-right: 0;
}

li:first-child a {
    font-size: 20px;
    font-weight: 700;
    color: #0282f9;
}

li a:hover {
    opacity: 0.5;
}

</style>