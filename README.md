<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Evergreen General Trading - Premium Interior Solutions UAE</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
        }

        /* NAVIGATION */
        nav {
            background: #0f2f24;
            padding: 1rem 2rem;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 2rem;
            flex-wrap: wrap;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
            padding: 0.5rem 1rem;
            border-radius: 5px;
        }

        nav a:hover {
            background: #25D366;
            color: white;
        }

        /* HEADER */
        header {
            background: #0f2f24;
            color: white;
            padding: 2rem;
            text-align: center;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }

        header p {
            font-size: 1.1rem;
            opacity: 0.9;
        }

        /* HERO */
        .hero {
            background: linear-gradient(rgba(15, 47, 36, 0.7), rgba(15, 47, 36, 0.7)),
                        url('https://images.unsplash.com/photo-1600585154340-be6161a56a0c?w=1200&h=500&fit=crop');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 6rem 2rem;
            text-align: center;
            min-height: 400px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }

        .hero h2 {
            font-size: 3rem;
            margin-bottom: 1rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }

        .hero p {
            font-size: 1.3rem;
            margin-bottom: 2rem;
            text-shadow: 1px 1px 3px rgba(0,0,0,0.5);
        }

        .hero-buttons {
            display: flex;
            gap: 1rem;
            justify-content: center;
            flex-wrap: wrap;
        }

        /* BUTTONS */
        .btn {
            display: inline-block;
            padding: 0.8rem 2rem;
            border-radius: 30px;
            text-decoration: none;
            color: white;
            font-weight: bold;
            transition: all 0.3s;
            border: 2px solid transparent;
            cursor: pointer;
        }

        .btn-call {
            background: #007bff;
        }

        .btn-call:hover {
            background: #0056b3;
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0, 123, 255, 0.4);
        }

        .btn-whatsapp {
            background: #25D366;
        }

        .btn-whatsapp:hover {
            background: #1da851;
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(37, 211, 102, 0.4);
        }

        /* SECTIONS */
        section {
            padding: 4rem 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        section h2 {
            font-size: 2.5rem;
            margin-bottom: 2rem;
            text-align: center;
            color: #0f2f24;
        }

        /* SERVICES GRID */
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }

        .service-card {
            background: white;
            padding: 2rem;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: all 0.3s;
            text-align: center;
            border-top: 4px solid #25D366;
        }

        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.15);
        }

        .service-card .icon {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        .service-card h3 {
            color: #0f2f24;
            margin-bottom: 0.5rem;
        }

        /* GALLERY */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
        }

        .gallery img {
            width: 100%;
            height: 250px;
            object-fit: cover;
            border-radius: 12px;
            transition: transform 0.3s;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }

        .gallery img:hover {
            transform: scale(1.05);
        }

        /* WHY CHOOSE US */
        .benefits {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            text-align: center;
        }

        .benefit-item {
            padding: 2rem;
            background: #f0f8f5;
            border-radius: 12px;
            border-left: 4px solid #25D366;
        }

        .benefit-item h3 {
            color: #0f2f24;
            margin-bottom: 0.5rem;
        }

        /* CTA SECTION */
        .cta {
            background: linear-gradient(135deg, #0f2f24 0%, #1a4a3a 100%);
            color: white;
            text-align: center;
            padding: 4rem 2rem;
            border-radius: 12px;
            margin: 4rem 0;
        }

        .cta h2 {
            color: white;
            margin-bottom: 1rem;
        }

        .cta p {
            font-size: 1.1rem;
            margin-bottom: 2rem;
        }

        /* CONTACT SECTION */
        .contact-container {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 3rem;
            align-items: start;
        }

        .contact-info {
            background: #f0f8f5;
            padding: 2rem;
            border-radius: 12px;
        }

        .contact-info h3 {
            color: #0f2f24;
            margin-bottom: 1.5rem;
        }

        .contact-info p {
            margin-bottom: 1rem;
            font-size: 1rem;
        }

        .contact-info strong {
            color: #0f2f24;
        }

        /* CONTACT FORM */
        .contact-form {
            background: white;
            padding: 2rem;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }

        .form-group {
            margin-bottom: 1.5rem;
        }

        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            color: #0f2f24;
            font-weight: 500;
        }

        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 0.8rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-family: inherit;
            font-size: 1rem;
            transition: border-color 0.3s;
        }

        .form-group input:focus,
        .form-group textarea:focus {
            outline: none;
            border-color: #25D366;
            box-shadow: 0 0 5px rgba(37, 211, 102, 0.3);
        }

        .form-group textarea {
            resize: vertical;
            min-height: 120px;
        }

        .form-group button {
            background: #25D366;
            color: white;
            padding: 0.8rem 2rem;
            border: none;
            border-radius: 5px;
            font-size: 1rem;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s;
            width: 100%;
        }

        .form-group button:hover {
            background: #1da851;
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(37, 211, 102, 0.4);
        }

        /* FOOTER */
        footer {
            background: #0f2f24;
            color: white;
            text-align: center;
            padding: 2rem;
            margin-top: 3rem;
        }

        footer p {
            margin: 0.5rem 0;
        }

        /* WHATSAPP FLOAT BUTTON */
        .whatsapp-float {
            position: fixed;
            bottom: 30px;
            right: 30px;
            background: #25D366;
            color: white;
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            text-decoration: none;
            font-size: 30px;
            box-shadow: 0 5px 20px rgba(37, 211, 102, 0.4);
            transition: all 0.3s;
            z-index: 50;
        }

        .whatsapp-float:hover {
            background: #1da851;
            transform: scale(1.1);
            box-shadow: 0 8px 25px rgba(37, 211, 102, 0.6);
        }

        /* RESPONSIVE */
        @media (max-width: 768px) {
            nav ul {
                gap: 1rem;
            }

            header h1 {
                font-size: 1.8rem;
            }

            .hero h2 {
                font-size: 1.8rem;
            }

            .hero p {
                font-size: 1rem;
            }

            .hero-buttons {
                flex-direction: column;
                align-items: center;
            }

            .btn {
                width: 200px;
            }

            section h2 {
                font-size: 1.8rem;
            }

            .contact-container {
                grid-template-columns: 1fr;
            }

            .whatsapp-float {
                bottom: 20px;
                right: 20px;
                width: 50px;
                height: 50px;
                font-size: 24px;
            }
        }
    </style>
</head>
<body>
    <!-- NAVIGATION -->
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#gallery">Gallery</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- HEADER -->
    <header>
        <h1>Evergreen General Trading</h1>
        <p>Premium Interior Solutions in UAE</p>
    </header>

    <!-- HERO -->
    <section class="hero" id="home">
        <h2>Transform Your Space</h2>
        <p>Curtains | Sofa | Flooring | Wallpaper | Complete Home Décor</p>
        <div class="hero-buttons">
            <a href="tel:+971559667739" class="btn btn-call">📞 Call Now</a>
            <a href="https://wa.me/971559667739" class="btn btn-whatsapp">💬 WhatsApp</a>
        </div>
    </section>

    <!-- SERVICES -->
    <section id="services">
        <h2>Our Services</h2>
        <div class="services-grid">
            <div class="service-card">
                <div class="icon">🪟</div>
                <h3>Curtains & Blinds</h3>
                <p>Custom curtains and blinds for every room style</p>
            </div>
            <div class="service-card">
                <div class="icon">🛋️</div>
                <h3>Sofa & Upholstery</h3>
                <p>Premium furniture and professional upholstery services</p>
            </div>
            <div class="service-card">
                <div class="icon">🪵</div>
                <h3>Flooring</h3>
                <p>Quality flooring options for modern homes</p>
            </div>
            <div class="service-card">
                <div class="icon">🧱</div>
                <h3>Wallpaper & PVC Panels</h3>
                <p>Trendy wallpapers and durable PVC solutions</p>
            </div>
            <div class="service-card">
                <div class="icon">🚪</div>
                <h3>Cabinets & Wardrobes</h3>
                <p>Custom storage solutions for organized living</p>
            </div>
            <div class="service-card">
                <div class="icon">🌴</div>
                <h3>Decking</h3>
                <p>Beautiful outdoor decking installations</p>
            </div>
        </div>
    </section>

    <!-- GALLERY -->
    <section id="gallery">
        <h2>Our Work</h2>
        <div class="gallery">
            <img src="https://images.unsplash.com/photo-1618221195710-dd6b41faaea6?w=400&h=300&fit=crop" alt="Interior Design 1">
            <img src="https://images.unsplash.com/photo-1586023492125-27b2c045efd7?w=400&h=300&fit=crop" alt="Interior Design 2">
            <img src="https://images.unsplash.com/photo-1505691938895-1758d7feb511?w=400&h=300&fit=crop" alt="Interior Design 3">
            <img src="https://images.unsplash.com/photo-1595526114035-0d45ed16cfbf?w=400&h=300&fit=crop" alt="Interior Design 4">
        </div>
    </section>

    <!-- WHY CHOOSE US -->
    <section>
        <h2>Why Choose Us</h2>
        <div class="benefits">
            <div class="benefit-item">
                <h3>✔ Affordable Pricing</h3>
                <p>Competitive rates without compromising quality</p>
            </div>
            <div class="benefit-item">
                <h3>✔ High Quality Work</h3>
                <p>Expert craftsmen with years of experience</p>
            </div>
            <div class="benefit-item">
                <h3>✔ Fast Installation</h3>
                <p>Quick turnaround times for your convenience</p>
            </div>
            <div class="benefit-item">
                <h3>✔ Custom Designs</h3>
                <p>Personalized solutions tailored to your needs</p>
            </div>
        </div>
    </section>

    <!-- CTA -->
    <section class="cta">
        <h2>Ready to Upgrade Your Home?</h2>
        <p>Contact us now for a FREE consultation and personalized quote</p>
        <div class="hero-buttons">
            <a href="tel:+971559667739" class="btn btn-call">📞 Call Now</a>
            <a href="https://wa.me/971559667739" class="btn btn-whatsapp">💬 WhatsApp Now</a>
        </div>
    </section>

    <!-- CONTACT -->
    <section id="contact">
        <h2>Contact Us</h2>
        <div class="contact-container">
            <div class="contact-info">
                <h3>Get in Touch</h3>
                <p>
                    <strong>📞 Phone Numbers:</strong><br>
                    +971 55 966 7739<br>
                    +971 55 114 9968
                </p>
                <p>
                    <strong>📍 Location:</strong><br>
                    Mussafah M10, Abu Dhabi, UAE
                </p>
                <p>
                    <strong>💬 Connect With Us:</strong><br>
                    <a href="https://wa.me/971559667739" style="color: #25D366; text-decoration: none;">Message on WhatsApp</a>
                </p>
            </div>

            <form class="contact-form" onsubmit="handleSubmit(event)">
                <h3>Send us a Message</h3>
                <div class="form-group">
                    <label for="name">Full Name *</label>
                    <input type="text" id="name" name="name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email Address *</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="phone">Phone Number</label>
                    <input type="tel" id="phone" name="phone">
                </div>
                <div class="form-group">
                    <label for="service">Service Interested In</label>
                    <input type="text" id="service" name="service" placeholder="e.g., Curtains, Flooring">
                </div>
                <div class="form-group">
                    <label for="message">Message *</label>
                    <textarea id="message" name="message" required></textarea>
                </div>
                <div class="form-group">
                    <button type="submit">Send Message</button>
                </div>
            </form>
        </div>
    </section>

    <!-- FOOTER -->
    <footer>
        <p>&copy; 2026 Evergreen General Trading. All rights reserved.</p>
        <p>Premium Interior Solutions | UAE</p>
    </footer>

    <!-- WHATSAPP FLOAT BUTTON -->
    <a href="https://wa.me/971559667739" class="whatsapp-float" title="Chat on WhatsApp">💬</a>

    <script>
        function handleSubmit(event) {
            event.preventDefault();
            
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const phone = document.getElementById('phone').value;
            const service = document.getElementById('service').value;
            const message = document.getElementById('message').value;
            
            // Create WhatsApp message
            const whatsappMessage = `Hello Evergreen!\n\nName: ${name}\nEmail: ${email}\nPhone: ${phone}\nInterested Service: ${service}\n\nMessage:\n${message}`;
            const encodedMessage = encodeURIComponent(whatsappMessage);
            const whatsappURL = `https://wa.me/971559667739?text=${encodedMessage}`;
            
            // Open WhatsApp
            window.open(whatsappURL, '_blank');
            
            // Reset form
            document.querySelector('.contact-form').reset();
            
            alert('Thank you! Your message will be sent via WhatsApp.');
        }

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({ behavior: 'smooth' });
                }
            });
        });
    </script>
</body>
</html>
