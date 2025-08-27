<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Zyad Yasser Portfolio</title>
  <style>
    /* --- Global Styles --- */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #fdfcfb;
      color: #333;
    }
    h1, h2 {
      color: #4a3c2a;
    }
    a {
      text-decoration: none;
      color: inherit;
    }

    /* --- Header --- */
    header {
      background: #4a3c2a;
      color: white;
      padding: 60px 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.8em;
    }
    header p {
      margin: 5px 0;
      font-size: 1.2em;
    }

    /* --- Navigation --- */
    nav {
      background: #6b5b46;
      padding: 12px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      font-weight: bold;
    }
    nav a:hover {
      color: #ffd966;
    }

    /* --- Sections --- */
    section {
      max-width: 1000px;
      margin: 40px auto;
      padding: 20px;
    }
    section img {
      max-width: 100%;
      border-radius: 10px;
      margin: 10px 0;
    }

    /* --- Contact --- */
    .contact {
      background: #4a3c2a;
      color: white;
      padding: 30px;
      text-align: center;
    }
    .contact a {
      color: #ffd966;
    }

    /* --- Responsive --- */
    @media (max-width: 768px) {
      nav {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
      }
      nav a {
        margin: 5px 10px;
      }
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <img src="WhatsApp Image 2025-08-26 at 20.44.57_fd487b78.jpg" alt="Profile Picture" width="150" style="border-radius: 50%; border: 3px solid #fff;">
    <h1>Zyad Yasser Mohamed</h1>
    <p>Electronics & Electrical Communication Engineer</p>
    <p>Portfolio</p>
  </header>

  <!-- Navigation -->
  <nav>
    <a href="#about">About</a>
    <a href="#education">Education</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#achievements">Achievements</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>I am an Electronics Engineering student with a strong interest in digital design, embedded systems, and FPGA development. I enjoy building practical projects that combine hardware and software. My goal is to apply engineering knowledge to solve real-world problems, while continuously improving my technical and research skills.</p>
    <h3>Why Me?</h3>
    <p>You should choose me because I bring a combination of technical knowledge, hands-on project experience, and a passion for continuous learning. From designing processors on FPGA to working with Arduino applications, I have proven my ability to turn concepts into working solutions.</p>
  </section>

  <!-- Education Section -->
  <section id="education">
    <h2>Education</h2>
    <p><strong>Cairo University</strong> – Electronics & Electrical Communications (Aug 2023 – Jan 2028)<br>GPA: 3.22</p>
    <p>Training: Timmerman Industries, National Telecommunication Institute (NTI)</p>
  </section>

  <!-- Skills Section -->
  <section id="skills">
    <h2>Skills & Expertise</h2>
    <ul>
      <li>Digital Design & FPGA (Verilog, Vivado, ModelSim)</li>
      <li>Embedded Systems & Arduino</li>
      <li>PCB Design</li>
      <li>Circuit Simulation & Debugging</li>
      <li>MATLAB for modeling & testing</li>
    </ul>
    <img src="Picture2.png" alt="Skills illustration">
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <h2>Previous Projects</h2>
    <ul>
      <li>Designed and implemented an 8-bit processor on FPGA using Verilog</li>
      <li>Developed an I2C master protocol for device communication</li>
      <li>Created PISO and SIPO converters for data transfer</li>
      <li>Designed a clock divider for accurate timing signals</li>
      <li>Built an Arduino-based smart car with sensors and obstacle avoidance</li>
    </ul>
    <img src="Picture5.png" alt="8-bit processor project">
    <img src="Picture7.png" alt="Smart car project">
  </section>

  <!-- Achievements Section -->
  <section id="achievements">
    <h2>Achievements</h2>
    <ul>
      <li>Successfully completed FPGA-based 8-bit processor design</li>
      <li>Developed working I2C communication protocol</li>
      <li>Arduino automation and robotics projects</li>
      <li>Hands-on training at NTI in FPGA and digital systems</li>
    </ul>
    <img src="Picture3.png" alt="Achievements">
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <h2>Contact</h2>
    <p>Mokatam, Cairo</p>
    <p>📞 +20 1551667933</p>
    <p>📧 <a href="mailto:zeiad.ahmed04@eng-st.cu.edu.eg">zeiad.ahmed04@eng-st.cu.edu.eg</a></p>
  </section>
</body>
</html>
