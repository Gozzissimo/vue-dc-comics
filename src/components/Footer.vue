<template>
    <footer>
        <div class="footer-top">
            <div class="container flex">
                <div class="col">
                    <h4>dc comics</h4>
                    <ul>
                        <li><a href="">Lorem</a></li>
                        <li><a href="">Lorem</a></li>
                        <li><a href="">Lorem</a></li>
                        <li><a href="">Lorem</a></li>
                        <li><a href="">Lorem</a></li>
                        <li><a href="">Lorem</a></li>
                    </ul>
                    <h4>shop</h4>
                    <ul>
                        <li><a href="">Lorem Ipsum lungo</a></li>
                        <li><a href="">Lorem</a></li>
                    </ul>
                </div>
                <div class="col">
                    <h4>dc</h4>
                    <ul>
                        <li><a href="">Lorem</a></li>
                        <li><a href="">Lorem</a></li>
                        <li><a href="">Lorem</a></li>
                        <li><a href="">Lorem</a></li>
                        <li><a href="">Lorem</a></li>
                        <li><a href="">Lorem</a></li>
                        <li><a href="">Lorem</a></li>
                    </ul>
                </div>
                <div class="col">
                    <h4>sites</h4>
                    <ul>
                        <li><a href="">Lorem</a></li>
                        <li><a href="">Lorem</a></li>
                        <li><a href="">Lorem</a></li>
                        <li><a href="">Lorem</a></li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="footer-bottom">
            <div class="container flex">
                <div class="side-left">
                    <a class="cta" href="">SIGN-UP NOW!</a>
                </div>
                <div class="side-right flex">
                    <h3>FOLLOW US</h3>
                    <ul class="social flex">
                        <li>
                            <a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a></li>
                        <li>
                            <a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a></li>
                        <li>
                            <a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a></li>
                        <li>
                            <a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a></li>
                        <li>
                            <a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a></li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'Footer',
    data() {
        return {
            
        }
    }
}
</script>

<style lang="scss" scoped>
@import "../assets/scss/partials/_variables.scss";

    footer {
        .footer-top {
            background-image: url("../assets/img/footer-bg.jpg");
            background-size: cover;
            .container {
                padding: 20px 0;
                background-image: url("../assets/img/dc-logo-bg.png");
                background-position-x: right;
                background-position-y: 50%;
                background-repeat: no-repeat;
            }
            .col {
                margin-right: 20px;
                h4 {
                    text-transform: uppercase;
                    font-size: 1.2em;
                    color: white;
                    margin-top: 10px;
                }
                ul {
                    margin-top: 10px;
                    li a {
                        color: grey;
                    }
                }
            }
        }
        .footer-bottom {
            background-color: $blackFontColor;
            .container {
                justify-content: space-between;
                align-items: center;
                padding: 1.5em 0;
                .side-left {
                    .cta {
                        display: block;
                        padding: 1em;
                        color: $whiteFontColor;
                        border: 2px solid $blueFontColor;
                    }
                }
                .side-right {
                    align-items: center;
                    h3 {
                        color: $blueFontColor;
                        margin-right: 10px;
                    }
                    .social li a{
                        margin-right: 10px;
                        display: block;
                    }
                }
            }
        }
    }
</style>