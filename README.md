<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background: #f4f4f4;
    }
    header {
      background: #333;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 40px;
      max-width: 1000px;
      margin: auto;
      background: #fff;
      margin-bottom: 20px;
      border-radius: 8px;
    }
    h2 {
      border-bottom: 2px solid #333;
      padding-bottom: 10px;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .project {
      background: #fafafa;
      padding: 20px;
      border: 1px solid #ddd;
      border-radius: 6px;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #333;
      color: #fff;
    }
    .btn {
      display: inline-block;
      padding: 10px 15px;
      background: #333;
      color: #fff;
      text-decoration: none;
      border-radius: 5px;
    }
  </style>
</head>
<body>

<header>
  <h1>Your Name</h1>
  <p>Data Analyst | Problem Solver | Tech Enthusiast</p>
  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#skills">Skills</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section id="about">
  <h2>About Me</h2>
  <p>
    Hello! I'm a passionate professional with experience in data analysis, business intelligence, and problem-solving. I enjoy transforming data into actionable insights.
  </p>
</section>

<section id="projects">
  <h2>Projects</h2>
  <div class="projects">
    <div class="project">
      <h3>Project 1</h3>
      <p>Description of your project.</p>
      <a href="#" class="btn">View Project</a>
    </div>
    <div class="project">
      <h3>Project 2</h3>
      <p>Description of your project.</p>
      <a href="#" class="btn">View Project</a>
    </div>
    <div class="project">
      <h3>Project 3</h3>
      <p>Description of your project.</p>
      <a href="#" class="btn">View Project</a>
    </div>
  </div>
</section>

<section id="skills">
  <h2>Skills</h2>
  <ul>
    <li>SQL</li>
    <li>Python</li>
    <li>Excel</li>
    <li>Power BI</li>
    <li>Data Visualization</li>
  </ul>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>Email: your.email@example.com</p>
  <p>LinkedIn: linkedin.com/in/yourprofile</p>
</section>

<footer>
  <p>© 2026 Your Name. All Rights Reserved.</p>
</footer>

</body>
</html>
