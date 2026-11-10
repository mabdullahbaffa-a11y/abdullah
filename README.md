<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Name | Web Developer Portfolio</title>

  <!-- Bootstrap 5 CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <!-- Bootstrap Icons -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css">
  <!-- Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
  <!-- AOS Animation -->
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
  <!-- Custom CSS -->
  <link rel="stylesheet" href="style.css">
</head>
<body data-bs-spy="scroll" data-bs-target="#mainNav" data-bs-offset="100" tabindex="0">

  <!-- ================= NAVBAR ================= -->
  <nav id="mainNav" class="navbar navbar-expand-lg fixed-top custom-navbar">
    <div class="container">
      <a class="navbar-brand" href="#home">My<span>Portfolio</span>.</a>
      <button class="navbar-toggler border-0 shadow-none" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu">
        <i class="bi bi-list fs-1 text-dark"></i>
      </button>
      <div class="collapse navbar-collapse" id="navMenu">
        <ul class="navbar-nav ms-auto gap-2">
          <li class="nav-item"><a class="nav-link active" href="#home">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
          <li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
          <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
          <li class="nav-item"><a class="nav-link" href="#journey">My Journey</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- ================= 1. HOME SECTION ================= -->
  <section id="home" class="home-section d-flex align-items-center">
    <div class="container text-center py-5" data-aos="fade-up">
      <span class="badge-custom mb-4 d-inline-block">Available for Freelance Work</span>
      <h1 class="hero-title mb-4">Hi, I am <span class="text-yellow">Muhammad Abdullah</span><br>Web Developer</h1>
      <p class="hero-desc mx-auto mb-5">I build modern, responsive, and user-friendly websites. I focus on clean code and great user experiences for businesses and individuals.</p>
      <div class="d-flex justify-content-center gap-4 mt-5">
        <a href="#projects" class="btn btn-yellow btn-lg px-5 py-3 rounded-pill fw-bold">View My Work <i class="bi bi-arrow-right ms-2"></i></a>
        <a href="#contact" class="btn btn-outline-dark btn-lg px-5 py-3 rounded-pill fw-bold">Contact Me</a>
      </div>
    </div>
  </section>

  <!-- ================= 2. ABOUT SECTION ================= -->
  <section id="about" class="about-section section-bg-grey">
    <div class="container">
      <div class="section-heading text-center" data-aos="fade-up">
        <h6 class="text-yellow fw-bold text-uppercase tracking-wide">Get To Know Me</h6>
        <h2 class="section-title">About <span class="text-yellow">Me</span></h2>
      </div>
      <div class="row align-items-center g-5 mt-4">
        <div class="col-lg-6 text-center" data-aos="fade-right">
          <div class="about-img-box p-3 bg-white rounded-5 shadow-sm">
            <img src="./img/abd.jfif" alt="Profile" class="img-fluid rounded-4">
          </div>
        </div>
        <div class="col-lg-6" data-aos="fade-left">
          <h3 class="mb-4 fw-bold fs-2">A dedicated Web Developer based in Pakistan.</h3>
          <p class="text-muted fs-5 mb-4">I am passionate about creating websites that not only look beautiful but also perform exceptionally well. I have learned and mastered various web technologies to bring ideas to life.</p>
          <p class="text-muted fs-5 mb-4">I believe in writing clean, maintainable code and delivering projects on time. Whether it's a simple landing page or a complex e-commerce store, I give my 100% to every project.</p>
          <div class="row mt-5 g-4">
            <div class="col-sm-6">
              <div class="info-box bg-white shadow-sm p-3 rounded-4 border-0">
                <i class="bi bi-person-fill text-yellow fs-4 me-2"></i> <strong>Name:</strong> Muhammad Abdullah
              </div>
            </div>
            <div class="col-sm-6">
              <div class="info-box bg-white shadow-sm p-3 rounded-4 border-0">
                <i class="bi bi-geo-alt-fill text-yellow fs-4 me-2"></i> <strong>Location:</strong> Pakistan
              </div>
            </div>
            <div class="col-sm-6">
              <div class="info-box bg-white shadow-sm p-3 rounded-4 border-0">
                <i class="bi bi-envelope-fill text-yellow fs-4 me-2"></i> <strong>Email:</strong> m.abdullahbaffa@gmail.com
              </div>
            </div>
            <div class="col-sm-6">
              <div class="info-box bg-white shadow-sm p-3 rounded-4 border-0">
                <i class="bi bi-briefcase-fill text-yellow fs-4 me-2"></i> <strong>Freelance:</strong> Available
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ================= 3. SKILLS SECTION ================= -->
  <section id="skills" class="skills-section">
    <div class="container">
      <div class="section-heading text-center" data-aos="fade-up">
        <h6 class="text-yellow fw-bold text-uppercase tracking-wide">My Expertise</h6>
        <h2 class="section-title">Technical <span class="text-yellow">Skills</span></h2>
      </div>
      <div class="row g-4 mt-5">
        <!-- Skill 1 -->
        <div class="col-6 col-md-3" data-aos="zoom-in" data-aos-delay="100">
          <div class="skill-card text-center bg-white p-4 shadow-sm rounded-4 h-100">
            <i class="bi bi-filetype-html skill-icon text-danger"></i>
            <h4 class="fw-bold mt-3 fs-5">HTML5</h4>
            <p class="text-muted small mb-0">Semantic Markup</p>
          </div>
        </div>
        <!-- Skill 2 -->
        <div class="col-6 col-md-3" data-aos="zoom-in" data-aos-delay="200">
          <div class="skill-card text-center bg-white p-4 shadow-sm rounded-4 h-100">
            <i class="bi bi-filetype-css skill-icon text-primary"></i>
            <h4 class="fw-bold mt-3 fs-5">CSS3</h4>
            <p class="text-muted small mb-0">Styling & Animations</p>
          </div>
        </div>
        <!-- Skill 3 -->
        <div class="col-6 col-md-3" data-aos="zoom-in" data-aos-delay="300">
          <div class="skill-card text-center bg-white p-4 shadow-sm rounded-4 h-100">
            <i class="bi bi-filetype-js skill-icon text-warning"></i>
            <h4 class="fw-bold mt-3 fs-5">JavaScript</h4>
            <p class="text-muted small mb-0">Interactive Logic</p>
          </div>
        </div>
        <!-- Skill 4 -->
        <div class="col-6 col-md-3" data-aos="zoom-in" data-aos-delay="400">
          <div class="skill-card text-center bg-white p-4 shadow-sm rounded-4 h-100">
            <i class="bi bi-bootstrap-fill skill-icon text-purple" style="color:#7952b3;"></i>
            <h4 class="fw-bold mt-3 fs-5">Bootstrap</h4>
            <p class="text-muted small mb-0">Responsive Design</p>
          </div>
        </div>
        <!-- Skill 5 -->
        <div class="col-6 col-md-3" data-aos="zoom-in" data-aos-delay="100">
          <div class="skill-card text-center bg-white p-4 shadow-sm rounded-4 h-100">
            <i class="bi bi-wordpress skill-icon text-info"></i>
            <h4 class="fw-bold mt-3 fs-5">WordPress</h4>
            <p class="text-muted small mb-0">CMS & Themes</p>
          </div>
        </div>
        <!-- Skill 6 -->
        <div class="col-6 col-md-3" data-aos="zoom-in" data-aos-delay="200">
          <div class="skill-card text-center bg-white p-4 shadow-sm rounded-4 h-100">
            <i class="bi bi-server skill-icon text-orange" style="color:#fb7a24;"></i>
            <h4 class="fw-bold mt-3 fs-5">XAMPP</h4>
            <p class="text-muted small mb-0">Local Server</p>
          </div>
        </div>
        <!-- Skill 7 -->
        <div class="col-6 col-md-3" data-aos="zoom-in" data-aos-delay="300">
          <div class="skill-card text-center bg-white p-4 shadow-sm rounded-4 h-100">
            <i class="bi bi-cart-check skill-icon text-success"></i>
            <h4 class="fw-bold mt-3 fs-5">E-Commerce</h4>
            <p class="text-muted small mb-0">Store Setup</p>
          </div>
        </div>
        <!-- Skill 8 -->
        <div class="col-6 col-md-3" data-aos="zoom-in" data-aos-delay="400">
          <div class="skill-card text-center bg-white p-4 shadow-sm rounded-4 h-100">
            <i class="bi bi-phone skill-icon text-dark"></i>
            <h4 class="fw-bold mt-3 fs-5">Responsive</h4>
            <p class="text-muted small mb-0">Mobile Friendly</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ================= 4. SERVICES SECTION ================= -->
  <section id="services" class="services-section section-bg-grey">
    <div class="container">
      <div class="section-heading text-center" data-aos="fade-up">
        <h6 class="text-yellow fw-bold text-uppercase tracking-wide">What I Do</h6>
        <h2 class="section-title">My <span class="text-yellow">Services</span></h2>
      </div>
      <div class="row g-4 mt-5">
        <div class="col-md-6 col-lg-4" data-aos="fade-up" data-aos-delay="100">
          <div class="service-card bg-white p-5 shadow-sm rounded-4 h-100 text-center">
            <div class="service-icon-wrap bg-light rounded-circle mx-auto mb-4 d-flex align-items-center justify-content-center" style="width:90px; height:90px;">
              <i class="bi bi-code-slash fs-1 text-yellow"></i>
            </div>
            <h4 class="fw-bold mb-3">Web Development</h4>
            <p class="text-muted">Custom websites built from scratch using HTML, CSS, JavaScript, and Bootstrap. Fully responsive and fast.</p>
          </div>
        </div>
        <div class="col-md-6 col-lg-4" data-aos="fade-up" data-aos-delay="200">
          <div class="service-card bg-white p-5 shadow-sm rounded-4 h-100 text-center">
            <div class="service-icon-wrap bg-light rounded-circle mx-auto mb-4 d-flex align-items-center justify-content-center" style="width:90px; height:90px;">
              <i class="bi bi-wordpress fs-1 text-yellow"></i>
            </div>
            <h4 class="fw-bold mb-3">WordPress Design</h4>
            <p class="text-muted">Professional WordPress websites with theme customization, plugin setup, and easy content management.</p>
          </div>
        </div>
        <div class="col-md-6 col-lg-4 mx-auto" data-aos="fade-up" data-aos-delay="300">
          <div class="service-card bg-white p-5 shadow-sm rounded-4 h-100 text-center">
            <div class="service-icon-wrap bg-light rounded-circle mx-auto mb-4 d-flex align-items-center justify-content-center" style="width:90px; height:90px;">
              <i class="bi bi-cart-check fs-1 text-yellow"></i>
            </div>
            <h4 class="fw-bold mb-3">E-Commerce Store</h4>
            <p class="text-muted">Complete online store setup with products, cart, checkout, and payment gateway integration.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ================= 5. PROJECTS SECTION ================= -->
  <section id="projects" class="projects-section">
    <div class="container">
      <div class="section-heading text-center" data-aos="fade-up">
        <h6 class="text-yellow fw-bold text-uppercase tracking-wide">My Recent Work</h6>
        <h2 class="section-title">Featured <span class="text-yellow">Projects</span></h2>
      </div>
      <div class="row g-4 mt-5">
        <!-- Project 1 -->
        <div class="col-md-6" data-aos="fade-up">
          <div class="project-card bg-white shadow-sm rounded-4 overflow-hidden h-100">
            <img src="./img/e-com.png" alt="Project 1" class="img-fluid w-100 project-img">
            <div class="p-4 p-md-5">
              <h4 class="fw-bold mb-2">E-Commerce Platform</h4>
              <p class="text-muted mb-4">A complete online store with product filtering, cart, and secure checkout.</p>
              <div class="d-flex gap-2 flex-wrap">
                <span class="badge bg-light text-dark border px-3 py-2 rounded-pill">HTML</span>
                <span class="badge bg-light text-dark border px-3 py-2 rounded-pill">CSS</span>
                <span class="badge bg-light text-dark border px-3 py-2 rounded-pill">JavaScript</span>
              </div>
            </div>
          </div>
        </div>
        <!-- Project 2 -->
        <div class="col-md-6" data-aos="fade-up" data-aos-delay="100">
          <div class="project-card bg-white shadow-sm rounded-4 overflow-hidden h-100">
            <img src="./img/business.webp" alt="Project 2" class="img-fluid w-100 project-img">
            <div class="p-4 p-md-5">
              <h4 class="fw-bold mb-2">Corporate Business Site</h4>
              <p class="text-muted mb-4">A clean and professional website for a business to showcase their services.</p>
              <div class="d-flex gap-2 flex-wrap">
                <span class="badge bg-light text-dark border px-3 py-2 rounded-pill">WordPress</span>
                <span class="badge bg-light text-dark border px-3 py-2 rounded-pill">Elementor</span>
              </div>
            </div>
          </div>
        </div>
        <!-- Project 3 -->
        <div class="col-md-6" data-aos="fade-up" data-aos-delay="200">
          <div class="project-card bg-white shadow-sm rounded-4 overflow-hidden h-100">
            <img src="./img/page1.png" alt="Project 3" class="img-fluid w-100 project-img">
            <div class="p-4 p-md-5">
              <h4 class="fw-bold mb-2">Online Store</h4>
              <p class="text-muted mb-4">A sleek and modern store for selling digital products and physical goods.</p>
              <div class="d-flex gap-2 flex-wrap">
                <span class="badge bg-light text-dark border px-3 py-2 rounded-pill">Bootstrap 5</span>
                <span class="badge bg-light text-dark border px-3 py-2 rounded-pill">XAMPP</span>
              </div>
            </div>
          </div>
        </div>
        <!-- Project 4 -->
        <div class="col-md-6" data-aos="fade-up" data-aos-delay="300">
          <div class="project-card bg-white shadow-sm rounded-4 overflow-hidden h-100">
            <img src="./img/port...f.png" alt="Project 4" class="img-fluid w-100 project-img">
            <div class="p-4 p-md-5">
              <h4 class="fw-bold mb-2">Portfolio Website</h4>
              <p class="text-muted mb-4">A personal portfolio built to showcase skills and projects with a modern UI.</p>
              <div class="d-flex gap-2 flex-wrap">
                <span class="badge bg-light text-dark border px-3 py-2 rounded-pill">JavaScript</span>
                <span class="badge bg-light text-dark border px-3 py-2 rounded-pill">CSS3</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

               <!-- ================= 6. JOURNEY SECTION ================= -->
  <section id="journey" class="journey-section section-bg-grey">
    <div class="container">
      <div class="section-heading text-center" data-aos="fade-up">
        <h6 class="text-yellow fw-bold text-uppercase tracking-wide">My Path</h6>
        <h2 class="section-title">My Learning <span class="text-yellow">Journey</span></h2>
        <p class="text-muted mt-3 mx-auto" style="max-width: 600px;">I am currently focused on building my skills, creating projects, and preparing to deliver high-quality work to future clients.</p>
      </div>
      
      <div class="row g-4 mt-5 justify-content-center">
        <!-- Card 1: The Beginning -->
        <div class="col-lg-4 col-md-6" data-aos="fade-up" data-aos-delay="100">
          <div class="journey-card bg-white p-4 p-xl-5 shadow-sm rounded-4 h-100 border-top border-4 border-warning">
            <div class="d-flex align-items-center mb-4">
              <div class="icon-box bg-light rounded-circle p-3 me-3 text-warning">
                <i class="bi bi-rocket-takeoff-fill fs-3"></i>
              </div>
              <div>
                <span class="badge bg-warning text-dark mb-1">May 2026</span>
                <h4 class="fw-bold mb-0 fs-5">The Beginning</h4>
              </div>
            </div>
            <p class="text-muted mb-0">This is where my journey started. I dived into the world of web development, learning the core foundations of how websites actually work behind the scenes.</p>
          </div>
        </div>

        <!-- Card 2: Learning & Practice -->
        <div class="col-lg-4 col-md-6" data-aos="fade-up" data-aos-delay="200">
          <div class="journey-card bg-white p-4 p-xl-5 shadow-sm rounded-4 h-100 border-top border-4 border-warning">
            <div class="d-flex align-items-center mb-4">
              <div class="icon-box bg-light rounded-circle p-3 me-3 text-warning">
                <i class="bi bi-code-square fs-3"></i>
              </div>
              <div>
                <span class="badge bg-warning text-dark mb-1">Current Phase</span>
                <h4 class="fw-bold mb-0 fs-5">Learning & Building</h4>
              </div>
            </div>
            <p class="text-muted mb-0">I am actively mastering HTML, CSS, JavaScript, and Bootstrap. I spend my days writing code, fixing bugs, and building real projects to sharpen my skills.</p>
          </div>
        </div>

        <!-- Card 3: The Goal -->
        <div class="col-lg-4 col-md-6" data-aos="fade-up" data-aos-delay="300">
          <div class="journey-card bg-white p-4 p-xl-5 shadow-sm rounded-4 h-100 border-top border-4 border-warning">
            <div class="d-flex align-items-center mb-4">
              <div class="icon-box bg-light rounded-circle p-3 me-3 text-warning">
                <i class="bi bi-bullseye fs-3"></i>
              </div>
              <div>
                <span class="badge bg-warning text-dark mb-1">Future Goal</span>
                <h4 class="fw-bold mb-0 fs-5">Helping Clients</h4>
              </div>
            </div>
            <p class="text-muted mb-0">My goal is to transition from a learner to a professional developer. I am preparing myself to take on real-world projects and help businesses grow online.</p>
          </div>
        </div>
      </div>
      
      <!-- A quote to add length and look good -->
      <div class="row mt-5 pt-4 justify-content-center" data-aos="fade-up" data-aos-delay="400">
        <div class="col-lg-8 text-center">
          <div class="p-4 p-md-5 bg-white rounded-4 shadow-sm border">
            <i class="bi bi-quote fs-1 text-warning"></i>
            <h3 class="fw-bold fst-italic mb-0 text-dark">"Every expert was once a beginner. I am building my foundation strong, one line of code at a time."</h3>
          </div>
        </div>
      </div>

    </div>
  </section>

  <!-- ================= 7. CONTACT SECTION ================= -->
  <section id="contact" class="contact-section">
    <div class="container">
      <div class="section-heading text-center" data-aos="fade-up">
        <h6 class="text-yellow fw-bold text-uppercase tracking-wide">Get In Touch</h6>
        <h2 class="section-title">Contact <span class="text-yellow">Me</span></h2>
      </div>
      <div class="row justify-content-center mt-5">
        <div class="col-lg-10">
          <div class="contact-wrap bg-white p-5 shadow-lg rounded-4" data-aos="zoom-in">
            <div class="row g-5">
              <div class="col-lg-5">
                <h3 class="fw-bold mb-4">Let's discuss your project</h3>
                <p class="text-muted mb-5">Feel free to reach out for any inquiries or collaborations. I am always open to new opportunities.</p>
                
                <div class="d-flex align-items-center mb-4">
                  <div class="bg-light rounded-circle p-3 me-3 text-yellow"><i class="bi bi-envelope-fill fs-4"></i></div>
                  <div>
                    <h6 class="mb-0 fw-bold">Email</h6>
                    <p class="text-muted mb-0">m.abdullahbaffa@gmail.com</p>
                  </div>
                </div>
                <div class="d-flex align-items-center mb-4">
                  <div class="bg-light rounded-circle p-3 me-3 text-yellow"><i class="bi bi-whatsapp fs-4"></i></div>
                  <div>
                    <h6 class="mb-0 fw-bold">WhatsApp</h6>
                    <p class="text-muted mb-0">+92 347 15 47 297</p>
                  </div>
                </div>
                <div class="d-flex align-items-center">
                  <div class="bg-light rounded-circle p-3 me-3 text-yellow"><i class="bi bi-geo-alt-fill fs-4"></i></div>
                  <div>
                    <h6 class="mb-0 fw-bold">Location</h6>
                    <p class="text-muted mb-0">Pakistan</p>
                  </div>
                </div>
              </div>
              <div class="col-lg-7">
                <form id="contactForm">
                  <div class="row g-4">
                    <div class="col-md-6">
                      <input type="text" class="form-control custom-input" placeholder="Your Name" required>
                    </div>
                    <div class="col-md-6">
                      <input type="email" class="form-control custom-input" placeholder="Your Email" required>
                    </div>
                    <div class="col-12">
                      <input type="text" class="form-control custom-input" placeholder="Subject" required>
                    </div>
                    <div class="col-12">
                      <textarea class="form-control custom-input" rows="4" placeholder="Your Message" required></textarea>
                    </div>
                    <div class="col-12">
                      <button type="submit" class="btn btn-yellow btn-lg px-5 py-3 rounded-pill fw-bold w-100">Send Message</button>
                    </div>
                  </div>
                  <div id="formAlert" class="mt-4"></div>
                </form>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ================= FOOTER ================= -->
  <footer class="footer py-5 bg-white border-top">
    <div class="container text-center">
      <a class="navbar-brand fs-3 fw-bold text-dark mb-3 d-inline-block" href="#home">My<span class="text-yellow">Portfolio</span>.</a>
      <p class="text-muted mb-4">Building digital experiences that matter.</p>
      <div class="d-flex justify-content-center gap-3 mb-4">
        <a href="#" class="btn btn-light rounded-circle shadow-sm p-3"><i class="bi bi-github fs-5 text-dark"></i></a>
        <a href="#" class="btn btn-light rounded-circle shadow-sm p-3"><i class="bi bi-linkedin fs-5 text-dark"></i></a>
        <a href="#" class="btn btn-light rounded-circle shadow-sm p-3"><i class="bi bi-whatsapp fs-5 text-dark"></i></a>
      </div>
      <p class="text-muted mb-0 small">&copy; <span id="year"></span> m.@bdullah . All rights reserved.</p>
    </div>
  </footer>

  <!-- Scripts -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script src="script.js"></script>
</body>
</html>
