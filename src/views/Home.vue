<template>
    <div>
        <navigation/>
        <searchComponent/>

    </div>
</template>

<script>
    import navigation from '../components/Navigation.vue';
    import searchComponent from '../components/SearchComponent'

    export default {
        name: 'home',
        components: {
            navigation,
            searchComponent
        }
    }
</script>

<style scoped>

</style>
