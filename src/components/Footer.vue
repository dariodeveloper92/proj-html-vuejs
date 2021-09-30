<template>
    <footer>
        <div id="footer-top">
            <div class="box-faq">
                <section class="section-nexgen">
                <ul>
                    <li>
                        <h1> NEXGEN </h1>
                    </li>
                    <li>
                        <p>A Functional HTML Template for Corporate & Business.</p>
                    </li>
                    <li>
                        <a class="li-horizontal" href="#">
                            <i class="fas fa-phone-alt"></i>
                            <h5>+1(305)1234-5678</h5>
                        </a>
                    </li>
                    <li>
                        <a class="li-horizontal"  href="#">
                            <i class="fas fa-envelope"></i>
                            <h5>hello@example.com</h5>
                        </a>
                    </li>
                    <li>
                        <a class="li-horizontal"  href="#">
                            <i class="fas fa-map-marker-alt"></i>
                        <h5>Main Avenue, p87</h5>
                        </a>
                    </li>
                    <li>
                        <button class="padding"> GET IN TOUCH </button>
                    </li>
                </ul>
            </section>
            <section class="faq-about">
                <ul>
                    <li>
                        <h1>About</h1>
                        <h5>The Company</h5>
                        <h5>institutional</h5>
                        <h5>Social & Events</h5>
                        <h5>Innovation</h5>
                        <h5>Environment</h5>
                        <h5>Technology</h5>
                    </li>
                </ul>
            </section>
            <section class="faq-services">
                <ul>
                    <li>
                        <h1>Services</h1>
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
                        <h1>Support</h1>
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

<style>
    /* footer------------------------------------ */
    footer {
        width: 100%;
        height: 100%;
        background-color: purple;
    }

    /* footer-top------------------------------------ */
    #footer-top {
        width: 100%;
        /* height: 100%; */
        display: flex;
        justify-content: space-around;
        align-items: center;
    }

    .box-faq {
        width: 80%;
        display: flex;
        justify-content: space-around;
        padding: 30px 0;
    }

    .section-nexgen,
    .faq-about,
    .faq-services,
    .faq-support {
        width: 250px;
        background-color: lightgray;
        border-radius: 10px;
        display: flex;
        justify-content: center;
        align-items: center;
        text-align: center;
    }

    /* footer-bottom----------------------------------- */
    #footer-bottom {
        width: 100%;
        /* height: 100%; */
        background-color: peru;
    }
</style>