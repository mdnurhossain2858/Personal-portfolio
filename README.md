<!DOCTYPE html>
  <html lang="en">
  <head>
    <title>Personal Portfolio - Bootstrap 5</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="css/font-awesome.min.css">
    <link rel="stylesheet" href="css/bootstrap.min.css">
  </head>
  <body class="bg-light">
    
    <!-- Navbar section start -->

    <nav class="navbar navbar-light bg-white fixed-top shadow-sm">
      <div class="container-lg">
        <a class="navbar-brand text-danger fw-bold fs-4" href="#">A.H</a>
        <div class="dropdown">
            <button class="btn btn-secondary btn-danger px-3" type="button" id="dropdownMenuButton" data-bs-toggle="dropdown" aria-expanded="false">
            <i class="fas fa-bars"></i>
            </button>
            <ul class="dropdown-menu dropdown-menu-end" aria-labelledby="dropdownMenuButton">
              <li>
                <a class="dropdown-item" href="#home">Home</a>
                <a class="dropdown-item" href="#about">About</a>
                <a class="dropdown-item" href="#services">Services</a>
                <a class="dropdown-item" href="#portfolio">Portfolio</a>
                <a class="dropdown-item" href="#testimonials">Testimonials</a>
                <a class="dropdown-item" href="#contact">Contact</a>
              </li>
            </ul>
          </div>
      </div>
    </nav>

    <!-- Navbar section end -->


    <!-- Home section start -->
      <section class="home py-5" id="home">
        <div class="container-lg">
          <div class="row min-vh-100 align-items-center align-content-center">
            <div class="col-md-6 mt-5 mt-md-0">
                <div class="home-img text-center">
                  <img src="img/profile.png" class="rounded-circle mw-100" alt="portfolio img">
                </div>
            </div>
            <div class="col-md-6 mt-5 mt-md-0 order-md-first">
              <div class="home-text">
                <p class="text-muted mb-1">Hello I'm</p>
                <h2 class="text-danger text-uppercase fs-1 fw-bold">Web Designer</h2>
                <h2 class="fs-4">Abid Hossain</h2>
                <p class="mt-4  text-muted">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                <a href="#portpolio" class="btn btn-danger px-3 mt-3">My work</a>
              </div>
            </div>
          </div>
        </div>
      </section>
    <!-- Home section end -->


    <!-- About section start -->
      <section class="about py-5" id="about">
        <div class="container-lg py-4">
          <div class="row justify-content-center">
            <div class="col-lg-8">
              <div class="section-title text-center">
                <h2 class="fw-bold mb-5">About Me</h2>
              </div>
            </div>
          </div>
        <div class="row">
          <div class="col-md-6">
            <div class="about-text">
              <h3 class="fs-4 mb-3">Lorem ipsum dolor sit amet, consectetur adipiscing elit</h3>
              <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            </div>
            <div class="row text-center text-uppercase">
              <div class="col-sm-4">
                <div class="fact-item">
                  <h4 class="fs-1 fw-bold">100</h4>
                  <p class="text-muted">Projects Completed</p>
                </div>
              </div>
              <div class="col-sm-4">
                <div class="fact-item">
                  <h4 class="fs-1 fw-bold">90</h4>
                  <p class="text-muted">Happy Clients</p>
                </div>
              </div>
              <div class="col-sm-4">
                <div class="fact-item">
                  <h4 class="fs-1 fw-bold">95</h4>
                  <p class="text-muted">Positive Reviews</p>
                </div>
              </div>
            </div>
            <div class="row">
              <div class="col-lg-12 d-flex align-items-center">
                <a href="#" class="btn px-3 btn-danger me-5">Download CV</a>
                <div class="social-links">
                  <a href="#" class="text-dark me-2"><i class="fab fa-facebook-f"></i></a>
                  <a href="#" class="text-dark me-2"><i class="fab fa-twitter"></i></a>
                  <a href="#" class="text-dark me-2"><i class="fab fa-instagram"></i></a>
                  <a href="#" class="text-dark me-2"><i class="fab fa-linkedin-in"></i></a>
                  <a href="#" class="text-dark me-2"><i class="fab fa-youtube"></i></a>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-6 mt-5  mt-md-0">
            <div class="skill-item mb-4">
              <h3 class="fs-6">Html</h3>
              <div class="progress" style="height: 5px;">
                <div class="progress-bar bg-danger" role="progressbar" style="width: 25%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
              </div>
            </div>
            <div class="skill-item mb-4">
              <h3 class="fs-6">Css</h3>
              <div class="progress" style="height: 5px;">
                <div class="progress-bar bg-danger" role="progressbar" style="width: 50%;" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100"></div>
              </div>
            </div>
            <div class="skill-item mb-4">
              <h3 class="fs-6">Javascript</h3>
              <div class="progress" style="height: 5px;">
                <div class="progress-bar bg-danger" role="progressbar" style="width: 75%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
              </div>
            </div>
            <div class="skill-item mb-4">
              <h3 class="fs-6">Bootstrap</h3>
              <div class="progress" style="height: 5px;">
                <div class="progress-bar bg-danger" role="progressbar" style="width: 100%;" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100"></div>
              </div>
            </div>
          </div>
        </div>
      </section>
    <!-- About section end -->
    <!-- service section start -->
    <section class="services py-5" id="services">
      <div class="container-lg py-4">
        <div class="row justify-content-center">
          <div class="col-lg-8">
            <div class="section-title text-center">
              <h2 class="fw-bold mb-5">What I Do</h2>
            </div>
          </div>
        </div>
        <div class="row text-center">
          <div class="col-md-6 col-lg-4 mb-4">
            <div class="service-item shadow-sm p-4 rounded bg-white">
              <div class="icon my-3 text-danger fs-2">
                <i class="fas fa-code"></i>
              </div>
              <h3 class="fs-5 py-2">Web Development</h3>
              <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipiscing elit</p>
            </div>
          </div>
          <div class="col-md-6 col-lg-4 mb-4">
            <div class="service-item shadow-sm p-4 rounded bg-white">
              <div class="icon my-3 text-danger fs-2">
                <i class="fas fa-lightbulb"></i>
              </div>
              <h3 class="fs-5 py-2">Creative Design</h3>
              <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipiscing elit</p>
            </div>
          </div>
          <div class="col-md-6 col-lg-4 mb-4">
            <div class="service-item shadow-sm p-4 rounded bg-white">
              <div class="icon my-3 text-danger fs-2">
                <i class="fas fa-image"></i>
              </div>
              <h3 class="fs-5 py-2">Photoshop</h3>
              <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipiscing elit</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- service section end -->
    <!-- portfolio section start -->
    <section class="portfolio py-5" id="portfolio">
      <div class="container-lg py-4">
        <div class="row justify-content-center">
          <div class="col-lg-8">
            <div class="section-title text-center">
              <h2 class="fw-bold mb-5">Latest Works</h2>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-md-6 col-lg-4">
            <div class="portfolio-item">
              <img src="img/portfolio/1.jpg" class="w-100 img-thumbnail" alt="portfolio item">
              <h3 class="text-capitalize fs-5 my-2">Team Section</h3>
              <p><a class="text-danger text-decoration-none" href="#">Live Demo</a></p>
            </div>
          </div>
          <div class="col-md-6 col-lg-4">
            <div class="portfolio-item">
              <img src="img/portfolio/2.jpg" class="w-100 img-thumbnail" alt="portfolio item">
              <h3 class="text-capitalize fs-5 my-2">App Landing Page</h3>
              <p><a class="text-danger text-decoration-none" href="#">Live Demo</a></p>
            </div>
          </div>
          <div class="col-md-6 col-lg-4">
            <div class="portfolio-item">
              <img src="img/portfolio/3.jpg" class="w-100 img-thumbnail" alt="portfolio item">
              <h3 class="text-capitalize fs-5 my-2">Creative Team Section</h3>
              <p><a class="text-danger text-decoration-none" href="#">Live Demo</a></p>
            </div>
          </div>
          <div class="col-md-6 col-lg-4">
            <div class="portfolio-item">
              <img src="img/portfolio/4.jpg" class="w-100 img-thumbnail" alt="portfolio item">
              <h3 class="text-capitalize fs-5 my-2">Toggle Pricing Table</h3>
              <p><a class="text-danger text-decoration-none" href="#">Live Demo</a></p>
            </div>
          </div>
          <div class="col-md-6 col-lg-4">
            <div class="portfolio-item">
              <img src="img/portfolio/5.jpg" class="w-100 img-thumbnail" alt="portfolio item">
              <h3 class="text-capitalize fs-5 my-2">Bootstrap 5 Image Gallery</h3>
              <p><a class="text-danger text-decoration-none" href="#">Live Demo</a></p>
            </div>
          </div>
          <div class="col-md-6 col-lg-4">
            <div class="portfolio-item">
              <img src="img/portfolio/6.jpg" class="w-100 img-thumbnail" alt="portfolio item">
              <h3 class="text-capitalize fs-5 my-2">Filterable Image Gallery</h3>
              <p><a class="text-danger text-decoration-none" href="#">Live Demo</a></p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- portfolio section end -->
    <!-- freelancer available section start -->
    <section class="freelancer-available py-5 bg-danger">
      <div class="container-lg">
        <div class="row justify-content-center">
          <div class="col-lg-8 text-center">
            <p class="text-light fs-5">Do you have any project ?</p>
            <h2 class="text-white fs-1">I'm Available For Freelancer Projects</h2>
            <a href="#contact" class="btn btn-outline-light">Hire Me</a>
          </div>
        </div>
      </div>
    </section>
    <!-- freelancer available section end -->
    <!-- testimonials section end -->
    <div class="testimonials py-5" id="testimonials">
      <div class="container-lg py-4">
        <div class="row justify-content-center">
          <div class="col-lg-8">
            <div class="section-title text-center">
              <h2 class="fw-bold mb-5">Testimonials</h2>
            </div>
          </div>
        </div>
        <div class="row justify-content-center">
          <div class="col-lg-8 col-xl-7">
            <div id="carousel1" class="carousel slide" data-bs-ride="carousel">
              <ol class="carousel-indicators">
                <li data-bs-target="#carousel1" data-bs-slide-to="0" class="active bg-danger"></li>
                <li class="bg-danger" data-bs-target="#carousel1" data-bs-slide-to="1"></li>
                <li class="bg-danger" data-bs-target="#carousel1" data-bs-slide-to="2"></li>
              </ol>
            <div class="carousel-inner -1">
              <!-- testimonial item start -->
              <div class="testimonials-item carousel-item active bg-white shadow-sm rounded p-4 mb-5">
                <div class="testimonials-author-info d-flex align-items-center">
                  <img src="img/testimonial/1.jpg" class="img-thumbnail rounded-circle" alt="author img">
                  <div class="author ms-3">
                    <h3 class="fs-6 mb-1">Nur Hossain</h3>
                    <p class="text-muted m-0">SEO Manager</p>
                  </div>
                </div>
                  <p class="text-muted mt-3 ">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                  <div class="rating text-danger">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                  </div>
              </div>
              <!-- testimonial item end -->
              <!-- testimonial item start -->
              <div class="testimonials-item carousel-item bg-white shadow-sm rounded p-4 mb-5">
                <div class="testimonials-author-info d-flex align-items-center">
                  <img src="img/testimonial/2.jpg" class="img-thumbnail rounded-circle" alt="author img">
                  <div class="author ms-3">
                    <h3 class="fs-6 mb-1">Mehejabin Hossain</h3>
                    <p class="text-muted m-0">SEO Manager</p>
                  </div>
                </div>
                  <p class="text-muted mt-3 ">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                  <div class="rating text-danger">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                  </div>
              </div>
              <!-- testimonial item end -->
              <!-- testimonial item start -->
              <div class="testimonials-item carousel-item bg-white shadow-sm rounded p-4 mb-5">
                <div class="testimonials-author-info d-flex align-items-center">
                  <img src="img/testimonial/3.jpg" class="img-thumbnail rounded-circle" alt="author img">
                  <div class="author ms-3">
                    <h3 class="fs-6 mb-1">Jaed Ibn Hossain</h3>
                    <p class="text-muted m-0">Hacker Manager</p>
                  </div>
                </div>
                  <p class="text-muted mt-3 ">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                  <div class="rating text-danger">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                  </div>
              </div>
              <!-- testimonial item end -->
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- testimonials section end -->
    <!-- contact section start -->
    <section class="contact py-5" id="contact">
      <div class="container-lg py-4">
        <div class="row justify-content-center">
          <div class="col-lg-8">
            <div class="section-title text-center">
              <h2 class="fw-bold mb-5">Contact Me</h2>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-md-5">
            <div class="contact-item d-flex">
              <div class="icon fs-4 text-danger">
                <i class="fas fa-envelope"></i>
              </div>
              <div class="text ms-3">
                <h3 class="fs-5">Email</h3>
                <p class="text-muted">example@gmail.com</p>
              </div>
            </div>
            <div class="contact-item d-flex">
              <div class="icon fs-4 text-danger">
                <i class="fas fa-phone"></i>
              </div>
              <div class="text ms-3">
                <h3 class="fs-5">Phone</h3>
                <p class="text-muted">+91 9654 293 ***  </p>
              </div>
            </div>
            <div class="contact-item d-flex">
              <div class="icon fs-4 text-danger">
                <i class="fas fa-map-marker-alt"></i>
              </div>
              <div class="text ms-3">
                <h3 class="fs-5">Visit Office</h3>
                <p class="text-muted">101 Street, New Dhaka - 1000</p>
              </div>
            </div>
          </div>
          <div class="col-md-7">
            <div class="contact-form">
              <form>
                <div class="row">
                  <div class="col-lg-6 mb-4">
                    <input type="text" placeholder="Your Name" class="form-control form-control-lg fs-6 border-0 shadow-sm"> 
                  </div>
                  <div class="col-lg-6 mb-4">
                    <input type="email" placeholder="Your E-mail" class="form-control form-control-lg fs-6 border-0 shadow-sm"> 
                  </div>
                </div>
                <div class="row">
                  <div class="col-lg-12 mb-4">
                    <input type="text" placeholder="Subject" class="form-control form-control-lg fs-6 border-0 shadow-sm"> 
                  </div>
                  <div class="col-lg-12 mb-4">
                    <textarea rows="5" placeholder="Your Message" class="form-control form-control-lg fs-6 border-0 shadow-sm"></textarea>
                  </div>
                </div>
                <div class="row">
                  <div class="col-lg-12">
                    <button type="submit" class="btn btn-danger px-3">Send Message</button>
                  </div>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- contact section end -->
    <!-- footer section start -->
    <footer class="footer border-top py-4">
      <div class="container-lg">
        <div class="row">
          <div class="col-lg-12">
            <p class="m-0 text-center text-muted">&copy; All Reserved by Nur Hossain</p>
          </div>
        </div>
      </div>
    </footer>
    <!-- footer section end -->

    <script src="js/bootstrap.bundle.min.js"></script>
  </body>
</html>
