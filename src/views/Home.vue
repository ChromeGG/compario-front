<template>
    <div>
        <navigation/>
        <div class="content">
            <mdb-container>
                <mdb-row>
                    <mdb-col col="2" style="background-color: grey">1 of 3</mdb-col>
                    <mdb-col col="8" style="background-color: #00bcd4">
                        <searchComponent/>
                    </mdb-col>
                    <mdb-col col="2" style="background-color: grey">3 of 3</mdb-col>
                </mdb-row>
            </mdb-container>
        </div>
    </div>
</template>

<script>
    import {mdbCol, mdbContainer, mdbRow} from 'mdbvue';

    import navigation from '../components/Navigation.vue';
    import searchComponent from '../components/SearchComponent.vue'

    export default {
        name: 'home',
        components: {
            navigation,
            mdbContainer,
            mdbRow,
            mdbCol,
            searchComponent
        }
    }
</script>

<style scoped>

    .content {
        margin-top: 74px;
    }

</style>
