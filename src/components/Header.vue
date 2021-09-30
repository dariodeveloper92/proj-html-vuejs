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
            <!-- <a href="#">
                <img alt="jumbotron" src="../assets/bg-2.jpg">
            </a> -->
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
                        <button> GET IN TOUCH </button>
                    </li>
                </ul>
            </section>
            <section class="section-center">
                <ul>
                    <li class="li-vertical">
                        <h1> Financial Risk </h1>
                    </li>
                    <li class="li-vertical">
                        <p>The right putcomes depend on continuous rigor in governance, models, and, processes across the finance function.</p>
                    </li>
                    <li class="li-vertical">
                        <button class="padding"> GET IN TOUCH </button>
                        <button> READ MORE </button>
                    </li>
                </ul>
            </section>
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
    /* header--------------------------------------- */
    header {
        width: 100%;
        height: 100%;
    }
    /* header-top------------------------------------ */
    #header-top {
        width: 100%;
        height: 10vh;
        background-color: blue;
    }
    
    /* header-bottom---------------------------------- */
    #header-bottom {
        width: 100%;
        height: 40vh;
        background-color: red;
        background-image: 
    }

    .section-center {
        display: flex;
        justify-content: center;
        /* align-content: space-around;
        justify-content: center; */
    }

    /* common---------------------------------------- */
    .horizontal-space {
        width: 80%;
        height: 100%;
        display: flex;
        justify-content: space-around;
        align-items: center;
    }

    /* .vertical-space {
        width: 80%;
        height: 100%;
        display: flex;
        align-content: space-around;
        justify-items: center;
    } */

    .li-horizontal {
        display: flex;
        align-items: center;
        text-align: center;
        position: relative;
        left: 8%;
    }

    .li-vertical {
        display: flex;
        justify-content: center;
        text-align: center;
    }

    i {
        color: white;
        padding: 10px;
    }

    h4 {
        color: white;
        padding: 5px;
    }

    .padding {
        padding: 5px;
    }

</style>