# porfolio
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nikhil Patel | Portfolio</title>
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { font-family: Arial, Helvetica, sans-serif; line-height: 1.6; color: #333; background: #fff; }
  a { text-decoration: none; color: inherit; }
  img { max-width: 100%; display: block; }
  section { max-width: 900px; margin: 0 auto; padding: 60px 20px; }
  .section-title { font-size: 28px; margin-bottom: 30px; text-align: center; color: #222; }

  header { background: #222; padding: 15px 0; position: sticky; top: 0; }
  nav { max-width: 900px; margin: 0 auto; padding: 0 20px; display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; }
  .logo { color: #fff; font-size: 20px; }
  nav ul { list-style: none; display: flex; gap: 20px; flex-wrap: wrap; }
  nav ul li a { color: #fff; font-size: 15px; }
  nav ul li a:hover { color: #4a90e2; }

  .hero { text-align: center; padding: 100px 20px; background: #f4f4f4; }
  .hero h1 { font-size: 36px; margin-bottom: 10px; }
  .hero h1 span { color: #4a90e2; }
  .hero h2 { font-size: 20px; color: #555; margin-bottom: 20px; }
  .hero p { max-width: 500px; margin: 0 auto 25px; color: #555; }

  .btn { display: inline-block; background: #4a90e2; color: #fff; padding: 10px 25px; border-radius: 5px; }
  .btn:hover { background: #357abd; }

  .about-container { display: flex; gap: 30px; align-items: center; flex-wrap: wrap; }
  .about-container img { width: 200px; border-radius: 50%; }
  .about-container p { margin-bottom: 15px; color: #555; }

  .skills-container { display: flex; flex-wrap: wrap; gap: 12px; justify-content: center; }
  .skill { background: #4a90e2; color: #fff; padding: 10px 20px; border-radius: 5px; font-size: 14px; }

  .project-container { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
  .project-card { border: 1px solid #ddd; border-radius: 6px; overflow: hidden; text-align: center; padding-bottom: 20px; }
  .project-card img { width: 100%; height: 180px; object-fit: cover; margin-bottom: 15px; }
  .project-card h3 { margin-bottom: 10px; }
  .project-card p { color: #555; padding: 0 15px; margin-bottom: 15px; }

  .timeline-item { border-left: 3px solid #4a90e2; padding-left: 20px; margin-bottom: 30px; }
  .timeline-date { display: block; color: #4a90e2; font-size: 14px; margin-bottom: 8px; }
  .timeline-content p { color: #555; }

  #resume, .contact-info { text-align: center; }
  #resume p, .contact-info p { margin-bottom: 15px; color: #555; }

  footer { background: #222; color: #fff; text-align: center; padding: 20px; }

  @media (max-width: 600px) {
    .about-container { flex-direction: column; text-align: center; }
  }
</style>
</head>
<body>

<header>
  <nav>
    <h2 class="logo">Nikhil Patel</h2>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#education">Education</a></li>
      <li><a href="#resume">Resume</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
</header>

<section id="home" class="hero">
  <h1>Hello, I'm <span>Nikhil Patel</span></h1>
  <h2>Web Development Beginner</h2>
  <p>I am an MCA student interested in Web Development, Python and SQL.</p>
  <a href="#projects" class="btn">View My Work</a>
</section>

<section id="about">
  <h2 class="section-title">About Me</h2>
  <div class="about-container">
    <img src="profile.jpg" alt="Nikhil Patel">
    <div>
      <p>Hello! I am Nikhil Patel, an MCA student at ICFAI University Raipur. I have basic knowledge of HTML, CSS, JavaScript, Python and SQL.</p>
      <p>I am interested in improving my programming and web development skills and building useful websites and applications.</p>
    </div>
  </div>
</section>

<section id="skills">
  <h2 class="section-title">My Skills</h2>
  <div class="skills-container">
    <div class="skill">HTML</div>
    <div class="skill">CSS</div>
    <div class="skill">JavaScript</div>
    <div class="skill">Python</div>
    <div class="skill">SQL</div>
    <div class="skill">C++</div>
  </div>
</section>

<section id="projects">
  <h2 class="section-title">My Projects</h2>
  <div class="project-container">
    <div class="project-card">
      <img src="project1.jpg" alt="Portfolio Project">
      <h3>Personal Portfolio</h3>
      <p>A responsive personal portfolio website created using HTML and CSS.</p>
      <a href="#" class="btn">View Project</a>
    </div>
    <div class="project-card">
      <img src="project2.jpg" alt="Calculator Project">
      <h3>Calculator</h3>
      <p>A simple calculator website created using HTML, CSS and JavaScript.</p>
      <a href="#" class="btn">View Project</a>
    </div>
    <div class="project-card">
      <img src="project3.jpg" alt="To Do List">
      <h3>To-Do List</h3>
      <p>A simple task management application using HTML, CSS and JavaScript.</p>
      <a href="#" class="btn">View Project</a>
    </div>
  </div>
</section>

<section id="education">
  <h2 class="section-title">Education</h2>
  <div class="timeline-item">
    <h3>MCA — Master of Computer Applications</h3>
    <span class="timeline-date">2025 – 2027</span>
    <div class="timeline-content"><p>ICFAI University, Raipur</p><p>Focused on Web Development, Python and SQL.</p></div>
  </div>
  <div class="timeline-item">
    <h3>B.Sc. — Computer Science</h3>
    <span class="timeline-date">2022 – 2025</span>
    <div class="timeline-content"><p>Hemchand Yadav University</p><p>Built foundation in programming and computer fundamentals.</p></div>
  </div>
  <div class="timeline-item">
    <h3>12th (Senior Secondary)</h3>
    <span class="timeline-date">2021 – 2022</span>
    <div class="timeline-content"><p>Swami Athmannad English Medium School</p></div>
  </div>
</section>

<section id="resume">
  <h2 class="section-title">My Resume</h2>
  <p>Click below to download my resume.</p>
  <a href="resume.pdf" download class="btn">Download Resume</a>
</section>

<section id="contact">
  <h2 class="section-title">Contact Me</h2>
  <div class="contact-info">
    <p><strong>Email:</strong> your-email@gmail.com</p>
    <p><strong>Phone:</strong> +91 XXXXX XXXXX</p>
    <p><strong>Location:</strong> Chhattisgarh, India</p>
  </div>
</section>

<footer>
  <p>&copy; 2026 Nikhil Patel. All Rights Reserved.</p>
</footer>

</body>
</html>
