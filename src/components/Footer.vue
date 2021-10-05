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
                            </li>
                            <div class="navbarFaq"> <!-- navbar Faq -->
                                <li class="li-navbar spaceNavbar" v-for="(faqAbout, index) in faqAbouts" :key="index">
                                    <a :class="(faqAbout.current)" href="faqAbout.url">
                                        <h4 class="lightgray">{{ faqAbout.text }}</h4>
                                    </a>
                                </li>
                            </div>    
                        </ul>
                    </section>
                    <section class="faq-services spaceToRight">
                        <ul>
                            <li>
                                <h3 class="whitePalette">Services</h3>
                            </li>
                            <div class="navbarFaq"><!-- navbar Faq -->
                                <li class="li-navbar spaceNavbar" v-for="(faqService, index) in faqServices" :key="index">
                                    <a :class="(faqService.current)" href="faqService.url">
                                        <h4 class="lightgray">{{ faqService.text }}</h4>
                                    </a>
                                </li>
                            </div>       
                        </ul>
                    </section>
                    <section class="faq-support">
                        <ul>
                            <li>
                                <h3 class="whitePalette">Support</h3>
                            </li>
                            <div class="navbarFaq"><!-- navbar Faq -->
                                <li class="li-navbar spaceNavbar" v-for="(faqSupport, index) in faqSupports" :key="index">
                                    <a :class="(faqSupport.current)" href="faqSupport.url">
                                        <h4 class="lightgray">{{ faqSupport.text }}</h4>
                                    </a>
                                </li>
                            </div>       
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
                    <h5 class="spaceToRight">2020 NEXGEN is Proudly Powered by</h5>
                    <h5 class="little-faq greenPalette spaceToRight">Codings</h5>
                    <h5>.</h5>
                </li>
            </ul>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'Footer',
    data() {
        return {
            faqAbouts: [
                {
                    text: "The Company",
                    url: "#",
                    current: false,
                },
                {
                    text: "institutional",
                    url: "#",
                    current: false,
                },
                {
                    text: "Social & Events",
                    url: "#",
                    current: false,
                },
                {
                    text: "Innovation",
                    url: "#",
                    current: false,
                },
                {
                    text: "Environment",
                    url: "#",
                    current: false,
                },
                {
                    text: "Technology",
                    url: "#",
                    current: false,
                },
            ],
            faqServices: [
                {
                    text: "Audit & Assurance",
                    url: "#",
                    current: false,
                },
                {
                    text: "Financial Advisory",
                    url: "#",
                    current: false,
                },
                {
                    text: " Analystics M&A",
                    url: "#",
                    current: false,
                },
                {
                    text: "Middle Marketing",
                    url: "#",
                    current: false,
                },
                {
                    text: "Legal Consulting",
                    url: "#",
                    current: false,
                },
                {
                    text: "Regulatory Risk",
                    url: "#",
                    current: false,
                },
            ],
            faqSupports: [
                {
                    text: "Responsability",
                    url: "#",
                    current: false,
                },
                {
                    text: "Terms of Use",
                    url: "#",
                    current: false,
                },
                {
                    text: "About Cookies",
                    url: "#",
                    current: false,
                },
                {
                    text: "Privacy Policy",
                    url: "#",
                    current: false,
                },
                {
                    text: "Accessibility",
                    url: "#",
                    current: false,
                },
                {
                    text: "Information",
                    url: "#",
                    current: false,
                },
            ],
        }
    }
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