<template>
    <header>
        <div id="header-top">
            <ul>
                <li>
                    <i class="fas fa-clock"></i>
                    <h5>Open hours Mon-Sat-9:00-18:00</h5>
                </li>
                <li>
                    <i class="fas fa-phone-alt"></i>
                    <h5>+1(305)1234-5678</h5>
                    <i class="fas fa-envelope"></i>
                    <h5>hello@example.com</h5>
                    <i class="fab fa-facebook-f"></i>
                    <i class="fab fa-twitter"></i>
                    <i class="fab fa-linkedin-in"></i>
                </li>
            </ul>
        </div>
        <div id="header-bottom">
            <section class="section-top">
                <ul>
                <li>
                    
                </li>
                <li>
                    
                </li>
            </ul>
            </section>
            <section class="section-center"></section>
            <section class="section-bottom"></section>
        </div>
    </header>
</template>

<script>
export default {
    name: 'Header',
}
</script>

<style>
/* @import '../styles/vars.scss'; */

    header {
        width: 100%;
        height: 25vh;
    }

    #header-top {
        width: 100%;
        height: 20%;
        background-color: blue;
    }

    ul {
        width: 80%;
        height: 100%;
        display: flex;
        justify-content: space-around;
        align-items: center;
    }

    li {
        display: flex;
        align-items: center;
        text-align: center;
        position: relative;
        left: 8%;
    }

    i {
        color: white;
        padding: 10px;
    }

    #header-bottom {
        width: 100%;
        height: 80%;
        background-color: red;
    }

</style>