<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>Bonface Wafula | Electrical Engineering Portfolio</title>
    <!-- Font Awesome Icons (no download needed) -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: #000000;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #e0e0e0;
            line-height: 1.7;
            padding: 20px;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            background: #0a0a0a;
            border-radius: 20px;
            padding: 30px 25px;
            box-shadow: 0 10px 30px rgba(255, 165, 0, 0.2);
            border: 1px solid #ff8c001a;
        }

        /* ORANGE TITLES */
        h1, h2, h3, .section-title {
            color: #ff8c00;
            font-weight: 700;
        }

        h1 {
            font-size: 2.5rem;
            letter-spacing: -0.5px;
            border-left: 5px solid #ff8c00;
            padding-left: 20px;
            margin-bottom: 10px;
        }

        h2 {
            font-size: 1.8rem;
            margin-top: 35px;
            margin-bottom: 20px;
            border-bottom: 2px solid #ff8c00;
            display: inline-block;
            padding-bottom: 5px;
        }

        .subhead {
            color: #cccccc;
            font-size: 1.1rem;
            margin-bottom: 30px;
            padding-left: 25px;
        }

        /* PHOTO STYLING */
        .profile-section {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            gap: 30px;
            margin: 30px 0 20px 0;
            background: #111111;
            padding: 20px;
            border-radius: 20px;
            border: 1px solid #ff8c0040;
        }

        .profile-img {
            width: 150px;
            height: 150px;
            object-fit: cover;
            border-radius: 50%;
            border: 3px solid #ff8c00;
            box-shadow: 0 0 15px rgba(255, 140, 0, 0.5);
            background: #222;
        }

        .profile-text {
            flex: 1;
        }

        /* CARDS */
        .card-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            margin: 25px 0;
        }

        .card {
            background: #111111;
            border-radius: 15px;
            padding: 20px;
            flex: 1;
            min-width: 200px;
            transition: transform 0.2s, box-shadow 0.2s;
            border-left: 4px solid #ff8c00;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(255, 140, 0, 0.2);
        }

        .card i {
            color: #ff8c00;
            font-size: 2rem;
            margin-bottom: 12px;
        }

        .project-item {
            background: #0d0d0d;
            padding: 18px;
            margin: 15px 0;
            border-radius: 12px;
            border-right: 3px solid #ff8c00;
        }

        /* SKILLS BADGES */
        .skill-badge {
            display: inline-block;
            background: #1f1f1f;
            color: #ffaa33;
            padding: 5px 12px;
            border-radius: 30px;
            font-size: 0.8rem;
            margin: 5px 5px 0 0;
            border: 1px solid #ff8c0066;
        }

        /* SOCIAL ICONS */
        .social-icons {
            margin: 30px 0 20px;
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }

        .social-icons a {
            background: #1a1a1a;
            color: #ff8c00;
            font-size: 1.8rem;
            width: 55px;
            height: 55px;
            border-radius: 50%;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s ease;
            text-decoration: none;
            border: 1px solid #ff8c0066;
        }

        .social-icons a:hover {
            background: #ff8c00;
            color: #000000;
            transform: scale(1.05);
        }

        /* LISTS & TEXT */
        ul, .info-line {
            margin: 15px 0;
            padding-left: 25px;
        }

        li {
            margin: 10px 0;
        }

        .info-line i {
            width: 30px;
            color: #ff8c00;
            margin-right: 10px;
        }

        hr {
            border-color: #ff8c0033;
            margin: 20px 0;
        }

        footer {
            text-align: center;
            margin-top: 45px;
            font-size: 0.85rem;
            color: #777;
            border-top: 1px solid #ff8c0020;
            padding-top: 25px;
        }

        @media (max-width: 600px) {
            .container {
                padding: 20px 15px;
            }
            h1 {
                font-size: 1.8rem;
            }
            .profile-section {
                flex-direction: column;
                text-align: center;
            }
            .social-icons a {
                width: 45px;
                height: 45px;
                font-size: 1.4rem;
            }
        }
    </style>
</head>
<body>
<div class="container">

    <!-- TITLE (ORANGE) -->
    <h1> BONFACE WAFULA</h1>
    <div class="subhead">Electrical & Electronics Engineering Student | AI & Hardware Explorer</div>

    <!-- PHOTO SECTION (ADD YOUR PHOTO URL OR REPLACE WITH YOUR IMAGE) -->
    <div class="profile-section">
        <!-- REPLACE "20260417_123355.jpg" WITH YOUR ACTUAL IMAGE LINK OR USE A PLACEHOLDER -->
        <img src="https://via.placeholder.com/150/ff8c00/000000?text=BONFACE" alt="Bonface Wafula" class="profile-img" id="profileImage">
        <div class="profile-text">
            <p><i class="fas fa-quote-left" style="color:#ff8c00; margin-right:8px;"></i> 
            3rd year engineering student passionate about tech projects, artificial intelligence, machine learning, and designing simple electronic devices. I merge hardware with intelligence to solve real problems.</p>
            <p><strong> Kitui, Kenya</strong> | <strong> South Eastern Kenya University</strong></p>
        </div>
    </div>

    <!-- WHAT I DO (CARDS) -->
    <h2><i class="fas fa-microchip"></i> What I Do</h2>
    <div class="card-grid">
        <div class="card">
            <i class="fas fa-plug"></i>
            <h3>Electronic Device Design</h3>
            <p>Create simple, functional electronic devices from concept to prototype. PCB design, soldering, and testing.</p>
        </div>
        <div class="card">
            <i class="fas fa-brain"></i>
            <h3>AI & Machine Learning</h3>
            <p>Learning how to apply ML to real-world engineering problems — from predictive maintenance to TinyML on microcontrollers.</p>
        </div>
        <div class="card">
            <i class="fas fa-laptop-code"></i>
            <h3>Tech Projects</h3>
            <p>Building and documenting projects at the intersection of hardware and software. Open source and collaborative.</p>
        </div>
    </div>

    <!-- PROJECTS SECTION (ENHANCED) -->
    <h2><i class="fas fa-project-diagram"></i> Featured Projects</h2>
    <div class="project-item">
        <i class="fas fa-lightbulb" style="color:#ff8c00;"></i>
        <strong>🔹 Simple LED Circuit & Timer</strong><br>
        Designed a 555 timer-based LED flasher on a breadboard. Learned about timing capacitors, transistor switching, and circuit debugging. <span class="skill-badge">Analog Circuits</span> <span class="skill-badge">555 Timer</span>
    </div>
    <div class="project-item">
        <i class="fas fa-temperature-high" style="color:#ff8c00;"></i>
        <strong>🔹 Temperature Monitoring System (IoT Basics)</strong><br>
        Using an Arduino and LM35 sensor to read room temperature and display on LCD. Currently adding Bluetooth module for phone alerts. <span class="skill-badge">Arduino</span> <span class="skill-badge">Sensors</span>
    </div>
    <div class="project-item">
        <i class="fas fa-robot" style="color:#ff8c00;"></i>
        <strong>🔹 AI-Powered Smart Switch (In Progress)</strong><br>
        Integrating a simple machine learning model to recognize voice commands or gestures to control home appliances. <span class="skill-badge">TinyML</span> <span class="skill-badge">Edge AI</span>
    </div>

    <!-- ACHIEVEMENTS & QUALIFICATIONS (STUDY PURPOSE) -->
    <h2><i class="fas fa-trophy"></i> Achievements & Certifications</h2>
    <ul>
        <li> <strong>Introduction to Machine Learning</strong> – Coursera / Stanford Online (2025)</li>
        <li> <strong>PCB Design Workshop</strong> – Kenya Advanced Institute of Science and Technology</li>
        <li><strong>Arduino Programming & Sensors</strong> – Udemy Certified</li>
        <li> <strong>3+ Practical Hardware Projects</strong> completed and documented</li>
        <li> <strong>Data Analysis with Python</strong> – FreeCodeCamp</li>
    </ul>

    <h2><i class="fas fa-graduation-cap"></i> Qualifications & Study Focus</h2>
    <ul>
        <li> <strong>BSc Electrical & Electronics Engineering</strong> – South Eastern Kenya University (2023 – 2028 expected)</li>
        <li> <strong>Relevant Coursework:</strong> Circuit Theory, Digital Electronics, Embedded Systems, Signals & Systems, Control Engineering</li>
        <li> <strong>Self-Study:</strong> Machine Learning Specialization (DeepLearning.AI), TinyML for microcontrollers</li>
        <li> <strong>Soft Skills:</strong> Problem solving, Technical documentation, Team collaboration, Fast learner</li>
    </ul>

    <!-- WHAT I'M LEARNING -->
    <h2><i class="fas fa-chalkboard-user"></i> Currently Learning</h2>
    <div class="card-grid">
        <div class="card">
            <i class="fas fa-chart-line"></i>
            <h3>Machine Learning Basics</h3>
            <p>Regression, classification, and neural networks using Python & TensorFlow.</p>
        </div>
        <div class="card">
            <i class="fas fa-microchip"></i>
            <h3>TinyML & Edge AI</h3>
            <p>Running ML models on low-power microcontrollers (ESP32, Arduino Nano).</p>
        </div>
        <div class="card">
            <i class="fas fa-waveform"></i>
            <h3>Advanced Circuit Design</h3>
            <p>Using KiCad for PCB layout and simulation before prototyping.</p>
        </div>
    </div>

    <!-- SOCIAL MEDIA WITH ICONS (MY HANDLES) -->
    <h2><i class="fas fa-share-alt"></i> Connect With Me</h2>
    <div class="social-icons">
        <a href="mailto:bonfacewafula256@gmail.com" target="_blank"><i class="fas fa-envelope"></i></a>
        <a href="https://wa.me/254712898486" target="_blank"><i class="fab fa-whatsapp"></i></a>
        <a href="https://x.com/bonny_nitez" target="_blank"><i class="fab fa-twitter"></i></a>
        <a href="https://www.instagram.com/_.bon_ny.__" target="_blank"><i class="fab fa-instagram"></i></a>
        <a href="https://github.com/Bonface-Wafula" target="_blank"><i class="fab fa-github"></i></a>
        <a href="https://www.linkedin.com/in/bonface-wafula" target="_blank"><i class="fab fa-linkedin-in"></i></a>
    </div>

    <!-- CONTACT INFO LINE -->
    <div class="info-line">
        <p><i class="fas fa-phone-alt"></i> WhatsApp / Call: 0712 898486</p>
        <p><i class="fas fa-map-marker-alt"></i> Kitui, Kenya (Open to collaborations & freelance projects)</p>
        <p><i class="fas fa-university"></i> South Eastern Kenya University – Electrical Engineering Dept.</p>
    </div>

    <hr>
    <footer>
        <i class="fas fa-code"></i> Built with HTML/CSS by Bonface Wafula | <i class="far fa-heart" style="color:#ff8c00;"></i> Learning in public • 2025
    </footer>
</div>
</body>
</html>