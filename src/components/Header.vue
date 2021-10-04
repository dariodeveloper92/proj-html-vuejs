<template>
    <header>
        <div id="header-top">
            <ul class="horizontal-space">
                <li class="li-horizontal">
                    <i class="fas fa-clock"></i>
                    <h5>Open hours Mon-Sat-9:00-18:00</h5>
                </li>
                <li class="li-horizontal">
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
            <div id="container-jumbotron">
                <img class="img-jumbotron" alt="jumbotron" src="../assets/bg-2.jpg">
                <section class="section-top">
                    <ul class="horizontal-space">
                        <li class="li-horizontal">
                            <h3>NEXGEN</h3>
                        </li>
                        <li class="li-horizontal">
                            <h4>HOME</h4>
                            <h4>ABOUT</h4>
                            <h4>SERVICES</h4>
                            <h4>TEAM</h4>
                            <h4>BLOG</h4>
                            <i class="far fa-user"></i>
                            <button class="greenButton"> GET IN TOUCH </button>
                        </li>
                    </ul>
                </section>
                <section class="section-center">
                    <ul>
                        <li class="li-vertical">
                            <h1 class="title"> Financial Risk </h1>
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
        // background-color: blue;
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
        //position: relative;
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

    /* common---------------------------------------- */
    

</style>