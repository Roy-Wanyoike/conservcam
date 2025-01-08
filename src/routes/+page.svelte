<script lang="ts">
    import Header from '$lib/Header.svelte';
    import Footer from '$lib/Footer.svelte';
</script>

<div class="boxed_wrapper">
    <!-- preloader -->
    <!-- <div class="loader-wrap">
        <div class="preloader">
            <div class="preloader-close">x</div>
            <div id="handle-preloader" class="handle-preloader about-page-2">
                <div class="animation-preloader">
                    <div class="spinner"></div>
                    <div class="txt-loading">
                        <span data-text-preloader="w" class="letters-loading">
                            c
                        </span>
                        <span data-text-preloader="e" class="letters-loading">
                            o
                        </span>
                        <span data-text-preloader="l" class="letters-loading">
                            n
                        </span>
                        <span data-text-preloader="d" class="letters-loading">
                            s
                        </span>
                        <span data-text-preloader="l" class="letters-loading">
                            e
                        </span>
                        <span data-text-preloader="f" class="letters-loading">
                            r
                        </span>
                        <span data-text-preloader="e" class="letters-loading">
                            v
                        </span>
                        <span data-text-preloader="e" class="letters-loading">
                            c
                        </span>
                        <span data-text-preloader="e" class="letters-loading">
                            a
                        </span>
                        <span data-text-preloader="e" class="letters-loading">
                            m
                        </span>
                    </div>
                </div>  
            </div>
        </div>
    </div> -->
    <!-- preloader end -->


    <!-- main header -->
    <Header />
    <!-- main-header end -->

    <!-- Mobile Menu  -->
    <div class="mobile-menu">
        <div class="menu-backdrop"></div>
        <div class="close-btn"><i class="fas fa-times"></i></div>
        
        <nav class="menu-box">
            <div class="nav-logo"><a href="#/"><img src="images/logo-2.png" alt="" title=""></a></div>
            <div class="menu-outer"><!--Here Menu Will Come Automatically Via Javascript / Same Menu as in Header--></div>
            <div class="contact-info">
                <h4>Contact Info</h4>
                <ul>
                    <li>Chicago 12, Melborne City, USA</li>
                    <li><a href="tel:+8801682648101">+88 01682648101</a></li>
                    <li><a href="mailto:info@example.com">info@example.com</a></li>
                </ul>
            </div>
            <div class="social-links">
                <ul class="clearfix">
                    <li><a href="#/"><span class="fab fa-twitter"></span></a></li>
                    <li><a href="#/"><span class="fab fa-facebook-square"></span></a></li>
                    <li><a href="#/"><span class="fab fa-pinterest-p"></span></a></li>
                    <li><a href="#/"><span class="fab fa-instagram"></span></a></li>
                    <li><a href="#/"><span class="fab fa-youtube"></span></a></li>
                </ul>
            </div>
        </nav>
    </div><!-- End Mobile Menu -->


    <!-- banner-section -->
    <section class="banner-section">
        <div class="banner-carousel owl-theme owl-carousel owl-dots-none">
            <div class="slide-item">
                <div class="image-layer" style="background-image:url(images/banner/banner-1.jpg)"></div>
                <div class="auto-container">
                    <div class="content-box">
                        <h3>Explore Our ConservaCam</h3>
                        <h2>New Wildlife Experience of Joy</h2>
                        <div class="btn-box">
                            <a href="#/" class="theme-btn btn-one">Purchase Now</a>
                        </div>
                    </div>  
                </div>
            </div>
            <div class="slide-item">
                <div class="image-layer" style="background-image:url(images/banner/banner-2.jpg)"></div>
                <div class="auto-container">
                    <div class="content-box">
                        <h3>Explore Our ConservaCam</h3>
                        <h2>New Wildlife Experience of Joy</h2>
                        <div class="btn-box">
                            <a href="#/" class="theme-btn btn-one">Purchase Now</a>
                        </div>
                    </div>  
                </div>
            </div>
            <div class="slide-item">
                <div class="image-layer" style="background-image:url(images/banner/banner-3.jpg)"></div>
                <div class="auto-container">
                    <div class="content-box">
                        <h3>Explore Our ConservaCam</h3>
                        <h2>New Wildlife Experience of Joy</h2>
                        <div class="btn-box">
                            <a href="#/" class="theme-btn btn-one">Purchase Now</a>
                        </div>
                    </div>  
                </div>
            </div>
            <div class="slide-item">
                <div class="image-layer" style="background-image:url(images/banner/banner-4.jpg)"></div>
                <div class="auto-container">
                    <div class="content-box">
                        <h3>Explore Our ConservaCam</h3>
                        <h2>New Wildlife Experience of Joy</h2>
                        <div class="btn-box">
                            <a href="#/" class="theme-btn btn-one">Purchase Now</a>
                        </div>
                    </div>  
                </div>
            </div>
        </div>
    </section>
    <!-- banner-section end -->


    <!-- info-section -->
    <section class="info-section">
        <div class="bg-layer"></div>
        <span class="rotate-text">What is ConservaCam?</span>
        <div class="auto-container">
            <div class="inner-container">
                <div class="row clearfix">
                    <div class="col-lg-4 col-md-6 col-sm-12 single-column">
                        <div class="single-item">
                            <div class="icon-box"><i class="flaticon-ticket"></i></div>
                            <h5><a href="#/">Buy Tickets</a></h5>
                            <p>Lorem ium dolor sit ameted pisicing elit sed do ut.</p>
                        </div>
                    </div>
                    <div class="col-lg-4 col-md-6 col-sm-12 single-column">
                        <div class="single-item">
                            <div class="icon-box"><i class="flaticon-calendar"></i></div>
                            <h5><a href="#/">new events</a></h5>
                            <p>Lorem ium dolor sit ameted pisicing elit sed do ut.</p>
                        </div>
                    </div>
                    <div class="col-lg-4 col-md-6 col-sm-12 single-column">
                        <div class="single-item">
                            <div class="icon-box"><i class="flaticon-map"></i></div>
                            <h5><a href="#/">zoo map</a></h5>
                            <p>Lorem ium dolor sit ameted pisicing elit sed do ut.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- info-section end -->


    <!-- about-section -->
    <section class="about-section sec-pad">
        <div class="auto-container">
            <div class="row clearfix">
                <div class="col-lg-6 col-md-12 col-sm-12 image-column">
                    <div class="image_block_one">
                        <div class="image-box">
                            <div class="shape" style="background-image: url(images/shape/shape-1.png);"></div>
                            <figure class="image"><img src="images/resource/about-1.jpg" alt=""></figure>
                            <div class="icon-box"><img src="images/icons/icon-1.png" alt=""></div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-6 col-md-12 col-sm-12 content-column">
                    <div class="content_block_one">
                        <div class="content-box">
                            <div class="sec-title">
                                <h2>Revolutionizing Wildlife Conservation with AI-Powered Insight</h2>
                            </div>
                            <div class="text">
                                <h4>Help us to protect wildlife around the world using ConservaCam.</h4>
                                <p>Monitor biodiversity effortlessly. Empower conservation decisions with real-time data.</p>
                                <ul class="list-style-one clearfix">
                                    <li>Lorem Ipsum is not simply random text</li>
                                    <li>If you are going to use a passage</li>
                                    <li>Making this the first true generator on the Internet</li>
                                </ul>
                            </div>
                            <div class="btn-box">
                                <a href="about.html" class="theme-btn btn-one">Purchase Now</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- about-section end -->


    <!-- chooseus-section -->
    <section class="chooseus-section sec-pad">
        <div class="img-wrap parallax-demo-1">
            <div class="parallax-inner back-img" style="background-image: url(images/background/chooseus-bg.jpg);"></div>
        </div>
        <div class="auto-container">
            <div class="row clearfix">
                <div class="col-lg-8 col-md-12 col-sm-12 inner-column">
                    <div class="inner-box">
                        <div class="sec-title">
                            <h2>Why should you chose ConservaCam?</h2>
                        </div>
                        <div class="row clearfix">
                            <div class="col-lg-6 col-md-6 col-sm-12 text-column">
                                <div class="text">
                                    <p>ConservaCam combines motion-sensing hardware and AI-driven software to
                                        capture, analyze, and transmit biodiversity data. Our system identifies individual
                                        animals, tracks behaviors, and provides actionable insights to support conservation
                                        efforts.
                                        </p>
                                    <figure class="signature"><img src="images/icons/signature-1.png" alt=""></figure>
                                </div>
                            </div>
                            <div class="col-lg-6 col-md-6 col-sm-12 text-column">
                                <ul class="list-style-one clearfix">
                                    <li>Making this first true generator</li>
                                    <li>Many desktop publish packages</li>
                                    <li>Lorem Ipsum is not simply</li>
                                    <li>If you are going to passage</li>
                                    <li>It has roots in a piece</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-12 col-sm-12 content-column">
                    <div class="content-box">
                        <div class="content-inner">
                            <div class="shape" style="background-image: url(images/shape/shape-2.png);"></div>
                            <figure class="image-layer  wow zoomIn animated" data-wow-delay="00ms" data-wow-duration="1500ms"><img src="images/resource/lion-1.png" alt=""></figure>
                            <h3>Family Membership</h3>
                            <h5>Yearly Package</h5>
                            <h2>$128.00</h2>
                            <a href="#/" class="theme-btn">buy now</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- chooseus-section end -->


    <!-- gallery-section -->
    <section class="gallery-section">
        <div class="auto-container">
            <div class="sec-title centred">
                <h2>amazing Animals <br />in our zoo</h2>
            </div>
        </div>
        <div class="outer-container">
            <div class="gallery-carousel owl-carousel owl-theme owl-dots-none owl-nav-none">
                <div class="gallery-block-one">
                    <div class="inner-box">
                        <figure class="image-box"><img src="images/gallery/gallery-1.jpg" alt=""></figure>
                        <div class="content-box">
                            <h3><a href="deer.html">deer</a></h3>
                        </div>
                        <div class="overlay-content">
                            <h3><a href="deer.html">deer</a></h3>
                            <p>There are many type of <br />variations pass not available</p>
                            <div class="link"><a href="deer.html"><i class="flaticon-right-arrow"></i></a></div>
                        </div>
                    </div>
                </div>
                <div class="gallery-block-one">
                    <div class="inner-box">
                        <figure class="image-box"><img src="images/gallery/gallery-2.jpg" alt=""></figure>
                        <div class="content-box">
                            <h3><a href="wolf.html">wolf</a></h3>
                        </div>
                        <div class="overlay-content">
                            <h3><a href="wolf.html">wolf</a></h3>
                            <p>There are many type of <br />variations pass not available</p>
                            <div class="link"><a href="wolf.html"><i class="flaticon-right-arrow"></i></a></div>
                        </div>
                    </div>
                </div>
                <div class="gallery-block-one">
                    <div class="inner-box">
                        <figure class="image-box"><img src="images/gallery/gallery-3.jpg" alt=""></figure>
                        <div class="content-box">
                            <h3><a href="elephant.html">elephant</a></h3>
                        </div>
                        <div class="overlay-content">
                            <h3><a href="elephant.html">elephant</a></h3>
                            <p>There are many type of <br />variations pass not available</p>
                            <div class="link"><a href="elephant.html"><i class="flaticon-right-arrow"></i></a></div>
                        </div>
                    </div>
                </div>
                <div class="gallery-block-one">
                    <div class="inner-box">
                        <figure class="image-box"><img src="images/gallery/gallery-4.jpg" alt=""></figure>
                        <div class="content-box">
                            <h3><a href="girrafe.html">girrafe</a></h3>
                        </div>
                        <div class="overlay-content">
                            <h3><a href="girrafe.html">girrafe</a></h3>
                            <p>There are many type of <br />variations pass not available</p>
                            <div class="link"><a href="girrafe.html"><i class="flaticon-right-arrow"></i></a></div>
                        </div>
                    </div>
                </div>
                <div class="gallery-block-one">
                    <div class="inner-box">
                        <figure class="image-box"><img src="images/gallery/gallery-5.jpg" alt=""></figure>
                        <div class="content-box">
                            <h3><a href="monkey.html">monkey</a></h3>
                        </div>
                        <div class="overlay-content">
                            <h3><a href="monkey.html">monkey</a></h3>
                            <p>There are many type of <br />variations pass not available</p>
                            <div class="link"><a href="monkey.html"><i class="flaticon-right-arrow"></i></a></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- gallery-section end -->


    <!-- clients-section -->
    <section class="clients-section">
        <div class="img-wrap parallax-demo-1">
            <div class="parallax-inner back-img" style="background-image: url(images/background/clients-bg.jpg);"></div>
        </div>
        <div class="auto-container">
            <div class="five-item-carousel owl-carousel owl-theme owl-nav-none owl-dots-none">
                <figure class="clients-logo"><a href="#/"><img src="images/clients/clients-1.png" alt=""></a></figure>
                <figure class="clients-logo"><a href="#/"><img src="images/clients/clients-2.png" alt=""></a></figure>
                <figure class="clients-logo"><a href="#/"><img src="images/clients/clients-3.png" alt=""></a></figure>
                <figure class="clients-logo"><a href="#/"><img src="images/clients/clients-4.png" alt=""></a></figure>
                <figure class="clients-logo"><a href="#/"><img src="images/clients/clients-5.png" alt=""></a></figure>
            </div>
        </div>
    </section>
    <!-- clients-section end -->


    <!-- adventure-section -->
    <section class="adventure-section">
        <div class="auto-container">
            <div class="row clearfix">
                <div class="col-lg-6 col-md-12 col-sm-12 content-column">
                    <div class="content_block_two">
                        <div class="content-box">
                            <div class="sec-title">
                                <h2>Your adventure begins here</h2>
                            </div>
                            <div class="inner-box">
                                <div class="single-item">
                                    <div class="icon-box"><i class="flaticon-tick"></i></div>
                                    <h4>night at the zoo</h4>
                                    <p>Lorem Ipsum nibh vel velit auctor aliqu. Aenean sollic tudin, lorem is simply man made many people recover them free text quis bibendum.</p>
                                </div>
                                <div class="single-item">
                                    <div class="icon-box"><i class="flaticon-tick"></i></div>
                                    <h4>support wild animals</h4>
                                    <p>Lorem Ipsum nibh vel velit auctor aliqu. Aenean sollic tudin, lorem is simply man made many people recover them free text quis bibendum.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-6 col-md-12 col-sm-12 image-column">
                    <div class="image_block_two">
                        <div class="image-box">
                            <div class="video-btn">
                                <a href="https://www.youtube.com/watch?v=nfP5N9Yc72A&amp;t=28s" class="lightbox-image" data-caption=""><i class="fas fa-play"></i></a>
                            </div>
                            <figure class="image"><img src="images/resource/adventure-1.jpg" alt=""></figure>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- adventure-section end -->


    <!-- testimonial-section -->
    <section class="testimonial-section centred sec-pad">
        <div class="auto-container">
            <div class="sec-title centred">
                <h2>What they’re <br />saying?</h2>
            </div>
            <div class="three-item-carousel owl-carousel owl-theme owl-dots-none owl-nav-none">
                <div class="testimonil-block-one">
                    <div class="inner-box">
                        <div class="author-thumb">
                            <figure class="thumb-box"><img src="images/resource/testimonial-1.jpg" alt=""></figure>
                            <div class="quote"><i class="flaticon-quote"></i></div>
                        </div>
                        <div class="text">
                            <p>I was impresed by the company services, lorem is simply free text used by copytyping no refreshing.  Neque porro est qui dolorem</p>
                        </div>
                        <div class="author-info">
                            <h5>Christine Rose</h5>
                            <span class="designation">Customer</span>
                        </div>
                    </div>
                </div>
                <div class="testimonil-block-one">
                    <div class="inner-box">
                        <div class="author-thumb">
                            <figure class="thumb-box"><img src="images/resource/testimonial-2.jpg" alt=""></figure>
                            <div class="quote"><i class="flaticon-quote"></i></div>
                        </div>
                        <div class="text">
                            <p>I was impresed by the company services, lorem is simply free text used by copytyping no refreshing.  Neque porro est qui dolorem</p>
                        </div>
                        <div class="author-info">
                            <h5>Mike hardson</h5>
                            <span class="designation">Customer</span>
                        </div>
                    </div>
                </div>
                <div class="testimonil-block-one">
                    <div class="inner-box">
                        <div class="author-thumb">
                            <figure class="thumb-box"><img src="images/resource/testimonial-3.jpg" alt=""></figure>
                            <div class="quote"><i class="flaticon-quote"></i></div>
                        </div>
                        <div class="text">
                            <p>I was impresed by the company services, lorem is simply free text used by copytyping no refreshing.  Neque porro est qui dolorem</p>
                        </div>
                        <div class="author-info">
                            <h5>sarah albert</h5>
                            <span class="designation">Customer</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- testimonial-section end -->


    <!-- events-section -->
    <section class="events-section sec-pad">
        <div class="bg-layer"></div>
        <div class="bg-image" style="background-image: url(images/background/events-bg.jpg);"></div>
        <div class="auto-container">
            <div class="row clearfix">
                <div class="col-lg-6 col-md-12 col-sm-12 title-column">
                    <div class="sec-title light">
                        <h2>Check zoo upcoming events</h2>
                        <a href="#/" class="theme-btn btn-one">view all</a>
                    </div>
                </div>
                <div class="col-lg-6 col-md-12 col-sm-12 inner-column">
                    <div class="inner-content">
                        <div class="events-block-one">
                            <div class="inner-box">
                                <div class="image-box">
                                    <figure class="image"><img src="images/resource/events-1.jpg" alt=""></figure>
                                    <div class="post-date"><h6>16<span>dec</span></h6></div>
                                </div>
                                <div class="inner">
                                    <ul class="info clearfix">
                                        <li><i class="far fa-clock"></i>2:00 am</li>
                                        <li><i class="far fa-map"></i>60 broklyn street</li>
                                    </ul>
                                    <h3><a href="#/">zebra and girrafe on the street</a></h3>
                                    <p>Suspendisse finibus urna mauris, lorem ipsum is simply free.</p>
                                </div>
                            </div>
                        </div>
                        <div class="events-block-one">
                            <div class="inner-box">
                                <div class="image-box">
                                    <figure class="image"><img src="images/resource/events-2.jpg" alt=""></figure>
                                    <div class="post-date"><h6>05<span>dec</span></h6></div>
                                </div>
                                <div class="inner">
                                    <ul class="info clearfix">
                                        <li><i class="far fa-clock"></i>2:00 am</li>
                                        <li><i class="far fa-map"></i>60 broklyn street</li>
                                    </ul>
                                    <h3><a href="#/">how Interaction with Animal can</a></h3>
                                    <p>Suspendisse finibus urna mauris, lorem ipsum is simply free.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- events-section end -->


    <!-- funfact-section -->
    <section class="funfact-section">
        <div class="img-wrap parallax-demo-1">
            <div class="parallax-inner back-img" style="background-image: url(images/background/funfact-bg.jpg);"></div>
        </div>
        <div class="auto-container">
            <div class="row clearfix">
                <div class="col-lg-3 col-md-6 col-sm-12 counter-block">
                    <div class="counter-block-one wow slideInUp animated" data-wow-delay="00ms" data-wow-duration="1500ms">
                        <div class="inner-box">
                            <div class="icon-box"><i class="flaticon-polar-bear"></i></div>
                            <div class="count-outer count-box">
                                <span class="count-text" data-speed="1500" data-stop="60">0</span><span>+</span>
                            </div>
                            <p>Wild Animals</p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 col-md-6 col-sm-12 counter-block">
                    <div class="counter-block-one wow slideInUp animated" data-wow-delay="00ms" data-wow-duration="1500ms">
                        <div class="inner-box">
                            <div class="icon-box"><i class="flaticon-whale"></i></div>
                            <div class="count-outer count-box">
                                <span class="count-text" data-speed="1500" data-stop="20">0</span><span>+</span>
                            </div>
                            <p>Aquatic Animals</p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 col-md-6 col-sm-12 counter-block">
                    <div class="counter-block-one wow slideInUp animated" data-wow-delay="00ms" data-wow-duration="1500ms">
                        <div class="inner-box">
                            <div class="icon-box"><i class="flaticon-bird"></i></div>
                            <div class="count-outer count-box">
                                <span class="count-text" data-speed="1500" data-stop="40">0</span><span>+</span>
                            </div>
                            <p>Beautiful Birds</p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 col-md-6 col-sm-12 counter-block">
                    <div class="counter-block-one wow slideInUp animated" data-wow-delay="00ms" data-wow-duration="1500ms">
                        <div class="inner-box">
                            <div class="icon-box"><i class="flaticon-smiling-emoticon-square-face"></i></div>
                            <div class="count-outer count-box">
                                <span class="count-text" data-speed="1500" data-stop="60">0</span><span>k</span>
                            </div>
                            <p>Happy Visitors</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- funfact-section end -->


    <!-- news-section -->
    <section class="news-section centred">
        <div class="auto-container">
            <div class="sec-title centred">
                <h2>Latest news & <br />Articles</h2>
            </div>
            <div class="row clearfix">
                <div class="col-lg-4 col-md-6 col-sm-12 news-block">
                    <div class="news-block-one wow fadeInUp animated" data-wow-delay="00ms" data-wow-duration="1500ms">
                        <div class="inner-box">
                            <div class="image-box">
                                <figure class="image"><a href="blog-details.html"><img src="images/news/news-1.jpg" alt=""></a></figure>
                                <div class="post-date"><h6>16<span>dec</span></h6></div>
                            </div>
                            <div class="lower-content">
                                <ul class="post-info clearfix">
                                    <li><i class="far fa-user-circle"></i><a href="blog-details.html">Admin</a></li>
                                    <li><i class="far fa-comments"></i><a href="blog-details.html">2 Comments</a></li>
                                </ul>
                                <h3><a href="blog-details.html">how Interaction with Animal can Release</a></h3>
                                <div class="link"><a href="blog-details.html"><i class="flaticon-right-arrow"></i></a></div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 col-sm-12 news-block">
                    <div class="news-block-one wow fadeInUp animated" data-wow-delay="00ms" data-wow-duration="1500ms">
                        <div class="inner-box">
                            <div class="image-box">
                                <figure class="image"><a href="blog-details.html"><img src="images/news/news-2.jpg" alt=""></a></figure>
                                <div class="post-date"><h6>15<span>dec</span></h6></div>
                            </div>
                            <div class="lower-content">
                                <ul class="post-info clearfix">
                                    <li><i class="far fa-user-circle"></i><a href="blog-details.html">Admin</a></li>
                                    <li><i class="far fa-comments"></i><a href="blog-details.html">3 Comments</a></li>
                                </ul>
                                <h3><a href="blog-details.html">Donec eget condimentum sapien</a></h3>
                                <div class="link"><a href="blog-details.html"><i class="flaticon-right-arrow"></i></a></div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 col-sm-12 news-block">
                    <div class="news-block-one wow fadeInUp animated" data-wow-delay="00ms" data-wow-duration="1500ms">
                        <div class="inner-box">
                            <div class="image-box">
                                <figure class="image"><a href="blog-details.html"><img src="images/news/news-3.jpg" alt=""></a></figure>
                                <div class="post-date"><h6>14<span>dec</span></h6></div>
                            </div>
                            <div class="lower-content">
                                <ul class="post-info clearfix">
                                    <li><i class="far fa-user-circle"></i><a href="blog-details.html">Admin</a></li>
                                    <li><i class="far fa-comments"></i><a href="blog-details.html">0 Comments</a></li>
                                </ul>
                                <h3><a href="blog-details.html">Etiam vel porttitor mi convallis</a></h3>
                                <div class="link"><a href="blog-details.html"><i class="flaticon-right-arrow"></i></a></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- news-section end -->


    <!-- cta-section -->
    <section class="cta-section">
        <div class="bg-layer"></div>
        <div class="auto-container">
            <div class="inner-box clearfix">
                <div class="pattern-layer" style="background-image: url(images/shape/shape-3.png);"></div>
                <figure class="image-layer"><img src="images/resource/animals-1.png" alt=""></figure>
                <div class="text pull-left">
                    <h2>The animals in <br />our parks</h2>
                </div>
                <div class="btn-box pull-right">
                    <a href="#/" class="theme-btn btn-one">Purchase Now</a>
                </div>
            </div>
        </div>
    </section>
    <!-- cta-section end -->


    <!-- main-footer -->
    <Footer />
    <!-- main-footer end -->



    <!-- scroll to top -->
    <button class="scroll-top scroll-to-target" data-target="html">
        <i class="fal fa-long-arrow-up"></i>
    </button>
</div>