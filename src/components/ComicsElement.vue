<template>
    <div class="comic-container">
        <div class="img">
            <img :src="thumbElement" :alt="seriesName">
        </div>
        <h3>{{ seriesName }}</h3>
    </div>
</template>

<script>
export default {
    name: 'ComicsElement',
    props: ['thumbElement', 'seriesName']
}
</script>

<style lang="scss" scoped>
    .comic-container {
        flex-basis: calc((100% / 6) - 20px);
        margin: 0 10px 30px;
        .img {
            width: 200px;
            height: 200px;
            overflow: hidden;
            img {
                width: 100%;
            }
        }
    }
</style>