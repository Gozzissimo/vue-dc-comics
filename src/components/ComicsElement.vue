<template>
    <li>
        <div>
            <a href="#">
                <img :src="thumbElement" :alt="seriesName">
                <h3>{{ seriesName }}</h3>
            </a>
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
    
</style>