<template>
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
    <div class="footer-center">

    </div>    
</div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped> 
    .container-top {
        padding: 3em 0;
        background-color: #0282F9;
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
                    color: black;
                    }
                }
            }
        }
        .footer-center {
            background-image: url(../assets/img/footer-bg.jpg);
        }
    }

</style>