<template>
    <div>
        <navigation/>
        <div class="content bg">
            <mdb-container>
                <mdb-row>
                    <mdb-col col="2"></mdb-col>
                    <mdb-col col="8">
                        <searchComponent/>
                    </mdb-col>
                    <mdb-col col="2"></mdb-col>
                </mdb-row>
            </mdb-container>
        </div>
        <footerComponent/>
    </div>
</template>

<script>
    import {mdbCol, mdbContainer, mdbRow} from 'mdbvue';

    import navigation from '../components/Navigation.vue';
    import searchComponent from '../components/SearchComponent.vue';
    import footerComponent from '../components/Footer.vue';

    export default {
        name: 'home',
        components: {
            navigation,
            mdbContainer,
            mdbRow,
            mdbCol,
            searchComponent,
            footerComponent
        }
    }
</script>

<style scoped>

    body, html {
        height: 100%;
    }

    .bg {
        /* The image used */
        /*background-image: url("/src/assets/background.jpg");*/
        background-image: url("https://www.123freevectors.com/wp-content/original/169733-shiny-abstract-pink-and-blue-background-vector-image.jpg");

        /* Full height */
        height: 100%;

        /* Center and scale the image nicely */
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;

    }

    .content {
        margin-top: 74px;
        height: 500px;
    }

</style>
