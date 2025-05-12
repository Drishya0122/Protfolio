<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Drishya Kadadas - Portfolio">
  <meta name="author" content="Drishya Kadadas">
  <title>Drishya Kadadas - Portfolio</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Roboto', sans-serif;
      background-color: #f0f2f5;
      color: #333;
      line-height: 1.6;
    }
    header {
      background-color: #1f2937;
      padding: 20px 0;
      color: #fff;
    }
    nav ul {
      display: flex;
      justify-content: center;
      list-style: none;
    }
    nav ul li {
      margin: 0 15px;
    }
    nav ul li a {
      color: #fff;
      text-decoration: none;
      font-size: 18px;
      transition: color 0.3s;
    }
    nav ul li a:hover {
      color: #38bdf8;
    }
    section {
      padding: 60px 20px;
    }
    .container {
      max-width: 1100px;
      margin: auto;
    }
    h1, h2, h3 {
      margin-bottom: 20px;
      font-weight: 700;
    }
    #home {
      background: linear-gradient(to right, #2563eb, #1e40af);
      color: white;
      text-align: center;
      padding: 100px 20px;
    }
    .btn {
      display: inline-block;
      background: #38bdf8;
      color: white;
      padding: 12px 25px;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 20px;
      transition: background 0.3s;
    }
    .btn:hover {
      background: #0ea5e9;
    }
    .project-cards {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    .project-card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
      width: 300px;
    }
    footer {
      background-color: #1f2937;
      color: white;
      text-align: center;
      padding: 20px 0;
    }
    .contact-links li {
      margin: 10px 0;
    }
    .contact-links a {
      color: #2563eb;
      text-decoration: none;
    }
    .contact-links a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

<header>
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
</header>

<section id="home">
  <div class="container">
    <h1>Drishya Kadadas</h1>
    <p>Aspiring Junior ICT Engineer | IoT & Robotics Enthusiast</p>
    <a href="#about" class="btn">Explore More</a>
  </div>
</section>

<section id="about">
  <div class="container">
    <h2>About Me</h2>
    <p>I am currently pursuing a Diploma in Information and Communication Technology at Government Polytechnic, Gandhinagar (7.63 CGPA). With hands-on experience as an intern at Tinkering India and Eduneuro, I specialize in IoT, Robotics, and EdTech development.</p>
    <p>My passion lies in embedded systems, web development, and using technology to create impactful solutions. I enjoy facilitating workshops and engaging with young innovators.</p>
  </div>
</section>

<section id="skills">
  <div class="container">
    <h2>Skills</h2>
    <ul>
      <li>Programming: C, C++, HTML, CSS, Embedded C</li>
      <li>Web Tools: WordPress, Git</li>
      <li>Soft Skills: Communication, Teamwork, Public Speaking, Problem Solving</li>
      <li>Specialties: IoT, Robotics, Troubleshooting, Creativity & Innovation</li>
    </ul>
  </div>
</section>

<section id="projects">
  <div class="container">
    <h2>Projects</h2>
    <div class="project-cards">
      <div class="project-card">
        <h3>IoT-Based Air Pollution Monitoring</h3>
        <p>Developed a real-time environmental monitoring system using sensors and IoT technologies to track and report air quality.</p>
        <a href="#" class="btn">View Project</a>
      </div>
      <div class="project-card">
        <h3>Tinkering India Website</h3>
        <p>Designed and implemented a news page and content for the Tinkering India site using WordPress and GitHub.</p>
        <a href="#" class="btn">Visit Site</a>
      </div>
    </div>
  </div>
</section>

<section id="contact">
  <div class="container">
    <h2>Contact Me</h2>
    <p>Want to collaborate or connect? Reach out below.</p>
    <ul class="contact-links">
      <li><i class="fas fa-envelope"></i> <a href="mailto:drishyakadadas@gmail.com">drishyakadadas@gmail.com</a></li>
      <li><i class="fab fa-linkedin"></i> <a href="https://www.linkedin.com/in/drishya-kadadas">LinkedIn</a></li>
      <li><i class="fas fa-map-marker-alt"></i> Ahmedabad, Gujarat, India</li>
      <li><i class="fas fa-phone"></i> +91 8866544016</li>
    </ul>
  </div>
</section>

<footer>
  <div class="container">
    <p>&copy; 2025 Drishya Kadadas | Designed with passion</p>
  </div>
</footer>

<script>
  document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
      e.preventDefault();
      document.querySelector(this.getAttribute('href')).scrollIntoView({ behavior: 'smooth' });
    });
  });
</script>

</body>
</html>
