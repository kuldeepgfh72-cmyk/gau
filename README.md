# gau<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>gourav(Tinku Bhai) | Construction Cards & CITB Test Booking Desk</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>

    <header class="main-header">
        <div class="container header-flex">
            <div class="logo">
                <h1>gourav<span>(Tinku Bhai)</span></h1>
            </div>
            <nav class="nav-links">
                <a href="#services">Cards & Tests</a>
                <a href="#booking-form">Book Now</a>
                <a href="#faqs">FAQs</a>
                <a href="tel:+442033862000" class="btn-call"><i class="fa-solid fa-phone"></i> +44 (20) 3386 2000</a>
            </nav>
        </div>
    </header>

    <section class="hero-section">
        <div class="container hero-grid">
            <div class="hero-text">
                <span class="badge">10 Minute Fast Booking Service</span>
                <h2>Unlock Your Construction Career With CSCS Cards & CITB Tests</h2>
                <p>Get your CSCS Card in 7 Days, 1-Day Course Certificates within 24 Hours, and full premium revision material. Fast, trusted, and hassle-free processing.</p>
                <div class="hero-features">
                    <div class="feat-item"><i class="fa-solid fa-circle-check"></i> 75k+ Processed</div>
                    <div class="feat-item"><i class="fa-solid fa-circle-check"></i> 24/7 Support</div>
                    <div class="feat-item"><i class="fa-solid fa-circle-check"></i> Nationwide Venues</div>
                </div>
            </div>
            
            <div class="form-wrapper" id="booking-form">
                <h3>Secure Online Booking Desk</h3>
                <form action="#" method="POST" class="booking-form">
                    <div class="form-group">
                        <label>Select Required Service</label>
                        <select required>
                            <option value="">-- Choose Option --</option>
                            <option value="cscs">CITB Test & CSCS Card</option>
                            <option value="citb">CITB Touch Screen Test Only</option>
                            <option value="cpcs">CPCS / NPORS Courses</option>
                            <option value="nvq">NVQ Training Assessment</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label>Full Name</label>
                        <input type="text" placeholder="John Doe" required>
                    </div>
                    <div class="form-group">
                        <label>Phone Number</label>
                        <input type="tel" placeholder="+44 7123 456789" required>
                    </div>
                    <button type="submit" class="btn-submit">Apply Now <i class="fa-solid fa-arrow-right"></i></button>
                </form>
            </div>
        </div>
    </section>

    <section class="services-section" id="services">
        <div class="container">
            <div class="section-title">
                <h2>Choose Your Construction Booking Service</h2>
                <p>We provide instant test confirmations and seamless document compliance paths across the UK.</p>
            </div>
            <div class="services-grid">
                <div class="service-card">
                    <div class="card-icon"><i class="fa-solid fa-id-card"></i></div>
                    <h3>CSCS Cards</h3>
                    <p>Green Labourer, Gold Supervisor, Black Manager, and Red Trainee temporary or structural site pass procurement applications.</p>
                </div>
                <div class="service-card">
                    <div class="card-icon"><i class="fa-solid fa-laptop-code"></i></div>
                    <h3>CITB Test Booking</h3>
                    <p>Secure rapid scheduling at official local UK touch screen testing centers. Free dynamic text preparation material provided.</p>
                </div>
                <div class="service-card">
                    <div class="card-icon"><i class="fa-solid fa-helmet-safety"></i></div>
                    <h3>Health & Safety Courses</h3>
                    <p>Full classroom or structural remote online interactive courses including 1-day HSA, SMSTS, and critical SSSTS certification schemes.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="faq-section" id="faqs">
        <div class="container standard-width">
            <div class="section-title">
                <h2>Frequently Asked Questions</h2>
            </div>
            <div class="faq-accordion">
                <div class="faq-item">
                    <button class="faq-toggle">How can I book a CITB test in the UK? <i class="fa-solid fa-chevron-down"></i></button>
                    <div class="faq-content">
                        <p>You can quickly apply using our online application gateway above or contact our help desk via telephone line directly to lock down an immediate open date slot near you.</p>
                    </div>
                </div>
                <div class="faq-item">
                    <button class="faq-toggle">Which CITB test should I book? <i class="fa-solid fa-chevron-down"></i></button>
                    <div class="faq-content">
                        <p>General site workers and trades require the basic Operatives Test. If you hold a specialized supervisory or site managerial job status, you will require the specialized advanced tests.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer class="main-footer">
        <div class="container footer-flex">
            <p>&copy; 2026 <strong>gourav(Tinku Bhai)</strong>. All rights reserved.</p>
            <p>Support Email: <a href="mailto:support@constructionhelpdesks.com">support@constructionhelpdesks.com</a></p>
        </div>
    </footer>

    <script>
        const faqToggles = document.querySelectorAll('.faq-toggle');
        faqToggles.forEach(toggle => {
            toggle.addEventListener('click', () => {
                const item = toggle.parentElement;
                item.classList.toggle('active');
            });
        });
    </script>
</body>
</html>
