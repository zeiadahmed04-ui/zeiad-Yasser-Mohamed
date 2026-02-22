<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Zyad Yasser | Electronics Engineer</title>
  <style>
    :root {
      --primary: #4a3c2a;
      --secondary: #6b5b46;
      --accent: #ffd966;
      --bg-light: #f4f1ee;
      --white: #ffffff;
      --text: #333;
    }

    * { box-sizing: border-box; }
    
    html { scroll-behavior: smooth; }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      background-color: var(--bg-light);
      color: var(--text);
      line-height: 1.6;
    }

    /* --- Hero Header --- */
    header {
      background: linear-gradient(135deg, #7ba0a0 0%, #4a3c2a 100%);
      color: white;
      padding: 80px 20px;
      text-align: center;
      position: relative;
    }

    .profile-container {
      display: flex;
      flex-direction: column;
      align-items: center;
      max-width: 1000px;
      margin: 0 auto;
    }

    .profile-img {
      width: 180px;
      height: 180px;
      border-radius: 50%;
      border: 5px solid rgba(255,255,255,0.3);
      object-fit: cover;
      margin-bottom: 20px;
      box-shadow: 0 10px 20px rgba(0,0,0,0.2);
    }

    header h1 { margin: 10px 0; font-size: 2.5rem; }
    
    .btn-resume {
      display: inline-block;
      margin-top: 15px;
      padding: 10px 25px;
      background: var(--accent);
      color: var(--primary);
      font-weight: bold;
      border-radius: 25px;
      transition: transform 0.2s;
    }
    .btn-resume:hover { transform: scale(1.05); }

    /* --- Navigation --- */
    nav {
      background: var(--white);
      padding: 15px;
      display: flex;
      justify-content: center;
      gap: 20px;
      position: sticky;
      top: 0;
      z-index: 1000;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
    }
    nav a {
      font-weight: 600;
      color: var(--secondary);
      font-size: 0.9rem;
      text-transform: uppercase;
    }
    nav a:hover { color: #7ba0a0; }

    /* --- Layout Grid --- */
    .main-container {
      max-width: 1100px;
      margin: 40px auto;
      display: grid;
      grid-template-columns: 1fr 1fr; /* Two Columns */
      gap: 30px;
      padding: 0 20px;
    }

    /* --- Card Styling --- */
    .card {
      background: var(--white);
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.05);
    }

    .card h2 {
      border-left: 5px solid var(--secondary);
      padding-left: 15px;
      margin-top: 0;
      font-size: 1.4rem;
    }

    .full-width { grid-column: 1 / -1; }

    /* --- Image Styling --- */
    .project-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 15px;
      margin-top: 20px;
    }
    .project-item {
      text-align: center;
      background: #fafafa;
      padding: 10px;
      border-radius: 10px;
    }
    .project-item img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 8px;
    }

    /* --- Contact Footer --- */
    footer {
      background: #2c2c2c;
      color: white;
      padding: 40px 20px;
      margin-top: 60px;
      text-align: center;
    }
    .footer-content {
      display: flex;
      justify-content: center;
      gap: 30px;
      flex-wrap: wrap;
    }

    /* --- Responsive --- */
    @media (max-width: 850px) {
      .main-container { grid-template-columns: 1fr; }
    }
  </style>
</head>
<body>

  <header>
    <div class="profile-container">
      <img src="WhatsApp%20Image%202025-08-26%20at%2020.29.45_f00a4dff.jpg" alt="Zyad Yasser" class="profile-img">
      <h1>Zyad Yasser Mohamed</h1>
      <p>Electronics & Electrical Communication Engineer</p>
      <a href="#" class="btn-resume">Download Resume/CV</a>
    </div>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#education">Education</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="main-container">
    
    <div class="column">
      <section id="about" class="card" style="margin-bottom: 30px;">
        <h2>About Me</h2>
        <p>I am an Electronics Engineering student specializing in digital design and embedded systems. I thrive on turning complex hardware concepts into functional, real-world solutions.</p>
      </section>

      <section id="education" class="card">
        <h2>Education</h2>
        <p><strong>Cairo University</strong><br>B.Sc. Electronics & Communication<br>2023 – 2028 | <b>GPA: 3.22</b></p>
        <p><i>Training:</i> NTI Smart Technology & Digital Systems</p>
      </section>
    </div>

    <div class="column">
      <section id="skills" class="card" style="margin-bottom: 30px;">
        <h2>Skills & Expertise</h2>
        <ul style="padding-left: 20px;">
          <li>Digital Design & FPGA (Verilog/Vivado)</li>
          <li>Embedded C & Arduino Robotics</li>
          <li>PCB Design & Circuit Debugging</li>
          <li>MATLAB Modeling</li>
        </ul>
      </section>

      <section id="achievements" class="card">
        <h2>Achievements</h2>
        <p>🏆 Completed 8-bit Processor on FPGA</p>
        <p>🚀 Developed I2C Master Protocol</p>
        <p>🤖 Built Autonomous Obstacle Avoidance Robot</p>
      </section>
    </div>

    <section id="projects" class="card full-width">
      <h2>Featured Projects</h2>
      <div class="project-grid">
        <div class="project-item">
          <img src="Picture5.png" alt="Processor">
          <p>8-bit Processor</p>
        </div>
        <div class="project-item">
          <img src="Picture2.png" alt="Arduino Car">
          <p>Arduino Smart Car</p>
        </div>
        <div class="project-item">
          <img src="Picture1%20(1).png" alt="FPGA Training">
          <p>NTI FPGA Training</p>
        </div>
      </div>
    </section>

  </div>

  <footer id="contact">
    <h2>Get In Touch</h2>
    <div class="footer-content">
      <p>📍 Mokatam, Cairo</p>
      <p>📞 +20 1551667933</p>
      <p>📧 <a href="mailto:zeiad.ahmed04@eng-st.cu.edu.eg" style="color: var(--accent);">zeiad.ahmed04@eng-st.cu.edu.eg</a></p>
    </div>
  </footer>

</body>
</html>
