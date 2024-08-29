<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="portfolio.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="logo">
            <h1>RITU MISHRA</h1>
        </div>
        <p class="tagline">Creative Developer | Problem Solver</p>
    </header>

    <!-- About Section -->
    <section id="about">
        <div class="about-content">
            <img src="riiii.jpg" alt="Your Name" class="profile-pic">
            <div class="bio">
                <h2>About Me</h2>
                <p>I am a dedicated developer with experience in web development, project management, and digital marketing. Passionate about creating innovative solutions, I have led various projects and contributed to tech communities through volunteering and leadership roles.</p>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>Skills</h2>
        <div class="skills-container">
            <div class="skills-column">
                <h3>Technical Skills</h3>
                <div class="skill">
                    <h4>Web Development</h4>
                </div>
                <div class="skill">
                    <h4>Project Management</h4>
                </div>
            </div>
            <div class="skills-column">
                <h3>Soft Skills</h3>
                <div class="skill">
                    <h4>Creative Design</h4>
                </div>
                <div class="skill">
                    <h4>Digital Marketing</h4>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Projects</h2>
        <div class="projects-grid">
            <div class="project-item">
                <img src="stry.png" alt="Project 1">
                <h3>story time chatbot</h3>
                <p> Focusing on a quick and efficient user experience
                  by streamlining the app with limited functionality reflects a thoughtful approach.</p>
            </div>
            <div class="project-item">
                <img src="con.jpg" alt="Project 2">
                <h3>currency converter app</h3>
                <p>Utilized modern Android development practices 
                  to ensure high performance and reliability. .</p>
            </div>
            <div class="project-item">
                <img src="docs.jpg" alt="Project 3">
                <h3>Docs Mini App</h3>
                <p> Focusing on a quick and efficient user experience
                  by streamlining the app with limited functionality reflects a thoughtful approach.</p>
            </div>
            <!-- Add more projects as needed -->
        </div>
    </section>

    <!-- Resume Section -->
    <section id="resume">
        <h2>Resume</h2>
        <a href="ritu mishra (1).pdf" class="resume-btn" download>Download My Resume</a>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact</h2>
        <div class="contact-info">
            <p>Email: <a href="mailto:your-email@example.com">your-email@example.com</a></p>
            <p>Phone: <a href="tel:+1234567890">+123 456 7890</a></p>
            <form action="#" method="POST" class="contact-form">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
                <button type="submit">Send Message</bu
