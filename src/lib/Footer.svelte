<script>
    let showMessage = false;

function handleSubmit(event) {
  event.preventDefault();
  showMessage = true;

  // Hide the notification after a few seconds
  setTimeout(() => {
    showMessage = false;
  }, 3000);
}
</script>

<style>
  .notification {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background-color: #28a745;
    color: white;
    padding: 15px 20px;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
    z-index: 9999;
    animation: fadeIn 0.3s ease-out, fadeOut 0.3s ease-out 2.7s forwards;
  }

  @keyframes fadeIn {
    from {
      opacity: 0;
      transform: translateY(20px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }

  @keyframes fadeOut {
    to {
      opacity: 0;
      transform: translateY(20px);
    }
  }
</style>


<section class="main-footer">
    <div class="footer-top">
        <div class="pattern-layer" style="background-image: url(images/shape/shape-4.png);"></div>
        <div class="auto-container">
            <div class="row clearfix">
                <div class="col-lg-4 col-md-6 col-sm-12 footer-column">
                    <div class="footer-widget logo-widget">
                        <figure class="footer-logo"><a href="#/"><img src="images/footer-logo.png" alt=""></a></figure>
                        <form on:submit={handleSubmit}>
                            <div class="mb-3">
                                <input type="text" class="form-control" placeholder="Your Name" required/>
                              </div>
                        </form>
                        {#if showMessage}
                        <div class="alert alert-success mt-3" role="alert">
                          Message Sent Successfully!
                        </div>
                      {/if}
                    </div>
                    <div class="mb-3">
                        <input type="email" class="form-control" placeholder="Enter Your Email" required />
                      </div>
                      <div class="mb-3">
                        <textarea class="form-control" placeholder="Write your message here" rows="5" required></textarea>
                      </div>
                      <button type="submit" class="btn btn-primary w-100">SEND MESSAGE</button>

                </div>
                <div class="col-lg-2 col-md-6 col-sm-12 footer-column">
                    <div class="footer-widget links-widget">
                        <div class="widget-title">
                            <h5>Links</h5>
                        </div>
                        <div class="widget-content">
                            <ul class="links-list clearfix">
                                <li><a href="#/">About Us</a></li>
                                <li><a href="#/">Book Tickets</a></li>
                                <li><a href="#/">Meet the Animals</a></li>
                                <li><a href="#/">Our Gallery</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 col-md-6 col-sm-12 footer-column">
                    <div class="footer-widget contact-widget">
                        <div class="widget-title">
                            <h5>Contact</h5>
                        </div>
                        <div class="widget-content">
                            <ul class="info clearfix">
                                <li><i class="flaticon-telephone"></i><a href="tel:6668880000">666 888 0000</a></li>
                                <li><i class="flaticon-email"></i><a href="mailto:needhelp@company.com">needhelp@company.com</a></li>
                                <li><i class="flaticon-pin"></i>66 broklyn golden street line new york</li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 col-md-6 col-sm-12 footer-column">
                    <div class="footer-widget gallery-widget">
                        <div class="widget-title">
                            <h5>Gallery</h5>
                        </div>
                        <div class="widget-content">
                            <ul class="image-list clearfix">
                                <li>
                                    <figure class="image">
                                        <img src="images/resource/footer-1.jpg" alt="">
                                        <a href="images/resource/footer-1.jpg" class="lightbox-image" data-fancybox="gallery"><i class="flaticon-plus-symbol"></i></a>
                                    </figure>
                                </li>
                                <li>
                                    <figure class="image">
                                        <img src="images/resource/footer-2.jpg" alt="">
                                        <a href="images/resource/footer-2.jpg" class="lightbox-image" data-fancybox="gallery"><i class="flaticon-plus-symbol"></i></a>
                                    </figure>
                                </li>
                                <li>
                                    <figure class="image">
                                        <img src="images/resource/footer-3.jpg" alt="">
                                        <a href="images/resource/footer-3.jpg" class="lightbox-image" data-fancybox="gallery"><i class="flaticon-plus-symbol"></i></a>
                                    </figure>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="footer-bottom centred">
        <div class="auto-container">
            <div class="copyright">
                <p>&copy; Copyright 2025 by <a href="#/">weldlfe.com</a></p>
            </div>
        </div>
    </div>
</section>