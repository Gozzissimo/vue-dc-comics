<template>
    <main>
        <section class="main-top">
            <div class="jumbotron">
                <h1>
                    CURRENT SERIES
                </h1>
            </div>
            <div class="container">
                <div class="comics flex">
                <ComicsElement 
                    v-for="(comic, index) in comics"
                    :key="index"
                    :thumbElement="comic.thumb"
                    :seriesName="comic.series"
                />
                </div>
                <div class="button">
                    <a class="load-more" href="#">
                        LOAD MORE
                    </a>
                </div>
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
import ComicsElement from "./ComicsElement.vue";

export default {
    name: 'Main',
    components: {
        ComicsElement,
    },

    data() {
        return {
            comics: [
                {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
                    "price": "$19.99",
                    "series": "Action Comics",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
                    "price": "$3.99",
                    "series": "American Vampire 1976",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
                    "price": "$16.99",
                    "series": "Aquaman",
                    "type": "graphic novel"
                },
                {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
                    "price": "$2.99",
                    "series": "Batgirl",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
                    "price": "$3.99",
                    "series": "Batman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
                    "price": "$2.99",
                    "series": "Batman Beyond",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
                    "price": "$3.99",
                    "series": "Batman/Superman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
                    "price": "$4.99",
                    "series": "Batman/Superman Annual",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
                    "price": "$5.99",
                    "series": "Batman: The Joker War Zone",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
                    "price": "$6.99",
                    "series": "Batman: Three Jokers",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
                    "price": "$4.99",
                    "series": "Batman: White Knight Presents: Harley Quinn",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
                    "price": "$16.99",
                    "series": "Catwoman",
                    "type": "graphic novel"
                }
            ]
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
            .jumbotron {
                height: 400px;
                background-image: url("../assets/img/jumbotron.jpg");
                background-size: cover;
                position: relative;
                margin-bottom: 20px;
                h1 {
                    background-color: $blueFontColor;
                    display: inline-block;
                    position: absolute;
                    top: 92%;
                    left: 15%;
                    padding: 0.3em 1em
                }
            }
            .container {
                .comics {
                    flex-wrap: wrap;
                    align-items: center;
                    justify-content: center;
                    padding-top: 20px;
                    padding-bottom: 20px;
                    margin-bottom: 20px;
                }
                .button {
                    text-align: center;
                    margin-bottom: 20px;
                    .load-more {
                        display: inline-block;
                        color: white;
                        background-color: $blueFontColor;
                        border: none;
                        padding: 10px 50px;
                    }
                }
            }
        }
        .main-bottom {
            background-color: $blueFontColor;
            padding: 30px 0;
            .container {
                ul {
                    align-items: center;
                    justify-content: center;
                    li {
                        align-items: center;
                        flex-basis: calc(100% / 5);
                        img {
                            width: 40px;
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