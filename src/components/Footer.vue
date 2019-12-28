<template>
    <div class="background d-flex align-items-center justify-content-center">
        <div>
            <div class="credits">
                <img src="https://img.icons8.com/nolan/42/github.png" alt="github icon">
                <img src="https://img.icons8.com/nolan/42/facebook-new.png" alt="fb icon">
            </div>
            <div>
                <p class="credits">©2019 - Adam Tkaczyk</p>
            </div>
        </div>
    </div>
</template>


<script>
    import {mdbBtn, mdbIcon} from 'mdbvue';

    export default {
        name: 'footerComponent',
        comments: {
            mdbIcon,
            mdbBtn,
        }
    }
</script>


<style scoped>

    .background {
        height: 200px;
        background-color: #272833;
    }

    .credits {
        color: white;
    }

    img {
        margin: 10px;
    }

</style>
