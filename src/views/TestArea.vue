<template>
    <div>
        <div class="bg">
            <p class="py-5 text-center">
                This example creates a half page background image.
                Try to resize the browser window to see how it always will cover the full screen (when scrolled to top),
                and that it scales nicely on all screen sizes.
            </p>
        </div>
    </div>
</template>


<script>
    export default {
        name: "TestArea"
    }
</script>


<style scoped>
    body, html {
        height: 100%;
    }

    .bg {
        /* The image used */
        background-image: url("https://www.123freevectors.com/wp-content/original/169733-shiny-abstract-pink-and-blue-background-vector-image.jpg");

        /* Half height */
        height: 50%;

        /* Center and scale the image nicely */
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
    }
</style>
