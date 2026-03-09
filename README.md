
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - [Alfaris]</title>
    <!-- Bootstrap 5 CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css">
    <!-- Mengambil Font dari Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;700&family=Space+Mono:wght@400;700&display=swap" rel="stylesheet">
    <!-- Mengambil Icon Library (FontAwesome) -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

    <!-- Latar Belakang Animasi -->
    <canvas id="canvas-bg"></canvas>

    <!-- Navigasi -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
        <div class="container-fluid">
            <a class="navbar-brand fw-bold" href="#header">JamilAlfaris</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link active" href="#header">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
                    <li class="nav-item"><a class="nav-link" href="#portfolio">Portfolio</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Header / Hero -->
    <header id="header">
        <h1 class="animate-fade-in-down">JamilAlfaris</h1>
        <p class="tagline animate-fade-in-up">(&lt; Web Developer / IT Student /&gt;)</p>
        <a href="#about" class="scroll-down animate-bounce"><i class="fas fa-chevron-down"></i></a>
    </header>

    <!-- About Section -->
    <section id="about" class="section py-5">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-4 mb-4 mb-md-0 text-center">
                    <img src="image/my-photo.jpg" alt="Profile" class="img-fluid rounded-circle shadow-lg animate-slide-in-left" style="max-width: 300px;">
                </div>
                <div class="col-md-8">
                    <h2 class="display-5 fw-bold mb-4 animate-slide-in-right">Tentang Saya</h2>
                    <p class="lead mb-3 animate-fade-in-up" style="animation-delay: 0.2s;">Halo! Saya adalah seorang Web Developer yang bersemangat dalam menciptakan pengalaman digital yang interaktif dan menarik.</p>
                    <p class="mb-4 animate-fade-in-up" style="animation-delay: 0.3s;">Saya saat ini sedang menempuh pendidikan sebagai IT Student dan terus belajar teknologi terbaru untuk meningkatkan keterampilan saya dalam pengembangan Front-end dan Back-end.</p>
                    <a href="#contact" class="btn btn-primary btn-lg animate-fade-in-scale" style="animation-delay: 0.4s;"><i class="fas fa-envelope"></i> Hubungi Saya</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="section py-5">
        <div class="container">
            <h2 class="display-5 fw-bold mb-5 text-center animate-fade-in-down">Keahlian</h2>
            <div class="row g-4 animate-stagger">
                <!-- HTML5 -->
                <div class="col-md-6 col-lg-3">
                    <div class="skill-card">
                        <i class="fab fa-html5 skill-icon" style="color: #ff6b6b;"></i>
                        <span class="skill-badge">Expert</span>
                        <h5 class="skill-title">HTML5</h5>
                        <div class="skill-progress">
                            <div class="skill-progress-bar" style="--progress-width: 95%"></div>
                        </div>
                        <div class="skill-percentage">95%</div>
                    </div>
                </div>
                <!-- CSS3 -->
                <div class="col-md-6 col-lg-3">
                    <div class="skill-card">
                        <i class="fab fa-css3-alt skill-icon" style="color: #4ecdc4;"></i>
                        <span class="skill-badge">Advanced</span>
                        <h5 class="skill-title">CSS3</h5>
                        <div class="skill-progress">
                            <div class="skill-progress-bar" style="--progress-width: 90%"></div>
                        </div>
                        <div class="skill-percentage">90%</div>
                    </div>
                </div>
                <!-- JavaScript -->
                <div class="col-md-6 col-lg-3">
                    <div class="skill-card">
                        <i class="fab fa-js skill-icon" style="color: #ffd93d;"></i>
                        <span class="skill-badge">Advanced</span>
                        <h5 class="skill-title">JavaScript</h5>
                        <div class="skill-progress">
                            <div class="skill-progress-bar" style="--progress-width: 88%"></div>
                        </div>
                        <div class="skill-percentage">88%</div>
                    </div>
                </div>
                <!-- React JS -->
                <div class="col-md-6 col-lg-3">
                    <div class="skill-card">
                        <i class="fab fa-react skill-icon" style="color: #61dafb;"></i>
                        <span class="skill-badge">Intermediate</span>
                        <h5 class="skill-title">React JS</h5>
                        <div class="skill-progress">
                            <div class="skill-progress-bar" style="--progress-width: 80%"></div>
                        </div>
                        <div class="skill-percentage">80%</div>
                    </div>
                </div>
                <!-- Node.js -->
                <div class="col-md-6 col-lg-3">
                    <div class="skill-card">
                        <i class="fab fa-node skill-icon" style="color: #68a063;"></i>
                        <span class="skill-badge">Intermediate</span>
                        <h5 class="skill-title">Node.js</h5>
                        <div class="skill-progress">
                            <div class="skill-progress-bar" style="--progress-width: 75%"></div>
                        </div>
                        <div class="skill-percentage">75%</div>
                    </div>
                </div>
                <!-- SQL -->
                <div class="col-md-6 col-lg-3">
                    <div class="skill-card">
                        <i class="fas fa-database skill-icon" style="color: #0d47a1;"></i>
                        <span class="skill-badge">Advanced</span>
                        <h5 class="skill-title">SQL</h5>
                        <div class="skill-progress">
                            <div class="skill-progress-bar" style="--progress-width: 85%"></div>
                        </div>
                        <div class="skill-percentage">85%</div>
                    </div>
                </div>
                <!-- Git -->
                <div class="col-md-6 col-lg-3">
                    <div class="skill-card">
                        <i class="fab fa-git-alt skill-icon" style="color: #f34f29;"></i>
                        <span class="skill-badge">Intermediate</span>
                        <h5 class="skill-title">Git</h5>
                        <div class="skill-progress">
                            <div class="skill-progress-bar" style="--progress-width: 82%"></div>
                        </div>
                        <div class="skill-percentage">82%</div>
                    </div>
                </div>
                <!-- Figma -->
                <div class="col-md-6 col-lg-3">
                    <div class="skill-card">
                        <i class="fab fa-figma skill-icon" style="color: #a259ff;"></i>
                        <span class="skill-badge">Intermediate</span>
                        <h5 class="skill-title">Figma</h5>
                        <div class="skill-progress">
                            <div class="skill-progress-bar" style="--progress-width: 78%"></div>
                        </div>
                        <div class="skill-percentage">78%</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="section py-5">
        <div class="container">
            <h2 class="display-5 fw-bold mb-5 text-center animate-fade-in-down">Portofolio</h2>
            <div class="row g-4 animate-stagger">
                <!-- Project 1: E-Commerce -->
                <div class="col-md-6 col-lg-4">
                    <div class="project-card">
                        <img src="https://picsum.photos/seed/project1/400/300" alt="Proyek 1" class="project-img">
                        <div class="project-overlay">
                            <div class="project-category">
                                <span class="category-badge">Frontend</span>
                                <span class="category-badge">Full Stack</span>
                            </div>
                        </div>
                        <div class="card-content">
                            <h5>Website E-Commerce</h5>
                            <p>Platform toko online modern dengan fitur keranjang belanja, pembayaran gateway, dan admin panel untuk manajemen produk.</p>
                            <div class="project-stats">
                                <div class="stat-item">
                                    <i class="fas fa-code"></i>
                                    <span>HTML, CSS, JS</span>
                                </div>
                                <div class="stat-item">
                                    <i class="fas fa-calendar"></i>
                                    <span>2024</span>
                                </div>
                            </div>
                            <a href="#" class="project-btn">Lihat Detail <i class="fas fa-arrow-right ms-2"></i></a>
                        </div>
                    </div>
                </div>
                <!-- Project 2: Dashboard -->
                <div class="col-md-6 col-lg-4">
                    <div class="project-card">
                        <img src="https://picsum.photos/seed/project2/400/300" alt="Proyek 2" class="project-img">
                        <div class="project-overlay">
                            <div class="project-category">
                                <span class="category-badge">Dashboard</span>
                                <span class="category-badge">Data Viz</span>
                            </div>
                        </div>
                        <div class="card-content">
                            <h5>Dashboard Admin</h5>
                            <p>Dashboard analitik data yang interaktif dengan grafik real-time, statistik user, dan sistem manajemen konten yang powerful.</p>
                            <div class="project-stats">
                                <div class="stat-item">
                                    <i class="fas fa-code"></i>
                                    <span>React, Node.js</span>
                                </div>
                                <div class="stat-item">
                                    <i class="fas fa-calendar"></i>
                                    <span>2024</span>
                                </div>
                            </div>
                            <a href="#" class="project-btn">Lihat Detail <i class="fas fa-arrow-right ms-2"></i></a>
                        </div>
                    </div>
                </div>
                <!-- Project 3: Landing Page -->
                <div class="col-md-6 col-lg-4">
                    <div class="project-card">
                        <img src="https://picsum.photos/seed/project3/400/300" alt="Proyek 3" class="project-img">
                        <div class="project-overlay">
                            <div class="project-category">
                                <span class="category-badge">Landing Page</span>
                                <span class="category-badge">UI/UX</span>
                            </div>
                        </div>
                        <div class="card-content">
                            <h5>Landing Page Startup</h5>
                            <p>Halaman pendaratan yang responsif dan engaging untuk startup teknologi dengan animasi scroll smooth dan conversion optimization.</p>
                            <div class="project-stats">
                                <div class="stat-item">
                                    <i class="fas fa-code"></i>
                                    <span>HTML, CSS, JS</span>
                                </div>
                                <div class="stat-item">
                                    <i class="fas fa-calendar"></i>
                                    <span>2024</span>
                                </div>
                            </div>
                            <a href="#" class="project-btn">Lihat Detail <i class="fas fa-arrow-right ms-2"></i></a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section (Ditambahkan agar link Nav berfungsi) -->
    <section id="contact" class="section py-5">
        <div class="contact-content">
            <div class="container">
                <h2 class="display-5 fw-bold mb-4 text-white animate-fade-in-down">Hubungi Saya</h2>
                <p class="contact-description lead animate-fade-in-up">
                    Saya selalu terbuka untuk peluang baru, kolaborasi, dan pertanyaan menarik. Jangan ragu untuk menghubungi saya melalui platform sosial media atau email untuk diskusi lebih lanjut.
                </p>

                <!-- Social Links -->
                <div class="social-links animate-stagger" style="margin-top: 3rem;">
                    <div class="social-item">
                        <a href="https://github.com/Salamalfaa" class="social-btn" title="GitHub">
                            <i class="fab fa-github"></i>
                        </a>
                        <span class="contact-label">GitHub</span>
                    </div>
                    <div class="social-item">
                        <a href="https://www.linkedin.com/in/m-jamil-salam-alfaris-20a96031b/" class="social-btn" title="LinkedIn">
                            <i class="fab fa-linkedin-in"></i>
                        </a>
                        <span class="contact-label">LinkedIn</span>
                    </div>
                    <div class="social-item">
                        <a href="https://www.instagram.com/mjasaalfa/" class="social-btn" title="Instagram">
                            <i class="fab fa-instagram"></i>
                        </a>
                        <span class="contact-label">Instagram</span>
                    </div>
                    <div class="social-item">
                        <a href="mailto:example@email.com" class="social-btn" title="Email">
                            <i class="fas fa-envelope"></i>
                        </a>
                        <span class="contact-label">Email</span>
                    </div>
                </div>

                <!-- Contact Info Box -->
                <div class="contact-info-box animate-fade-in-scale" style="animation-delay: 0.5s;">
                    <h3>Informasi Kontak</h3>
                    <div class="contact-method">
                        <i class="fas fa-map-marker-alt"></i>
                        <span>Indonesia</span>
                    </div>
                    <div class="contact-method">
                        <i class="fas fa-envelope"></i>
                        <span>mjamilsalamalfaris@email.com</span>
                    </div>
                    <div class="contact-method">
                        <i class="fas fa-phone"></i>
                        <span>+62 XXX XXXX XXXX</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer id="footer" class="bg-secondary text-white text-center py-4">
        <p class="mb-0">&copy; 2026 mjamilsalamalfaris. Hak Cipta Dilindungi.</p>
    </footer>

     
    <script>
        // 1. Animasi Partikel Background (Canvas)
        const canvas = document.getElementById('canvas-bg');
        const ctx = canvas.getContext('2d');
        canvas.width = window.innerWidth;
        canvas.height = window.innerHeight;

        let particlesArray;

        // Kelas Partikel
        class Particle {
            constructor(x, y, directionX, directionY, size, color) {
                this.x = x;
                this.y = y;
                this.directionX = directionX;
                this.directionY = directionY;
                this.size = size;
                this.color = color;
            }
            // Gambar partikel
            draw() {
                ctx.beginPath();
                ctx.arc(this.x, this.y, this.size, 0, Math.PI * 2, false);
                ctx.fillStyle = this.color;
                ctx.fill();
            }
            // Update posisi partikel
            update() {
                if (this.x > canvas.width || this.x < 0) {
                    this.directionX = -this.directionX;
                }
                if (this.y > canvas.height || this.y < 0) {
                    this.directionY = -this.directionY;
                }
                this.x += this.directionX;
                this.y += this.directionY;
                this.draw();
            }
        }

        // Inisialisasi partikel
        function init() {
            particlesArray = [];
            let numberOfParticles = (canvas.height * canvas.width) / 9000; // Kepadatan partikel
            for (let i = 0; i < numberOfParticles; i++) {
                let size = (Math.random() * 2) + 1;
                let x = (Math.random() * ((innerWidth - size * 2) - (size * 2)) + size * 2);
                let y = (Math.random() * ((innerHeight - size * 2) - (size * 2)) + size * 2);
                let directionX = (Math.random() * 0.4) - 0.2;
                let directionY = (Math.random() * 0.4) - 0.2;
                let color = '#38bdf8';
                particlesArray.push(new Particle(x, y, directionX, directionY, size, color));
            }
        }

        // Animasi Loop
        function animate() {
            requestAnimationFrame(animate);
            ctx.clearRect(0, 0, innerWidth, innerHeight);
            for (let i = 0; i < particlesArray.length; i++) {
                particlesArray[i].update();
            }
            connect();
        }

        // Menghubungkan titik-titik dengan garis
        function connect() {
            let opacityValue = 1;
            for (let a = 0; a < particlesArray.length; a++) {
                for (let b = a; b < particlesArray.length; b++) {
                    let distance = ((particlesArray[a].x - particlesArray[b].x) * (particlesArray[a].x - particlesArray[b].x)) + 
                                   ((particlesArray[a].y - particlesArray[b].y) * (particlesArray[a].y - particlesArray[b].y));
                    if (distance < (canvas.width/7) * (canvas.height/7)) {
                        opacityValue = 1 - (distance / 20000);
                        ctx.strokeStyle = 'rgba(56, 189, 248,' + opacityValue + ')';
                        ctx.lineWidth = 1;
                        ctx.beginPath();
                        ctx.moveTo(particlesArray[a].x, particlesArray[a].y);
                        ctx.lineTo(particlesArray[b].x, particlesArray[b].y);
                        ctx.stroke();
                    }
                }
            }
        }

        // Handle Resize Window
        window.addEventListener('resize', function() {
            canvas.width = innerWidth;
            canvas.height = innerHeight;
            init();
        });

        // Jalankan animasi
        init();
        animate();

        // 2. Highlight Navigasi saat Scroll
        const sections = document.querySelectorAll('.section, header');
        const navLi = document.querySelectorAll('.navbar a');

        window.addEventListener('scroll', () => {
            let current = '';
            sections.forEach(section => {
                const sectionTop = section.offsetTop;
                const sectionHeight = section.clientHeight;
                if (pageYOffset >= (sectionTop - sectionHeight / 3)) {
                    current = section.getAttribute('id');
                }
            });

            navLi.forEach(a => {
                a.classList.remove('active');
                if (a.getAttribute('href').includes(current)) {
                    a.classList.add('active');
                }
            });
        });

        // 3. Scroll Reveal Animations - Luxury Entrance Effect
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    // Tambahkan animasi ke elemen yang terlihat
                    if (entry.target.classList.contains('animate-stagger')) {
                        entry.target.style.opacity = '1';
                    } else if (!entry.target.classList.contains('animate-fade-in-down') && 
                               !entry.target.classList.contains('animate-fade-in-up') &&
                               !entry.target.classList.contains('animate-slide-in-left') &&
                               !entry.target.classList.contains('animate-slide-in-right')) {
                        // Tambahkan fade in untuk elemen lain
                        entry.target.classList.add('animate-fade-in-up');
                    }
                    observer.unobserve(entry.target);
                }
            });
        }, observerOptions);

        // Observe semua section
        document.querySelectorAll('.section').forEach(section => {
            observer.observe(section);
        });

        // Observe elemen-elemen yang akan di-animate saat scroll
        document.querySelectorAll('.card').forEach(card => {
            observer.observe(card);
        });
    </script>

    <!-- Bootstrap 5 JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
