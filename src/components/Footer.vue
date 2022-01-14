<template>
<div class="container-footer">
    <div class="container-top">
        <div class="footer-top">
            <ul>
                <li>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <h4><a href="">digital comics</a></h4>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                    <h4><a href="">dc merchandise</a></h4>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                    <h4><a href="">subscription</a></h4>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                    <h4><a href="">comic shop locator</a></h4>
                </li>
                <li>
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                    <h4><a href="">dc power visa</a></h4>
                </li>
            </ul>
        </div>
    </div>
    <div class="footer-center">
        <div class="back-logo">
            <div class="container footer-center-sx">
                <div>
                <ul>
                    <li class="head-li">dc comics</li>
                    <li><a href="">Characters</a></li>
                    <li><a href="">Comics</a></li>
                    <li><a href="">Movies</a></li>
                    <li><a href="">TV</a></li>
                    <li><a href="">Games</a></li>
                    <li><a href="">Videos</a></li>
                    <li><a href="">News</a></li>
                </ul>
                <ul>
                    <li class="head-li">shop</li>
                    <li><a href="">Shop DC</a></li>
                    <li><a href="">Shop DC Collectibles</a></li>
                </ul>
                </div>
                <div>
                <ul>
                    <li class="head-li">dc</li>
                    <li><a href="">Terms Of Use</a></li>
                    <li><a href="">Privacy policy (New)</a></li>
                    <li><a href="">Ad Choices</a></li>
                    <li><a href="">Advertising</a></li>
                    <li><a href="">Jobs</a></li>
                    <li><a href="">Subscriptions</a></li>
                    <li><a href="">Talent Workshop</a></li>
                    <li><a href="">CPSC Certificates</a></li>
                    <li><a href="">Ratings</a></li>
                    <li><a href="">Shop Help</a></li>
                    <li><a href="">Contact Us</a></li>
                </ul>
                </div>
                <div>
                <ul>
                    <li class="head-li">Sites</li>
                    <li><a href="">DC</a></li>
                    <li><a href="">MAD Magazine</a></li>
                    <li><a href="">DC Kids</a></li>
                    <li><a href="">DC Universe</a></li>
                    <li><a href="">DC Power Visa</a></li>
                </ul>
                </div>

            </div>
        </div>
    </div>
    <div class="footer-bottom">
        <div class="container d-flex">
            <div class="footer-bottom-sx">
                <button>sign-up now!</button>
            </div>
            <div class="footer-bottom-dx">
                <h2>follow us</h2>
                <ul>
                    <li>
                        <a href="">
                            <img src="../assets/img/footer-facebook.png" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <img src="../assets/img/footer-twitter.png" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <img src="../assets/img/footer-youtube.png" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <img src="../assets/img/footer-pinterest.png" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <img src="../assets/img/footer-periscope.png" alt="">
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </div>    
</div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped> 
@import "../assets/scss/partials/_variables.scss";

    .container-top {
        padding: 3em 0;
        background-color: $blueDcomics;
        .footer-top {
            width: 80%;
            margin: 0 auto;
            ul {
                display: flex;
                justify-content: space-between;
                li {
                display: flex;
                align-items: center;
                list-style-type: none;
                    img {
                        width: 3em;
                        margin: 0 1em;
                    }
                    a{
                    text-decoration: none;
                    text-transform: uppercase;
                    color: white;
                    }
                }
            }
        }
    }
    .footer-center {
        background-image: url(../assets/img/footer-bg.jpg);
        position: relative;
        .back-logo {
            background-image: url(../assets/img/dc-logo-bg.png);
            background-repeat: no-repeat;
            background-position-x: 85%;
            background-position-y: 50%;
            .footer-center-sx {
                width: 80%;
                height: 100%;
                padding: 2em 0;
                display: flex;
                ul {
                    margin: 1em;
                    li {
                        list-style-type: none;
                        margin-bottom: 3px;
                        a {
                            text-decoration: none;
                            color: #7C7C7C;
                        } 
                    }
                    .head-li {
                        text-transform: uppercase;
                        font-weight: bold;
                        margin: 1em 0;
                        color: white;
                    }
                }
            }
        }
    }
    .footer-bottom {
        background-color: #303030;
        height: 100px;
        width: 100%;
        display: flex;
        align-items: center;

        .d-flex {
            display: flex; 
            .footer-bottom-sx {
                width: 50%;
                button {
                    text-transform: uppercase;
                    border: 1px solid $blueDcomics;
                    background-color: #303030;
                    font-weight: bold;
                    color: white;
                    padding: 1em;
                    cursor: pointer;
                }
            }
            .footer-bottom-dx {
                display: flex;
                width: 50%;
                justify-content: end;
                h2 {
                    text-transform: uppercase;
                    display: flex;
                    align-items: center;
                    color: $blueDcomics;
                    padding: 0 1em;
                }
                ul {
                    display: flex;
                    li {
                        list-style-type: none;
                        padding: 0.5em;
                    }
                }
            }
        }
    }

</style>