<template>
    <div class="box">
        <mdb-container>
            <mdb-row>
                <mdb-col col="8">SEARCH BAR</mdb-col>
                <mdb-col col="4">SELECT</mdb-col>
            </mdb-row>
        </mdb-container>
    </div>
</template>


<script>
    import {mdbCol, mdbContainer, mdbRow} from 'mdbvue';

    export default {
        name: 'SearchComponent',
        components: {
            mdbContainer,
            mdbRow,
            mdbCol
        }
    }
</script>


<style scoped>

    .box {
        background-color: #b8d2fc;
        border-radius: 20px;
    }

</style>
