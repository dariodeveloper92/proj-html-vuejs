<template>
    <header>
        <div id="header-top">
            <ul class="horizontal-space">
                <li class="li-horizontal">
                    <i class="spaceToRight fas fa-clock"></i>
                    <h5>Open Hours: Mon - Sat - 9:00 - 18:00</h5>
                </li>
                <li class="li-horizontal">
                    <i class="spaceToRight fas fa-phone-alt"></i>
                    <h5>+1(305)1234-5678</h5>
                    <i class="spaceToRight fas fa-envelope"></i>
                    <h5>hello@example.com</h5>
                    <i class="spaceToRight fab fa-facebook-f"></i>
                    <i class="spaceToRight fab fa-twitter"></i>
                    <i class="spaceToRight fab fa-linkedin-in"></i>
                </li>
            </ul>
        </div>
        <div id="header-bottom">
            <div id="container-jumbotron">
                <img class="img-jumbotron" alt="jumbotron" src="../assets/bg-2.jpg">
                <section class="section-top">
                    <ul class="horizontal-space">
                        <li class="li-horizontal">
                            <h3 class="green-subtitle">NEX</h3>
                            <h3>GEN</h3>
                        </li>
                        <div class="navbarMenu"><!-- navbar Menu -->
                            <li class="li-navbar spaceNavbar" v-for="(navBar, index) in navBars" :key="index">
                                <a :class="(navBar.current)" href="navBar.url">
                                    <h4>{{ navBar.text }}</h4>
                                </a>
                            </li>
                        </div>
                        <li>    
                            <i class="far fa-user"></i>
                            <button class="greenButton"> GET IN TOUCH </button>
                        </li>
                    </ul>
                </section>
                <section class="section-center">
                    <ul>
                        <li class="li-vertical">
                            <h1 class="title big-title"> <b>Financial Risk</b> </h1>
                        </li>
                        <li class="li-vertical">
                            <p>The right putcomes depend on continuous rigor in governance, models, and, processes across the finance function.</p>
                        </li>
                        <div class="box-button">
                            <div class="li-button">
                                <button class="greenButton padding"> GET IN TOUCH </button>
                                <button class="transparentButton"> READ MORE </button>
                            </div>
                        </div>
                    </ul>
                </section>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    name: 'Header',
    data() {
        return {
            navBars: [
                {
                    text: "HOME",
                    url: "#",
                    current: false,
                },
                {
                    text: "ABOUT",
                    url: "#",
                    current: false,
                },
                {
                    text: "SERVICES",
                    url: "#",
                    current: false,
                },
                {
                    text: "TEAM",
                    url: "#",
                    current: false,
                },
                {
                    text: "BLOG",
                    url: "#",
                    current: false,
                },
            ]
        }
    }
}
</script>

<style  lang="scss">
@import '../styles/vars.scss';

    /* header--------------------------------------- */
    header {
        width: 100%;
        height: 100%;
    }
    /* header-top------------------------------------ */
    #header-top {
        width: 100%;
        height: 10vh;
        background-color: $smalt-blue;
    }
    
    /* header-bottom---------------------------------- */
    #header-bottom {
        width: 100%;
        height: 100%;
        background-color: red;
    }

    #container-jumbotron {
        width: 100%;
        height: 100vh;
    }

    .img-jumbotron {
        width: 100%;
        height: 100%;
        object-fit: cover;
        position: absolute;
        margin-bottom: 0;
        border-radius: 0;
    }

    .section-top,
    .section-center {
        position: relative;
        display: flex;
        justify-content: center;
    }
</style>