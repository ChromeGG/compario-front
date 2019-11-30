<template>
    <div>
        <navigation/>
        <div class="d-flex justify-content-center align-items-center">
            <searchComponent/>
        </div>
    </div>
</template>

<script>
    import navigation from '../components/Navigation.vue';
    import searchComponent from '../components/SearchComponent.vue'

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
