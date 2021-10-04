<template>
    <footer>
        <div id="footer-top">
            <div id="container-jumbotron-footer">
                <img class="img-jumbotron" alt="jumbotron" src="../assets/bg-7.jpg">
                <div class="box-faq">
                    <section class="section-nexgen spaceToRight">
                        <li>
                            <div class="title-footer">
                                <h3 class="green-subtitle"> NEX </h3>
                                <h3> GEN </h3>  
                            </div>
                            <p class="paragrafo-seventh">A Functional HTML Template for Corporate & Business.</p>
                            <a class="li-horizontal lightgray" href="#">
                                <i class="lightgray fas fa-phone-alt"></i>
                                <h5>+1(305)1234-5678</h5>
                            </a>
                                <a class="li-horizontal lightgray"  href="#">
                                <i class="lightgray fas fa-envelope"></i>
                                <h5>hello@example.com</h5>
                            </a>
                            <a class="li-horizontal lightgray"  href="#">
                                <i class="lightgray fas fa-map-marker-alt"></i>
                                <h5>Main Avenue, 987</h5>
                            </a>
                            <button class="transparentButton"> GET IN TOUCH </button>
                        </li>
                    </section>
                    <section class="faq-about spaceToRight">
                        <ul>
                            <li>
                                <h3 class="whitePalette">About</h3>
                                <h5>The Company</h5>
                                <h5>institutional</h5>
                                <h5>Social & Events</h5>
                                <h5>Innovation</h5>
                                <h5>Environment</h5>
                                <h5>Technology</h5>
                            </li>
                        </ul>
                    </section>
                    <section class="faq-services spaceToRight">
                        <ul>
                            <li>
                                <h3 class="whitePalette">Services</h3>
                                <h5>Audit & Assurance</h5>
                                <h5>Financial Advisory</h5>
                                <h5>Analystics M&A</h5>
                                <h5>Middle Marketing</h5>
                                <h5>Legal Consulting</h5>
                                <h5>Regulatory Risk</h5>
                            </li>
                        </ul>
                    </section>
                    <section class="faq-support">
                        <ul>
                            <li>
                                <h3 class="whitePalette">Support</h3>
                                <h5>Responsibility</h5>
                                <h5>Terms of Use</h5>
                                <h5>About Cookies</h5>
                                <h5>Privacy Policy</h5>
                                <h5>Accessibility</h5>
                                <h5>Information</h5>
                            </li>
                        </ul>
                    </section>
                </div>
            </div>
        </div>
        <div id="footer-bottom">
            <ul class="horizontal-space">
                <li class="li-horizontal">
                    <h5>Enjoy the low price. We are tracking any intention of piracy.</h5>
                </li>
                <li class="li-horizontal">
                    <i class="far fa-copyright"></i>
                    <h5>2020 NEXGEN is Proudly Powered by Codings.</h5>
                </li>
            </ul>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'Footer',
}
</script>

<style  lang="scss">
@import '../styles/vars.scss';
    /* footer------------------------------------ */
    footer {
        width: 100%;
        height: 100vh;
        background-color: purple;
    }

    /* footer-top------------------------------------ */
    #footer-top {
        width: 100%;
        height: 90%;
    }

    .box-faq {
        width: 100%;
        //height: 10%;
        display: flex;
        justify-content: center;
        align-items: center;
        padding: 30px 0;
        color: lightgray;
    }

    .section-nexgen,
    .faq-about,
    .faq-services,
    .faq-support {
        width: 200px;
        height: 250px;
        //background-color:opacity($color: #000000);
        border: 3px solid gray; 
        border-radius: 10px;
        display: flex;
        justify-content: flex-start;
        align-items: center;
        position: relative;
        font-size: 12px;
    }

    .section-nexgen {
        background-color: transparent;
        border: 3px solid transparent;
    }
    /* footer-bottom----------------------------------- */
    #footer-bottom {
        width: 100%;
        height: 10%;
        background-color: $wood-smoke;
    }
</style>