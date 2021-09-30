<template>
    <footer>
        <div id="footer-top">
            <section class="section-nexgen">
                <ul class="vertical-space">
                    <li class="li-vertical">
                        <h1> NEXGEN </h1>
                    </li>
                    <li class="li-vertical">
                        <p>A Functional HTML Template for Corporate & Business.</p>
                    </li>
                    <li>
                        <i class="fas fa-phone-alt"></i>
                        <h5>+1(305)1234-5678</h5>
                        <i class="fas fa-envelope"></i>
                        <h5>hello@example.com</h5>
                        <i class="fas fa-map-marker-alt"></i>
                        <h5>Main Avenue, p87</h5>
                    </li>
                    <li class="li-vertical">
                        <button class="padding"> GET IN TOUCH </button>
                    </li>
                </ul>
            </section>
            <section class="faq-about">

            </section>
            <section class="faq-services">

            </section>
            <section class="faq-support">
                
            </section>
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
    footer {
        width: 100%;
        height: 25vh;
    }

    #footer-top {
        width: 100%;
        /* height: 80%; */
        background-color: purple;
    }

    #footer-bottom {
        width: 100%;
        /* height: 20%; */
        background-color: peru;
    }
</style>