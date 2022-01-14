<template>
    <main>
        <section class="main-top">
            <div class="container flex">
                <h1>
                    --> Content goes here --
                </h1>
            </div>
        </section>
        <section class="main-bottom">
            <div class="container">
                <ul class="flex">
                    <li class="flex">
                        <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                        <a class="flex" href="#">
                            digital comics
                        </a>
                    </li>
                    <li class="flex">
                        <img src="../assets/img/buy-comics-merchandise.png" alt="">
                        <a class="flex" href="#">
                            dc merchandise
                        </a>
                    </li>
                    <li class="flex">
                        <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                        <a class="flex" href="#">
                            subscription
                        </a>
                    </li>
                    <li class="flex">
                        <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                        <a class="flex" href="#">
                            comic shop locator
                        </a>
                    </li>
                    <li class="flex">
                        <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                        <a class="flex" href="#">
                            dc power visa
                        </a>
                    </li>
                </ul>
            </div>
        </section>
    </main>
</template>

<script>
export default {
    name: 'Main',
    data() {
        return {
            
        }
    }
}
</script>

<style lang="scss" scoped>
    @import "../assets/scss/partials/_variables.scss";
    main {
        background-color: $mainTopBackground;
        .main-top {
            color: $whiteFontColor;
        }
        .main-bottom {
            background-color: $blueFontColor;
            padding: 30px 0;
            .container {
                ul {
                    justify-content: center;
                    li {
                        align-items: center;
                        img {
                            width: 20%;
                        }
                        a {
                            margin-left: 10px;
                            text-transform: uppercase;
                            color: $whiteFontColor;
                        } 
                    }
                }
            }
        }
    }
</style>