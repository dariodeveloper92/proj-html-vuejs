<template>
    <footer>
        <div id="footer-top">
            <h1> Footer top </h1>
        </div>
        <div id="footer-bottom">
            <h1> Footer bottom </h1>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'Footer',
}
</script>

<style>
    footer {
        width: 100%;
        height: 25vh;
    }

    #footer-top {
        width: 100%;
        height: 80%;
        background-color: purple;
    }

    #footer-bottom {
        width: 100%;
        height: 20%;
        background-color: peru;
    }
</style>