<template>

    <div class="footer-top">
        <div class="container">
            <div class="list-links cols">
                <nav class="col">
                    <h3>dc comics</h3>
                    <ul>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Comics</a>
                        </li>
                        <li>
                            <a href="#">Movies</a>
                        </li>
                        <li>
                            <a href="#">TV</a>
                        </li>
                        <li>
                            <a href="#">Games</a>
                        </li>
                        <li>
                            <a href="#">Videos</a>
                        </li>
                         <li>
                            <a href="#">News</a>
                        </li>
                    </ul>
                    <h3>Shop</h3>
                     <ul>
                        <li>
                            <a href="#">Shop DC</a>
                        </li>
                        <li>
                            <a href="#">Shop DC Collectibles</a>
                        </li>
                    </ul>
                </nav>
                 <nav class="col">
                    <h3>dc</h3>
                    <ul>
                        <li>
                            <a href="#">Terms Of Use</a>
                        </li>
                        <li>
                            <a href="#">Privacy policy(New)</a>
                        </li>
                        <li>
                            <a href="#">Ad Choices</a>
                        </li>
                        <li>
                            <a href="#">Advertising</a>
                        </li>
                        <li>
                            <a href="#">Jobs</a>
                        </li>
                        <li>
                            <a href="#">Subscriptions</a>
                        </li>
                        <li>
                            <a href="#">Talent Workshops</a>
                        </li>
                        <li>
                            <a href="#">CPS Certificates</a>
                        </li>
                        <li>
                            <a href="#">Ratings</a>
                        </li>
                        <li>
                            <a href="#">Shop Help</a>
                        </li>
                        <li>
                            <a href="#">Contact Us</a>
                        </li>
                    </ul>
                </nav>
                <nav class="col">
                    <h3>Sites</h3>
                    <ul>
                        <li>
                            <a href="#">DC</a>
                        </li>
                        <li>
                            <a href="#">MAD Magazine</a>
                        </li>
                        <li>
                            <a href="#">DC Kids</a>
                        </li>
                        <li>
                            <a href="#">DC Universe</a>
                        </li>
                        <li>
                            <a href="#">DC Power Visa</a>
                        </li>
                    </ul>
                </nav>
            </div>

            <div class="cols">
                <img src="../assets/img/dc-logo-bg.png" alt="logo-big">
            </div>
        </div>
    </div>

</template>

<script>
export default {
    name: 'FooterBig',
}
</script>

<style scoped>
.footer-top {
    background-image: url('../assets/img/footer-bg.jpg');
}

.container {
    display: flex;
}

.cols {
    height: 400px;
    flex-basis: 600px;
    display: flex;
}

.cols img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.col {
    flex-basis: calc(100% / 3);
}

/* list links */
.list-links {
    padding: 2rem 0;
}

h3 {
    text-transform: uppercase;
    color: #fff;
    padding: 1rem 0;
}

ul {
    list-style: none;
}

li a {
    font-size: 14px;
    line-height: 22px;
    color: #959595;
    text-decoration: none;
    cursor: pointer;
}

li a:hover {
    color: #fff;
}

</style>