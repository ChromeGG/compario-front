<template>
    <div class="box night-fade-gradient">
        <mdb-container>
            <mdb-row>
                <mdb-col col="9">
                    <input class="form-control" type="text" placeholder="Input value " aria-label="Search"/>
                </mdb-col>
                <mdb-col col="3">
                    <template>
                        <select class="browser-default custom-select">
                            <option value="1" selected>Money</option>
                            <option value="2">Speed</option>
                            <option value="3">Weight</option>
                        </select>
                    </template>
                </mdb-col>
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

    .form-control::placeholder {
        font-style: italic;
    }

    .box {
        margin-top: 5%;
        margin-bottom: 5%;
        padding: 10px;
        height: 300px;
        background-color: #b8d2fc;
        border-radius: 20px;
    }

</style>
