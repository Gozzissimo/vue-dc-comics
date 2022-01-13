<template>
    <header>
        <div class="container flex">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="dc-logo">
            </div>
            <ul class="flex">
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
        </div>
    </header>
</template>

<script>
export default {
    name: 'Header',
    data() {
        return {
            
        }
    }
}
</script>

<style lang="scss" scoped>
    @import "../assets/scss/partials/_variables.scss";
    header {
        margin: 20px 0;
        color: $blackFontColor;
        font-size: 1em;
        .container {
            justify-content: space-between;
            .logo img {
                width: 70%;
            }      
            ul {
                align-items: center;
                li a {
                    display: block;
                    padding: 1em;
                    text-transform: uppercase;
                    &:hover,
                    &:focus,
                    &:active {
                        color: $blueFontColor;
                        border-bottom: 2px solid $blueFontColor;
                    }
                }
            }
        }
    }
</style>