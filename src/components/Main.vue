<template>
    <main>
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