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
        <div class="footer-bottom container">
            <a class="cta" href=""></a>
            <div class="social">
                <h3></h3>
                <ul>
                    <li><img src="" alt=""></li>
                </ul>
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

        }
    }
</style>