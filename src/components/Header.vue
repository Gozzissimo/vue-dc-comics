<template>
    <header>
        <h1>{{ title }}</h1>
    </header>
</template>

<script>
export default {
    name: 'Header',
    data() {
        return {
            title: "Lorem Ipsum"
        }
    }
}
</script>

<style lang="scss" scoped>
    h1 {
        color: red;
    }
</style>