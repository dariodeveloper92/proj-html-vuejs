<template>
    <main>
        <!-- main-first -->
        <div id="main-first">
            <section class="section-center">
                <ul>
                    <li class="li-vertical">
                        <h6> INTRODUTION VIDEO </h6>
                    </li>
                    <li class="li-vertical">
                        <h1> Advisory Performance </h1>
                    </li>
                    <li class="li-vertical">
                        <p>Financial executives need to review their strategies, operating models and capabilities so that their areas can generate sound information for better decision making.</p>
                    </li>
                    <li class="li-vertical">
                        <a href="#">
                            <img class="box-img" alt="jumbotron" src="../assets/video-1.jpg">
                        </a>
                    </li>
                </ul>
            </section>
        </div>
        <!-- main-second -->
        <div id="main-second">
            <section class="section-center">
                <ul>
                    <li class="li-vertical">
                        <h5> WHAT ARE WE DOING </h5>
                    </li>
                    <li class="li-vertical">
                        <h1> Results in Numbers </h1>
                    </li>
                </ul>
            </section>
            <section class="box-numbers">
                <ul>
                    <li>
                        <h1>128</h1>
                        <h2>Certifications</h2>
                    </li>
                </ul>
                <ul>
                    <li>
                        <h1>230</h1>
                        <h2>Employees</h2>
                    </li>
                </ul>
                <ul>
                    <li>
                        <h1>517</h1>
                        <h2>Customers</h2>
                    </li>
                </ul>
                <ul>
                    <li>
                        <h1>94</h1>
                        <h2>Countries Served</h2>
                    </li>
                </ul>
            </section>
        </div>
        <!-- main-third -->
        <div id="main-third">
            <section class="section-center">
                <ul>
                    <li class="li-vertical">
                        <h5> OUR BUSINESS AREAS </h5>
                    </li>
                    <li class="li-vertical">
                        <h1> Excellence in Services </h1>
                    </li>
                </ul>
            </section>
            <section class="box-numbers">
                <ul>
                    <li class="li-vertical">
                        <p>We are leades in providing consultancy services with a set of cutting-edge technologies and a team of experienced and renowned professionals. These are some options that you can hire.</p>
                        <button> SEE ALL </button>
                    </li>
                </ul>
            </section>
            <div class="box-cards">
                <section class="card">
                    <ul>
                        <li class="icons">
                            <i class="fas fa-network-wired"></i>
                            <i class="fas fa-arrow-right"></i>
                        </li>
                    </ul>
                    <ul>
                        <li>
                            <h1>Audit 6 Assurance</h1>
                            <p>Lorem ipsum dolor sit amet consecutur adipiscing elit.</p>
                        </li>
                    </ul>
                </section>
                <section class="card">
                    <ul>
                        <li class="icons">
                            <i class="fas fa-briefcase"></i>
                            <i class="fas fa-arrow-right"></i>
                        </li>
                    </ul>
                    <ul>
                        <li>
                            <h1>Financial Advisory</h1>
                            <p>Lorem ipsum dolor sit amet consecutur adipiscing elit.</p>
                        </li>
                    </ul>
                </section>
                <section class="card">
                    <ul>
                        <li class="icons">
                            <i class="fas fa-chart-bar"></i>
                            <i class="fas fa-arrow-right"></i>
                        </li>
                    </ul>
                    <ul>
                        <li>
                            <h1>Analytics and M&A</h1>
                            <p>Lorem ipsum dolor sit amet consecutur adipiscing elit.</p>
                        </li>
                    </ul>
                </section>
            </div>
            <div class="box-cards">
                <section class="card">
                    <ul>
                        <li class="icons">
                            <i class="fas fa-plane"></i>
                            <i class="fas fa-arrow-right"></i>
                        </li>
                    </ul>
                    <ul>
                        <li>
                            <h1>Middle Marketing</h1>
                            <p>Lorem ipsum dolor sit amet consecutur adipiscing elit.</p>
                        </li>
                    </ul>
                </section>
                <section class="card">
                    <ul>
                        <li class="icons">
                            <i class="fas fa-globe"></i>
                            <i class="fas fa-arrow-right"></i>
                        </li>
                    </ul>
                    <ul>
                        <li>
                            <h1>Legal Consulting</h1>
                            <p>Lorem ipsum dolor sit amet consecutur adipiscing elit.</p>
                        </li>
                    </ul>
                </section>
                <section class="card">
                    <ul>
                        <li class="icons">
                            <i class="fas fa-inbox"></i>
                            <i class="fas fa-arrow-right"></i>
                        </li>
                    </ul>
                    <ul>
                        <li>
                            <h1>Regulatory Risk</h1>
                            <p>Lorem ipsum dolor sit amet consecutur adipiscing elit.</p>
                        </li>
                    </ul>
                </section>
            </div>
        </div>
        <!-- main-fourth -->
        <div id="main-fourth">
            
        </div>
        <!-- main-fifth -->
        <div id="main-fifth">
            
        </div>
        <!-- main-sixth -->
        <div id="main-sixth">
            
        </div>
        <!-- main-seventh -->
        <div id="main-seventh">
            
        </div>
    </main>
</template>

<script>
export default {
    name: 'Main',
}
</script>

<style>
    /* main--------------------------------------- */
    main {
        width: 100%;
        height: 100%;
        background-color: lightblue;
    }

    /* main-first--------------------------------------- */
    #main-first {
        background-color: lime;
    }
    .box-img {
        object-fit: contain;
        width: 50%;
    }

    /* main-second--------------------------------------- */
    #main-second {
        background-color: lightblue;
    }

    .box-numbers {
        display: flex;
        justify-content: center;
        align-items: center;
        text-align: center;
    }

    /* main-third--------------------------------------- */
    #main-third {
        background-color: sienna;
        width: 100%;
    }

    .box-cards {
        display: flex;
        justify-content: space-around;
        width: 100%;
        height: 100%;
        padding: 10px;
    }

    .card {
        width: 250px;
        height: 250px;
        background-color: lightgray;
        border-radius: 10px;
        text-align: center;
    }
    
    /* main-fourth--------------------------------------- */
    #main-fourth {
        background-color: plum;
    }

    /* main-fifth--------------------------------------- */
    #main-fifth {
        background-color: gold;
    }
    /* main-sixth--------------------------------------- */
    #main-sixth {
        background-color: tomato;
    }
    /* main-seventh--------------------------------------- */
    #main-seventh {
        background-color: blueviolet;
    }
</style>