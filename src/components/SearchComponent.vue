<template>
    <div class="box">
        <div class="content">
            <mdb-form-inline class="active-purple active-purple-2">
                <mdbIcon icon="search"/>
                <input class="form-control mr-sm-2" type="text" placeholder="Search" aria-label="Search"/>
            </mdb-form-inline>
        </div>
    </div>
</template>


<script>
    import {mdbFormInline, mdbIcon} from 'mdbvue';

    export default {
        name: 'SearchComponent',
        components: {
            mdbIcon,
            mdbFormInline,
        }
    }
</script>


<style scoped>

    .active-purple-2 input[type=text]:focus:not([readonly]) {
        border: 2px solid #ce93d8;
        box-shadow: 0 1px 0 0 #ce93d8;
    }

    .content {
        margin: 25px;
    }

    mdbIcon {
        padding-right: 55px;
    }

    .box {
        margin: 150px;
        width: 700px;
        height: 1000px;
        background-color: #b8d2fc;
        border-radius: 25px;
    }

</style>
