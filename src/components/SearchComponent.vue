<template>
    <div class="d-flex justify-content-center align-items-center">
        <div class="box">
            <p>Adasdasd</p>
            <mdb-select multiple selectAll search :options="[
    {value: 'Option 1', text: 'USA'},
    {value: 'Option 2', text: 'Germany'},
    {value: 'Option 3', text: 'France'},
    {value: 'Option 4', text: 'Poland'},
    {value: 'Option 5', text: 'Japan'}
  ]"/>
        </div>
    </div>
</template>


<script>
    import {mdbSelect} from 'mdbvue';

    export default {
        name: 'SearchComponent',
        components: {
            mdbSelect
        }
    }
</script>


<style>

    .box {
        margin: 150px;
        width: 700px;
        height: 3000px;
        color: red;
        background-color: #3f51b5;
    }

</style>
