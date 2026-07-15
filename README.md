<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WebCraft Academy</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.0/font/bootstrap-icons.css">
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>

    <div class="blob blob-1"></div>
    <div class="blob blob-2"></div>
    <div class="blob blob-3"></div>

    <!-- 01. NAVIGATION BAR -->
    <header>
        <nav class="navbar navbar-expand-md fixed-top">
            <div class="container">
                <a href="#" class="navbar-brand fw-bold">WebCraft Academy</a>
                
                <label for="menu-toggle" class="navbar-toggler d-md-none">
                    <i class="bi bi-list fs-2"></i>
                </label>
                <input type="checkbox" id="menu-toggle" class="d-none">
                
                <div class="collapse navbar-collapse d-none d-md-flex" id="navbarNav">
                    <ul class="navbar-nav ms-auto mb-2 mb-md-0">
                        <li class="nav-item"><a href="#home" class="nav-link active">Home</a></li>
                        <li class="nav-item"><a href="#about" class="nav-link">About</a></li>
                        <li class="nav-item"><a href="#roadmap" class="nav-link">Roadmap</a></li>
                        <li class="nav-item"><a href="#courses" class="nav-link">Courses</a></li>
                        <li class="nav-item"><a href="#faq" class="nav-link">FAQ</a></li>
                        <li class="nav-item"><a href="#signup" class="btn btn-outline-light ms-2">Sign Up</a></li>
                    </ul>
                </div>
            </div>
            
            <div class="mobile-drawer d-md-none">
                <ul class="nav flex-column">
                    <li class="nav-item"><a href="#home" class="nav-link">Home</a></li>
                    <li class="nav-item"><a href="#about" class="nav-link">About</a></li>
                    <li class="nav-item"><a href="#roadmap" class="nav-link">Roadmap</a></li>
                    <li class="nav-item"><a href="#courses" class="nav-link">Courses</a></li>
                    <li class="nav-item"><a href="#faq" class="nav-link">FAQ</a></li>
                    <li class="nav-item"><a href="#signup" class="nav-link">Sign Up</a></li>
                </ul>
            </div>
        </nav>
    </header>

    <main>
        <!-- 02. HERO SECTION -->
        <section class="hero" id="home">
            <div class="container">
                <div class="row align-items-center min-vh-100">
                    <div class="col-12 col-md-6 mb-4 mb-md-0">
                        <h1 class="display-3 fw-bold mb-4">Master Modern<br>Web Development</h1>
                        <p class="lead mb-4">Learn to build stunning, responsive websites from scratch.</p>
                        <a href="#courses" class="btn btn-primary btn-lg">Get Started</a>
                    </div>
                    <div class="col-12 col-md-6">
                        <div class="floating-image">
                            <img src="images/photo-1547658719-da2b51169166.avif" 
                                 alt="Web Development" class="img-fluid rounded-4">
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- 03. ABOUT SECTION -->
        <section class="about-section py-5" id="about">
            <div class="container py-5">
                <div class="row align-items-center">
                    <div class="col-12 col-md-6 mb-4 mb-md-0">
                        <h2 class="display-5 fw-bold mb-4">Why Choose WebCraft Academy?</h2>
                        <p class="lead mb-3">We provide comprehensive web development courses.</p>
                        <ul class="list-unstyled">
                            <li class="mb-3 d-flex align-items-center">
                                <i class="bi bi-check-circle-fill text-primary me-3 fs-4"></i>
                                <span>Expert instructors</span>
                            </li>
                            <li class="mb-3 d-flex align-items-center">
                                <i class="bi bi-check-circle-fill text-primary me-3 fs-4"></i>
                                <span>Hands-on projects</span>
                            </li>
                            <li class="mb-3 d-flex align-items-center">
                                <i class="bi bi-check-circle-fill text-primary me-3 fs-4"></i>
                                <span>Lifetime access</span>
                            </li>
                        </ul>
                    </div>
                    <div class="col-12 col-md-6">
                        <div class="row g-4">
                            <div class="col-12 col-md-6">
                                <article class="card h-100 border-0 shadow-sm">
                                    <div class="card-body text-center p-4">
                                        <i class="bi bi-laptop fs-1 text-primary mb-3 d-block"></i>
                                        <h5 class="card-title fw-bold">Practical Learning</h5>
                                        <p class="card-text">Learn by building real projects</p>
                                    </div>
                                </article>
                            </div>
                            <div class="col-12 col-md-6">
                                <article class="card h-100 border-0 shadow-sm">
                                    <div class="card-body text-center p-4">
                                        <i class="bi bi-people fs-1 text-primary mb-3 d-block"></i>
                                        <h5 class="card-title fw-bold">Community</h5>
                                        <p class="card-text">Join our supportive community</p>
                                    </div>
                                </article>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- 04. ROADMAP SECTION -->
        <section class="roadmap-section py-5" id="roadmap">
            <div class="container py-5">
                <h2 class="text-center display-5 fw-bold mb-5">Learning Roadmap</h2>
                <div class="row justify-content-center">
                    <div class="col-12 col-md-8">
                        <div class="timeline">
                            <div class="timeline-line"></div>
                            <article class="timeline-item mb-4">
                                <div class="row align-items-center">
                                    <div class="col-12 col-md-6 text-md-end mb-3 mb-md-0">
                                        <div class="timeline-badge badge-1 mx-auto mx-md-0">1</div>
                                    </div>
                                    <div class="col-12 col-md-6">
                                        <div class="timeline-card">
                                            <h4 class="fw-bold">HTML Basics</h4>
                                            <p>Learn the structure of web pages</p>
                                        </div>
                                    </div>
                                </div>
                            </article>
                            <article class="timeline-item mb-4">
                                <div class="row align-items-center">
                                    <div class="col-12 col-md-6 order-md-2 mb-3 mb-md-0">
                                        <div class="timeline-badge badge-2 mx-auto mx-md-0">2</div>
                                    </div>
                                    <div class="col-12 col-md-6 order-md-1">
                                        <div class="timeline-card">
                                            <h4 class="fw-bold">CSS Styling</h4>
                                            <p>Make your websites beautiful</p>
                                        </div>
                                    </div>
                                </div>
                            </article>
                            <article class="timeline-item mb-4">
                                <div class="row align-items-center">
                                    <div class="col-12 col-md-6 text-md-end mb-3 mb-md-0">
                                        <div class="timeline-badge badge-3 mx-auto mx-md-0">3</div>
                                    </div>
                                    <div class="col-12 col-md-6">
                                        <div class="timeline-card">
                                            <h4 class="fw-bold">JavaScript</h4>
                                            <p>Add interactivity</p>
                                        </div>
                                    </div>
                                </div>
                            </article>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- 05. COURSES SLIDER SECTION -->
        <section class="slider-section py-5" id="courses">
            <div class="container py-5">
                <h2 class="text-center display-5 fw-bold mb-5">Interactive Course Slider</h2>
                
                <div class="slider-wrapper-custom">
                    <button class="slider-btn-custom prev-btn" id="prevBtn">
                        <i class="bi bi-chevron-left"></i>
                    </button>
                    
                    <div class="slider-container-custom">
                        <div class="slider-track-custom" id="sliderTrack">
                            <article class="slide-card-custom">
                                <div class="card-image-custom">
                                    <img src="https://images.unsplash.com/photo-1461749280684-dccba630e2f6?auto=format&fit=crop&w=400&q=80" alt="HTML">
                                </div>
                                <h3>HTML</h3>
                                <p>Master semantic HTML and build accessible, structured web pages.</p>
                            </article>
                            <article class="slide-card-custom">
                                <div class="card-image-custom">
                                    <img src="https://images.unsplash.com/photo-1507721999472-8ed4421c4af2?auto=format&fit=crop&w=400&q=80" alt="CSS">
                                </div>
                                <h3>CSS</h3>
                                <p>Create beautiful, responsive designs with modern CSS techniques.</p>
                            </article>
                            <article class="slide-card-custom">
                                <div class="card-image-custom">
                                    <img src="https://images.unsplash.com/photo-1579468118864-1b9ea3c0db4a?auto=format&fit=crop&w=400&q=80" alt="JavaScript">
                                </div>
                                <h3>JavaScript</h3>
                                <p>Learn the fundamentals of JavaScript programming and DOM manipulation.</p>
                            </article>
                            <article class="slide-card-custom">
                                <div class="card-image-custom">
                                    <img src="https://images.unsplash.com/photo-1526379095098-d400fd0bf935?auto=format&fit=crop&w=400&q=80" alt="Python">
                                </div>
                                <h3>Python</h3>
                                <p>Data science, automation, and backend development fundamentals.</p>
                            </article>
                        </div>
                    </div>
                    
                    <button class="slider-btn-custom next-btn" id="nextBtn">
                        <i class="bi bi-chevron-right"></i>
                    </button>
                </div>
                
                <div class="slider-dots-custom" id="sliderDots">
                    <span class="dot-custom active"></span>
                    <span class="dot-custom"></span>
                    <span class="dot-custom"></span>
                </div>
            </div>
        </section>

        <!-- 06. SIGN UP FORM -->
        <section class="signup-section py-5" id="signup">
            <div class="container py-5">
                <div class="row justify-content-center">
                    <div class="col-12 col-md-8 col-lg-6">
                        <article class="card border-0 shadow-lg">
                            <div class="card-body p-5">
                                <h2 class="text-center display-6 fw-bold mb-4">Sign Up Now</h2>
                                <form id="signupForm">
                                    <div class="mb-3">
                                        <label for="fullName" class="form-label fw-bold">Full Name</label>
                                        <input type="text" class="form-control" id="fullName" required>
                                    </div>
                                    <div class="mb-3">
                                        <label for="email" class="form-label fw-bold">Email</label>
                                        <input type="email" class="form-control" id="email" required>
                                    </div>
                                    <div class="mb-3">
                                        <label for="course" class="form-label fw-bold">Select Course</label>
                                        <select class="form-select" id="course" required>
                                            <option value="">Choose...</option>
                                            <option value="html">HTML</option>
                                            <option value="css">CSS</option>
                                            <option value="js">JavaScript</option>
                                            <option value="python">Python</option>
                                        </select>
                                    </div>
                                    <div class="mb-3">
                                        <label for="password" class="form-label fw-bold">Password</label>
                                        <input type="password" class="form-control" id="password" required>
                                    </div>
                                    <div class="d-grid">
                                        <button type="submit" class="btn btn-primary btn-lg">Create Account</button>
                                    </div>
                                </form>
                            </div>
                        </article>
                    </div>
                </div>
            </div>
        </section>

        <!-- 07. FAQ SECTION -->
        <section class="faq-section py-5" id="faq">
            <div class="container py-5">
                <h2 class="text-center display-5 fw-bold mb-5">FAQ</h2>
                <div class="row justify-content-center">
                    <div class="col-12 col-md-8">
                        <div class="accordion" id="faqAccordion">
                            <article class="accordion-item mb-3 border-0 shadow-sm">
                                <h3 class="accordion-header">
                                    <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#faq1">
                                        Do I need prior experience?
                                    </button>
                                </h3>
                                <div id="faq1" class="accordion-collapse collapse show" data-bs-parent="#faqAccordion">
                                    <div class="accordion-body">No prior experience needed!</div>
                                </div>
                            </article>
                            <article class="accordion-item mb-3 border-0 shadow-sm">
                                <h3 class="accordion-header">
                                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#faq2">
                                        How long do I have access?
                                    </button>
                                </h3>
                                <div id="faq2" class="accordion-collapse collapse" data-bs-parent="#faqAccordion">
                                    <div class="accordion-body">Lifetime access to all materials.</div>
                                </div>
                            </article>
                            <article class="accordion-item mb-3 border-0 shadow-sm">
                                <h3 class="accordion-header">
                                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#faq3">
                                        Will I get a certificate?
                                    </button>
                                </h3>
                                <div id="faq3" class="accordion-collapse collapse" data-bs-parent="#faqAccordion">
                                    <div class="accordion-body">Yes, certificate of completion!</div>
                                </div>
                            </article>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- 08. FOOTER -->
    <footer class="footer py-5">
        <div class="container">
            <div class="row">
                <div class="col-12 col-md-4 mb-4 mb-md-0">
                    <h3 class="fw-bold mb-3">WebCraft Academy</h3>
                    <p>Building modern, responsive websites.</p>
                </div>
                <div class="col-12 col-md-4 mb-4 mb-md-0">
                    <h4 class="fw-bold mb-3">Quick Links</h4>
                    <ul class="list-unstyled">
                        <li class="mb-2"><a href="#home">Home</a></li>
                        <li class="mb-2"><a href="#about">About</a></li>
                        <li class="mb-2"><a href="#courses">Courses</a></li>
                        <li class="mb-2"><a href="#faq">FAQ</a></li>
                    </ul>
                </div>
                <div class="col-12 col-md-4">
                    <h4 class="fw-bold mb-3">Contact</h4>
                    <p><i class="bi bi-envelope me-2"></i> info@webcraft.academy</p>
                    <p><i class="bi bi-phone me-2"></i> +20 1277757288</p>
                    <div class="social-icons mt-3">
                        <a href="#" class="me-3"><i class="bi bi-whatsapp fs-4"></i></a>
                        <a href="#" class="me-3"><i class="bi bi-linkedin fs-4"></i></a>
                        <a href="#" class="me-3"><i class="bi bi-github fs-4"></i></a>
                        <a href="#"><i class="bi bi-facebook fs-4"></i></a>
                    </div>
                </div>
            </div>
            <div class="row mt-4 pt-4 border-top">
                <div class="col-12 text-center">
                    <p>&copy; 2026 All Rights Reserved</p>
                </div>
            </div>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>










    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html { scroll-behavior: smooth; }

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: #0a0e27;
    color: #ffffff;
    overflow-x: hidden;
    min-height: 100vh;
}

/* ============ BLOBS ============ */
.blob {
    position: fixed;
    border-radius: 50%;
    filter: blur(120px);
    opacity: 0.4;
    z-index: 0;
    pointer-events: none;
}

.blob-1 {
    width: 500px; height: 500px;
    background: radial-gradient(circle, #6a0dad, transparent);
    top: -100px; left: -100px;
}

.blob-2 {
    width: 400px; height: 400px;
    background: radial-gradient(circle, #00c896, transparent);
    top: 50%; right: -100px;
}

.blob-3 {
    width: 350px; height: 350px;
    background: radial-gradient(circle, #1a3a6b, transparent);
    bottom: -50px; left: 30%;
}

/* ============ NAVBAR ============ */
.navbar {
    background: rgba(10, 14, 39, 0.95) !important;
    backdrop-filter: blur(10px);
    padding: 15px 0;
    transition: all 0.3s ease;
}

.navbar-brand {
    color: #00d4ff !important;
    font-size: 1.8rem;
}

.nav-link {
    color: #b0b8d0 !important;
    transition: all 0.3s ease;
}

.nav-link:hover, .nav-link.active {
    color: #00d4ff !important;
}

.btn-outline-light {
    border-color: #00d4ff;
    color: #00d4ff;
}

.btn-outline-light:hover {
    background: #00d4ff;
    color: #0a0e27;
}

/* CSS-Only Mobile Drawer */
#menu-toggle:checked ~ .mobile-drawer {
    display: block !important;
}

.mobile-drawer {
    display: none;
    position: absolute;
    top: 100%;
    left: 0;
    width: 100%;
    background: rgba(10, 14, 39, 0.98);
    padding: 20px;
    z-index: 1000;
}

.mobile-drawer .nav-link {
    color: #b0b8d0 !important;
    padding: 12px 20px;
}

/* ============ HERO ============ */
.hero {
    position: relative;
    z-index: 1;
    padding-top: 100px;
}

.hero h1 {
    background: linear-gradient(135deg, #ffffff, #00d4ff);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
}

.floating-image {
    border-radius: 20px;
    overflow: hidden;
    box-shadow: 0 20px 60px rgba(0, 0, 0, 0.5);
    border: 2px solid rgba(0, 212, 255, 0.3);
    animation: float 6s ease-in-out infinite;
}

@keyframes float {
    0%, 100% { transform: translateY(0px); }
    50% { transform: translateY(-15px); }
}

/* ============ ABOUT ============ */
.about-section {
    position: relative;
    z-index: 1;
    background: rgba(20, 30, 80, 0.3);
    color: #ffffff;
}

.about-section h2, .about-section h5, .about-section .card-title {
    color: #ffffff;
}

.about-section p, .about-section .lead, .about-section .card-text, .about-section span {
    color: #ffffff;
}

.card {
    background: rgba(20, 30, 80, 0.6);
    border: 1px solid rgba(0, 212, 255, 0.2) !important;
    transition: all 0.3s ease;
}

.card:hover {
    transform: translateY(-10px);
    box-shadow: 0 15px 40px rgba(0, 212, 255, 0.2) !important;
}

/* ============ ROADMAP ============ */
.roadmap-section {
    position: relative;
    z-index: 1;
}

.timeline {
    position: relative;
    padding: 20px 0;
}

.timeline-line {
    position: absolute;
    left: 50%;
    top: 0;
    bottom: 0;
    width: 3px;
    background: linear-gradient(to bottom, #00d4ff, #0066ff, transparent);
    transform: translateX(-50%);
}

.timeline-badge {
    width: 50px;
    height: 50px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-weight: 700;
    font-size: 1.2rem;
    box-shadow: 0 0 20px rgba(0, 212, 255, 0.4);
}

.badge-1 { background: linear-gradient(135deg, #ff6b9d, #c44dff); color: #fff; }
.badge-2, .badge-3 { background: linear-gradient(135deg, #00d4ff, #0099cc); color: #0a0e27; }

.timeline-card {
    background: rgba(20, 30, 80, 0.6);
    border: 1px solid rgba(0, 212, 255, 0.2);
    border-radius: 12px;
    padding: 20px;
    text-align: center;
}

/* ============ SLIDER - جنب بعض ============ */
.slider-section {
    position: relative;
    z-index: 1;
    background: rgba(20, 30, 80, 0.3);
}

.slider-wrapper-custom {
    display: flex;
    align-items: center;
    gap: 20px;
    max-width: 1200px;
    margin: 0 auto;
}

.slider-container-custom {
    flex: 1;
    overflow: hidden;
    border-radius: 16px;
}

.slider-track-custom {
    display: flex;
    gap: 20px;
    transition: transform 0.5s ease;
}

.slide-card-custom {
    min-width: calc(33.333% - 14px);
    background: rgba(20, 30, 80, 0.8);
    border: 1px solid rgba(0, 212, 255, 0.3);
    border-radius: 16px;
    padding: 20px;
    flex-shrink: 0;
    transition: all 0.3s ease;
}

.slide-card-custom:hover {
    transform: translateY(-10px);
    box-shadow: 0 15px 40px rgba(0, 212, 255, 0.3);
    border-color: #00d4ff;
}

.card-image-custom {
    width: 100%;
    height: 180px;
    border-radius: 12px;
    overflow: hidden;
    margin-bottom: 15px;
}

.card-image-custom img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.3s ease;
}

.slide-card-custom:hover .card-image-custom img {
    transform: scale(1.1);
}

.slide-card-custom h3 {
    color: #00d4ff;
    font-size: 1.4rem;
    margin-bottom: 10px;
}

.slide-card-custom p {
    color: #b0b8d0;
    font-size: 0.95rem;
}

.slider-btn-custom {
    width: 50px;
    height: 50px;
    border-radius: 50%;
    border: 2px solid #00d4ff;
    background: rgba(20, 30, 80, 0.8);
    color: #00d4ff;
    font-size: 1.2rem;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: all 0.3s ease;
    flex-shrink: 0;
}

.slider-btn-custom:hover {
    background: #00d4ff;
    color: #0a0e27;
    transform: scale(1.1);
}

.slider-dots-custom {
    display: flex;
    justify-content: center;
    gap: 10px;
    margin-top: 30px;
}

.dot-custom {
    width: 12px;
    height: 12px;
    border-radius: 50%;
    background: rgba(255, 255, 255, 0.3);
    cursor: pointer;
    transition: all 0.3s ease;
}

.dot-custom.active {
    background: #00d4ff;
    width: 30px;
    border-radius: 6px;
}

/* ============ SIGN UP ============ */
.signup-section {
    position: relative;
    z-index: 1;
}

.form-control, .form-select {
    background: rgba(20, 30, 80, 0.6);
    border: 1px solid rgba(0, 212, 255, 0.2);
    color: #ffffff;
}

.form-control:focus, .form-select:focus {
    background: rgba(20, 30, 80, 0.8);
    border-color: #00d4ff;
    color: #ffffff;
    box-shadow: 0 0 15px rgba(0, 212, 255, 0.3);
}

.form-label { color: #b0b8d0; }

.btn-primary {
    background: linear-gradient(135deg, #00d4ff, #0099cc);
    border: none;
}

.btn-primary:hover {
    background: linear-gradient(135deg, #00e5ff, #00aadd);
    transform: translateY(-2px);
}

/* ============ FAQ ============ */
.faq-section {
    position: relative;
    z-index: 1;
    background: rgba(20, 30, 80, 0.3);
}

.accordion-item {
    background: rgba(20, 30, 80, 0.6);
    border: 1px solid rgba(0, 212, 255, 0.2) !important;
}

.accordion-button {
    background: rgba(20, 30, 80, 0.6);
    color: #ffffff;
}

.accordion-button:not(.collapsed) {
    background: rgba(0, 212, 255, 0.2);
    color: #00d4ff;
}

.accordion-body { color: #b0b8d0; }

/* ============ FOOTER ============ */
.footer {
    position: relative;
    z-index: 1;
    background: rgba(10, 14, 39, 0.95);
    border-top: 1px solid rgba(0, 212, 255, 0.2);
}

.footer h3, .footer h4 { color: #00d4ff; }

.footer a {
    color: #b0b8d0;
    text-decoration: none;
    transition: all 0.3s ease;
}

.footer a:hover {
    color: #00d4ff;
}

.social-icons a { color: #00d4ff; }

/* ============ RESPONSIVE ============ */
@media (max-width: 992px) {
    .slide-card-custom {
        min-width: calc(50% - 10px);
    }
}

@media (max-width: 768px) {
    .hero h1 { font-size: 2rem !important; }
    .display-3 { font-size: 2rem !important; }
    .display-5 { font-size: 1.75rem !important; }
    
    .slide-card-custom {
        min-width: 100%;
    }
    
    .timeline-line { left: 20px; }
    
    .mobile-drawer { display: none; }
    
    #menu-toggle:checked ~ .mobile-drawer {
        display: block !important;
    }
}

@media (min-width: 768px) {
    .mobile-drawer {
        display: none !important;
    }
}















// ============ CONSTANTS ============
const TODAY = new Date();
const MS_IN_A_DAY = 24 * 60 * 60 * 1000;

// ============ PARALLEL ARRAYS ============
const courseNames = ["HTML Basics", "CSS Styling", "JavaScript", "Python"];
const courseStatuses = ["Open Now", "Open Now", "Starting Soon", "Coming Soon"];
const courseLaunchDates = ["2026-01-15", "2026-01-20", "2026-02-01", "2026-02-15"];

// ============ daysLeft() ============
function daysLeft(isoDateString) {
    const launchDate = new Date(isoDateString);
    const difference = launchDate - TODAY;
    return Math.ceil(difference / MS_IN_A_DAY);
}

// ============ SLIDER ============
const sliderTrack = document.getElementById('sliderTrack');
const prevBtn = document.getElementById('prevBtn');
const nextBtn = document.getElementById('nextBtn');
const dots = document.querySelectorAll('.dot-custom');

let currentSlide = 0;
let slidesPerView = 3;
const totalSlides = 4;

function updateSlidesPerView() {
    if (window.innerWidth <= 768) slidesPerView = 1;
    else if (window.innerWidth <= 992) slidesPerView = 2;
    else slidesPerView = 3;
}

function getMaxSlide() {
    return Math.max(0, totalSlides - slidesPerView);
}

function updateSlider() {
    const slideWidth = sliderTrack.children[0].offsetWidth + 20;
    sliderTrack.style.transform = `translateX(-${currentSlide * slideWidth}px)`;
    
    dots.forEach((dot, index) => {
        dot.classList.remove('active');
        if (index === currentSlide) dot.classList.add('active');
    });
}

nextBtn.addEventListener('click', () => {
    currentSlide = currentSlide < getMaxSlide() ? currentSlide + 1 : 0;
    updateSlider();
});

prevBtn.addEventListener('click', () => {
    currentSlide = currentSlide > 0 ? currentSlide - 1 : getMaxSlide();
    updateSlider();
});

dots.forEach((dot, index) => {
    dot.addEventListener('click', () => {
        currentSlide = Math.min(index, getMaxSlide());
        updateSlider();
    });
});

// Auto Play
let autoPlay = setInterval(() => {
    currentSlide = currentSlide < getMaxSlide() ? currentSlide + 1 : 0;
    updateSlider();
}, 4000);

const sliderSection = document.querySelector('.slider-section');
sliderSection.addEventListener('mouseenter', () => clearInterval(autoPlay));
sliderSection.addEventListener('mouseleave', () => {
    autoPlay = setInterval(() => {
        currentSlide = currentSlide < getMaxSlide() ? currentSlide + 1 : 0;
        updateSlider();
    }, 4000);
});

window.addEventListener('resize', () => {
    updateSlidesPerView();
    if (currentSlide > getMaxSlide()) currentSlide = getMaxSlide();
    updateSlider();
});

updateSlidesPerView();
updateSlider();

// ============ FORM ============
const signupForm = document.getElementById('signupForm');
if (signupForm) {
    signupForm.addEventListener('submit', function(e) {
        e.preventDefault();
        console.log("Sign up:", {
            name: document.getElementById('fullName').value,
            email: document.getElementById('email').value,
            course: document.getElementById('course').value
        });
        alert("Account created!");
        signupForm.reset();
    });
}

// ============ NAVBAR SCROLL ============
window.addEventListener('scroll', () => {
    const navbar = document.querySelector('.navbar');
    if (window.pageYOffset > 100) {
        navbar.style.padding = '10px 0';
        navbar.style.boxShadow = '0 4px 30px rgba(0, 212, 255, 0.2)';
    } else {
        navbar.style.padding = '15px 0';
        navbar.style.boxShadow = 'none';
    }
});

// ============ CONSOLE OUTPUT ============
window.addEventListener('load', () => {
    console.log("=== Course Information ===");
    for (let i = 0; i < courseNames.length; i++) {
        console.log(`${courseNames[i]} - ${courseStatuses[i]} - ${daysLeft(courseLaunchDates[i])} days left`);
    }
});
    <script src="scripts/app.js"></script>
</body>
</html>
