<template>
    <li>
        <div class="comic-container">
            <img :src="thumbElement" :alt="seriesName">
            <h3>{{ seriesName }}</h3>
        </div>
    </li>
</template>

<script>
export default {
    name: 'ComicsElement',
    props: ['thumbElement', 'seriesName']
}
</script>

<style lang="scss" scoped>
    .comic-container {
        flex-basis: calc(100% / 6);
    }
</style>