<script lang="ts">
    import Header from '$lib/Header.svelte';
    import Footer from '$lib/Footer.svelte';



    
    let features = [
    {
      icon: "bi-palette",
      title: "Cutting-Edge Technology",
      description: "AI-powered animal identification ensures accurate and reliable insights.Edge processing reduces false triggers and minimizes bandwidth usage. Advanced motion detection combines PIR and microwave sensors for precision",
    },
    {
      icon: "bi-cloud-download",
      title: "Built for the Wild",
      description: "Durable, weather-resistant hardware designed to withstand extreme environments.Low power consumption ensures extended battery life, even in remote areas.Compact and unobtrusive design blends seamlessly into natural habitats,avoiding disturbance.",
    },
    {
      icon: "bi-geo-alt",
      title: "Actionable Insights in Real-Time",
      description: "Automated behavior tracking for comprehensive wildlife understanding.Intuitive dashboards provide conservancies with actionable data at a glance.Cloud integration ensures secure access to all data remotely.",
    },
    {
      icon: "bi-chat-dots",
      title: "Scalable and Customizable",
      description: "Configurable software and hardware options to meet specific conservancy needs. Suitable for deployment across diverse ecosystems, from savannahs to rainforests. ",
    },
    {
      icon: "bi-tools",
      title: "Aligned with Conservation Goals",
      description: "Supports the United Nations Sustainable Development Goal 15: Life on Land.  Provides critical data for research, policy-making, and conservation planning.",
    },
    {
      icon: "bi-camera",
      title: "Proven Success in the Field",
      description: "Successfully deployed in pilot projects, including Nyeri County, with measurable results. Trusted by conservationists and researchers for delivering accurate and impactful data.",
    },
  ];


  
</script>


<style>
   
  .ripple {
    position: relative;
    overflow: hidden;
    display: inline-block;
    cursor: pointer;
  }

  .ripple img {
    transition: transform 0.3s ease;
  }

  .ripple:hover img {
    transform: scale(1.05);
  }
  .feature-card {
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }
  .feature-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 6px 16px rgba(0, 0, 0, 0.2);
  }
  .feature-icon {
    font-size: 2rem;
    color: #6c63ff;
    margin-bottom: 15px;
  }
  .hardware-section {
    padding: 60px 0;
    background-color: #f8f9fa;
  }

  .hardware-image {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
  }

  .feature-list li {
    margin-bottom: 15px;
  }

  .cta-button {
    background-color: #6c63ff;
    color: #fff;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    transition: background-color 0.3s ease;
  }

  .cta-button:hover {
    background-color: #5b54e6;
  }
  .about-section {
    background-color: #f8f9fa; /* Light background color */
    padding: 60px 0; /* Padding for spacing */
  }

  .about-image {
    border-radius: 8px; /* Rounded corners for the image */
  }
  .conservacam-section {
    background: linear-gradient(90deg, #1d1d2b, #282846); /* Gradient background */
    color: white; /* Text color */
    padding: 60px 0; /* Spacing */
    text-align: center; /* Center align text */
  }

  .headline {
    font-size: 1.8rem; /* Adjust font size */
    margin-bottom: 20px; /* Add spacing below */
  }

  .cta-button {
    background-color: #ff5722; /* CTA button color */
    color: white;
    border: none;
    padding: 10px 20px;
    font-size: 1.2rem;
    border-radius: 5px;
    transition: background-color 0.3s ease;
  }

  .cta-button:hover {
    background-color: #e64a19; /* Darker hover color */
  }
</style>

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
<br>
<br>
<br>
<br>

<!-- banner-section -->
<section class="banner-section">
    <div class="container-fluid bg-light min-vh-100 d-flex align-items-center pt-5">
        <div class="container">
          <div class="row align-items-center">
            <div class="col-md-6">
              <h2 class="display-5 fw-bold mb-3">Revolutionizing Wildlife Conservation with AI-Powered Insights </h2>
              <p class="lead text-muted mb-4">Monitor biodiversity effortlessly. Empower conservation decisions with real-time
                data.</p>
                <a href="#/" class="btn btn-primary btn-lg">Purchase Now</a>
             
            </div>
            <div class="col-md-6 text-center">
              <div class="ripple">
                <img src="images/gallery/gallery-8.jpg" alt="Digital Watch" class="img-fluid rounded">
              </div>
            </div>
          </div>
        </div>
      </div>
</section>
    <!-- banner-section end -->


    <!-- The Future of Wildlife Monitoring -->
    <section class="info-section">
        <div class="container section-padding">
            <div class="row align-items-center">
              <div class="col-md-6 text-center">
                <img src="images/gallery/gallery-8.jpg" alt="How HubSpot Works" class="img-fluid rounded"> <!-- Replace with actual image path -->
              </div>
              <div class="col-md-6">
                <h2 class="">The Future of Wildlife Monitoring</h2>
                <p class="text-muted mb-4">ConservaCam combines motion-sensing hardware and AI-driven software to
                    capture, analyze, and transmit biodiversity data. Our system identifies individual
                    animals, tracks behaviors, and provides actionable insights to support conservation
                    efforts.</p>
                    <div class="gap-3">
                    <a href="#/" class="btn btn-primary btn-lg me-5">Purchase Now</a>
                    <a href="#/" class="btn btn-outline-primary btn-lg">Purchase Now</a>
 
                    </div>
                   
                <div>
                </div>
              </div>
            </div>
          </div>
    </section>
    <!-- info-section end -->

    <!-- Why ConservaCam Is Best -->
    <section class="chooseus-section sec-pad">
        <div class="container my-5">
            <div class="text-center mb-4">
              <h2 class="fw-bold">Why ConservaCam Is Best</h2>
              <p class="text-muted">ConservaCam stands out as the ultimate solution for wildlife monitoring and conservation.Here's why:</p>
            </div>
            <div class="row g-4">
              {#each features as feature}
                <div class="col-md-4">
                  <div class="feature-card p-4 bg-white text-center">
                    <i class="bi { feature.icon } feature-icon"></i>
                    <h5 class="fw-bold">{ feature.title }</h5>
                    <p class="text-muted">{ feature.description }</p>
                  </div>
                </div>
              {/each}
            </div>
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
                                <br>
                                <a href="#/" class="btn btn-outline-primary btn-lg">See the Full Hardware Specs</a>

                            </div>
                            <div class="col-lg-6 col-md-6 col-sm-12 text-column">
                                <ul class="list-style-one clearfix">
                                    <li>Motion Sensors: PIR and microwave for precise detection.</li>
                                    <li>Camera Module: OpenMV microcontroller with 480p resolution.</li>
                                    <li>Wireless Communication: NRF24L01 for data transmission.</li>
                                    <li>Power Management: Sleep mode for extended battery life.</li>
                                    <li>High-quality 3D renders of hardware.</li>
                                    <li> Diagram showcasing modular components.             </li>
                                  
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
            <div class="row clearfix">
                <div class="col-lg-6 col-md-12 col-sm-12 image-column">
                    <div class="image_block_one">
                        <div class="image-box">
                            <div class="shape" style="background-image: url(images/shape/shape-1.png);"></div>
                            <figure class="image"><img src="images\resource\data-visualization.jpg" alt=""></figure>
                            <div class="icon-box"><img src="images/icons/icon-1.png" alt=""></div>
                        </div>
                        <br>
                        <span></span>
                        <br>
                        <div class="btn-box">
                            <a href="/about" class="theme-btn btn-one">Explore Software Capabilities</a>
                        </div>
                    </div>
                </div>
                <div class="col-lg-6 col-md-12 col-sm-12 content-column">
                    <div class="content_block_one">
                        <div class="content-box">
                            <div class="sec-title">
                                <h3>AI-Powered Insights at Your Fingertips</h3>
                            </div>
                            <div class="text">
                                <h4>Help us to protect wildlife around the world using ConservaCam.</h4>
                                <p>Monitor biodiversity effortlessly. Empower conservation decisions with real-time data.</p>
                                <ul class="list-style-one clearfix">
                                    <li>Animal Identification: AI trained on thousands of species</li>
                                    <li>Behavior Analysis: Real-time tracking and behavior patterns.</li>
                                    <li>Data Visualization: Intuitive dashboards</li>
                                </ul>
                                <marquee class="strong">Visuals</marquee>
                                <ul class="list-style-one clearfix">
                                    <li>Screenshot of software interface.</li>
                                    <li>Infographic showing the data flow from hardware to insights.</li>
                                </ul>
                              
                            </div>
                            
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- gallery-section end -->
    
  

    <!-- who we are -->
    <section class="testimonial-section centred sec-pad">
        <div class="about-section">
            <div class="container">
              <div class="row align-items-center">
                <div class="col-md-6">
                  <h2 class="fw-bold mb-3">Who We Are</h2>
                  <p class="text-muted">ConservaCam is an AI-driven solution built by a passionate team of engineers and
                    conservationists. We aim to enhance biodiversity monitoring with cutting-edge
                    technology, enabling conservancies to make data-driven decisions for wildlife
                    protection</p>
                </div>
                <div class="col-md-6 text-center">
                  <img
                    src="/images/resource/animals-6.jpg"
                    alt="About Us"
                    class="img-fluid about-image"
                  />
                </div>
              </div>
            </div>
          </div>
    </section>
    <!-- testimonial-section end -->
    <!-- Our Mission and Vision -->
    <section class="gallery-section">
        <div class="auto-container">
            <div class="row clearfix">
                <div class="col-lg-6 col-md-12 col-sm-12 image-column">
                    <div class="image_block_one">
                        <div class="image-box">
                            <div class="shape" style="background-image: url(images/shape/shape-1.png);"></div>
                            <figure class="image"><img src="images\news\news-5.jpg" alt=""></figure>
                            <div class="icon-box"><img src="images/icons/icon-1.png" alt=""></div>
                        </div>
                        <br>
                        <span></span>
                        <br>
                        <div class="btn-box">
                            <a href="/about" class="theme-btn btn-one btn-outline">Join Our Mission</a>
                        </div>
                    </div>
                </div>
                <div class="col-lg-6 col-md-12 col-sm-12 content-column">
                    <div class="content_block_one">
                        <div class="content-box">
                            <div class="sec-title">
                                <h2>Our Purpose and Aspirations</h2>
                            </div>
                            <div class="text">
                                <h4>To empower conservancies with advanced tools for monitoring, understanding, and
                                    protecting biodiversity.
                                </h4>
                                    <h2>Vision</h2>
                                    <h4>A world where technology harmonizes with nature to preserve ecosystems for future generations
                                    </h4>                              
                            </div>
                            
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <span></span>
    <br>
    <!-- Final Section -->
    <div class="conservacam-section">
        <div class="container">
          <h1 class="headline text-light">Be the eyes nature needs—equip your conservancy with ConservaCam and
            uncover the stories in the wild.
          </h1>
          <button class="cta-button">Get Started Now</button>
        </div>
      </div>

  

    <!-- main-footer -->
    <Footer />
    <!-- main-footer end -->



    <!-- scroll to top -->
    <button class="scroll-top scroll-to-target" data-target="html">
        <i class="fal fa-long-arrow-up"></i>
    </button>
</div>