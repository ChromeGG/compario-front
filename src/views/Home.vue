<template>
    <div class="main-container">
        <navigation></navigation>
    </div>
</template>

<script>
    import navigation from '../components/Navigation.vue';

    export default {
        name: 'home',
        components: {
            navigation
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

    div {
        margin: 0 !important;
        padding: 0 0 0 0 !important;
    }

</style>
