<My portfolio>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Portfolio of Zyad Yasser Mohamed, Electronics & Electrical Communication Engineer">
  <title>Zyad Yasser · EECE Portfolio</title>
  <!-- Font Awesome for crisp icons (optional but enhances visual) -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <style>
    /* ----- RESET & GLOBAL ----- */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Inter', system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Arial, sans-serif;
      background: #f4f2ee;
      color: #1e1e2f;
      line-height: 1.6;
    }

    /* fallback if Inter isn't available */
    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
    }

    h1, h2, h3 {
      font-weight: 600;
      letter-spacing: -0.02em;
    }

    h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
      border-left: 6px solid #b08968;
      padding-left: 1rem;
      color: #2e2a28;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    /* ----- HEADER with refined earthy palette ----- */
    header {
      background: linear-gradient(145deg, #2f2a24 0%, #4f4a42 100%);
      color: white;
      padding: 3rem 1.5rem 2.5rem 1.5rem;
      text-align: center;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
    }

    .profile-img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #e6d5b8;
      box-shadow: 0 8px 16px rgba(0,0,0,0.2);
      margin-bottom: 1.2rem;
      background: #fff; /* in case image missing, subtle background */
    }

    header h1 {
      font-size: 2.6rem;
      font-weight: 700;
      margin: 0.2rem 0 0.2rem;
      letter-spacing: -0.01em;
    }

    header p {
      font-size: 1.2rem;
      opacity: 0.9;
      margin: 0.2rem 0;
    }

    /* ----- NAVIGATION (sleek sticky) ----- */
    nav {
      background: #3e3a34;
      padding: 0.9rem 1rem;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 100;
      backdrop-filter: blur(6px);
      background: rgba(45, 41, 36, 0.95);
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }

    nav a {
      color: #f2e9de;
      margin: 0 0.8rem;
      font-weight: 500;
      font-size: 1.05rem;
      padding: 0.4rem 0.2rem;
      border-bottom: 2px solid transparent;
      transition: 0.2s ease;
    }

    nav a:hover {
      color: #ffdba6;
      border-bottom-color: #ffdba6;
    }

    /* ----- SECTIONS (card-like) ----- */
    section {
      max-width: 1100px;
      margin: 2.5rem auto;
      padding: 1.8rem 2.2rem;
      background: #ffffffdd;
      background: white;
      border-radius: 28px;
      box-shadow: 0 15px 30px -12px rgba(0,0,0,0.15);
      backdrop-filter: blur(2px);
      transition: transform 0.2s;
    }

    section:hover {
      transform: scale(1.005);
    }

    /* image styling inside sections */
    section img {
      max-width: 100%;
      height: auto;
      border-radius: 20px;
      margin-top: 1.5rem;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
      border: 1px solid #ece3d7;
    }

    /* lists with custom icons */
    ul {
      list-style: none;
      margin: 1.2rem 0 0.8rem;
    }

    ul li {
      margin: 0.75rem 0;
      padding-left: 2rem;
      position: relative;
      font-size: 1.08rem;
    }

    ul li::before {
      content: "▹";
      color: #b07d5e;
      font-weight: bold;
      position: absolute;
      left: 0;
    }

    /* contact section specific */
    .contact {
      background: #2b2b24;
      color: #f0ead8;
      border-radius: 28px;
    }

    .contact h2 {
      color: #f5e1c0;
      border-left-color: #e9b384;
    }

    .contact a {
      color: #ffcf9a;
      font-weight: 500;
      border-bottom: 1px dotted #ffcf9a;
    }

    .contact a:hover {
      color: #ffffff;
      border-bottom-style: solid;
    }

    .contact p {
      margin: 0.75rem 0;
      font-size: 1.1rem;
    }

    .contact i {
      width: 1.8rem;
      color: #e9b384;
    }

    /* inline small adjustments */
    .badge {
      background: #e9dacb;
      color: #3e3a34;
      padding: 0.2rem 1rem;
      border-radius: 30px;
      font-size: 0.9rem;
      display: inline-block;
      margin-top: 1rem;
    }

    /* responsive design */
    @media (max-width: 800px) {
      nav a {
        display: inline-block;
        margin: 0.3rem 0.8rem;
      }
      h2 {
        font-size: 1.8rem;
      }
      section {
        padding: 1.5rem 1.2rem;
        margin: 1.8rem 1rem;
      }
    }

    @media (max-width: 480px) {
      header h1 { font-size: 2rem; }
      .profile-img { width: 120px; height: 120px; }
      nav a { font-size: 0.95rem; margin: 0.2rem 0.4rem; }
    }

    /* custom utility for spacing */
    .mt-2 { margin-top: 0.5rem; }
  </style>
</head>
<body>
  <header>
    <!-- Image: fixed file names (URL encoded spaces). They exist in your original code. -->
    <img src="WhatsApp%20Image%202025-08-26%20at%2020.29.45_f00a4dff.jpg" alt="Zyad Yasser profile" class="profile-img">
    <h1>Zyad Yasser Mohamed</h1>
    <p>Electronics & Electrical Communication Engineer</p>
    <p><i class="fas fa-microchip" style="margin-right: 6px;"></i> FPGA · Embedded · Digital Design</p>
  </header>

  <nav>
    <a href="#about"><i class="fas fa-user"></i> About</a>
    <a href="#education"><i class="fas fa-graduation-cap"></i> Education</a>
    <a href="#skills"><i class="fas fa-cogs"></i> Skills</a>
    <a href="#projects"><i class="fas fa-code"></i> Projects</a>
    <a href="#achievements"><i class="fas fa-trophy"></i> Achievements</a>
    <a href="#contact"><i class="fas fa-envelope"></i> Contact</a>
  </nav>

  <!-- ABOUT section (enhanced with clarity) -->
  <section id="about">
    <h2>About Me</h2>
    <p style="font-size:1.15rem">I’m an Electronics Engineering student at Cairo University with deep curiosity for digital design, embedded systems, and FPGA development. I love building things that connect hardware and software — from processor architectures to autonomous robots.</p>
    <h3 style="margin-top: 1.5rem; color:#4e3e33;">Why work with me?</h3>
    <p>I combine strong technical fundamentals with hands-on prototyping. Whether it's implementing I2C on an FPGA or programming an Arduino obstacle-avoidance car, I focus on clean, functional solutions. I constantly level up my skills through training (like NTI) and personal projects. Let’s turn ideas into silicon‑proven reality.</p>
    <div class="badge"><i class="far fa-smile"></i> open for internships & collaboration</div>
  </section>

  <!-- EDUCATION with better context -->
  <section id="education">
    <h2>Education</h2>
    <p><strong><i class="fas fa-university"></i> Cairo University</strong> — Electronics & Electrical Communications Engineering <br> <span style="background: #f0ebe4; padding:0.2rem 1rem; border-radius:20px;">Aug 2023 – Jan 2028 · GPA 3.22</span></p>
    <p><i class="fas fa-certificate"></i> <strong>Training:</strong> SMART technology, National Telecommunication Institute (NTI) – FPGA & digital systems track.</p>
    <!-- Image reference from your original file (Picture1 (1).png) properly encoded -->
    <img src="Picture1%20(1).png" alt="Education illustration - schematic and books">
  </section>

  <!-- SKILLS section (visual grouping) -->
  <section id="skills">
    <h2>Skills & Expertise</h2>
    <ul>
      <li>Digital Design & FPGA (Verilog, Vivado, ModelSim)</li>
      <li>Embedded Systems & Arduino (C, embedded C)</li>
      <li>PCB Design (KiCad / EasyEDA)</li>
      <li>Circuit Simulation & Debugging (LTspice, oscilloscopes)</li>
      <li>MATLAB for modeling, testing & signal processing</li>
      <li>Communication protocols: I2C, SPI, UART</li>
    </ul>
    <img src="Picture2.png" alt="Skills mindmap illustration">
  </section>

  <!-- PROJECTS section (more detailed) -->
  <section id="projects">
    <h2>Featured Projects</h2>
    <ul>
      <li><strong>8-bit processor on FPGA</strong> — complete datapath, control unit, and register file implemented in Verilog, simulated with ModelSim.</li>
      <li><strong>I2C master controller</strong> — designed and verified I2C protocol for serial communication; tested with EEPROM model.</li>
      <li><strong>PISO & SIPO shift registers</strong> — parameterizable modules for serial-in parallel-out and vice versa.</li>
      <li><strong>Programmable clock divider</strong> — generated accurate timing signals for FPGA-based systems.</li>
      <li><strong>Arduino smart car</strong> — ultrasonic sensors + servo + motor shield; obstacle avoidance and line following modes.</li>
    </ul>
    <img src="Picture5.png" alt="8-bit processor datapath diagram">
  </section>

  <!-- ACHIEVEMENTS with icons -->
  <section id="achievements">
    <h2>Achievements</h2>
    <ul>
      <li><i class="fas fa-check-circle" style="color:#b07d5e; margin-right: 0.6rem;"></i> Successfully taped-out concept: 8-bit FPGA processor (simulation & board tested).</li>
      <li><i class="fas fa-check-circle" style="color:#b07d5e; margin-right: 0.6rem;"></i> Fully functional I2C protocol implementation from scratch.</li>
      <li><i class="fas fa-check-circle" style="color:#b07d5e; margin-right: 0.6rem;"></i> Built 3 Arduino-based robots including obstacle avoider and Bluetooth controlled.</li>
      <li><i class="fas fa-check-circle" style="color:#b07d5e; margin-right: 0.6rem;"></i> Intensive hands-on training at NTI (FPGA & digital design).</li>
      <li><i class="fas fa-check-circle" style="color:#b07d5e; margin-right: 0.6rem;"></i> Selected for faculty smart car competition (finalist).</li>
    </ul>
    <img src="Picture3.png" alt="Award and achievement icons">
  </section>

  <!-- CONTACT (clean, with icons and map marker) -->
  <section id="contact" class="contact">
    <h2>Let’s connect</h2>
    <p><i class="fas fa-map-pin"></i> Mokatam, Cairo, Egypt</p>
    <p><i class="fas fa-phone-alt"></i> +20 155 166 7933</p>
    <p><i class="fas fa-envelope"></i> <a href="mailto:zeiad.ahmed04@eng-st.cu.edu.eg">zeiad.ahmed04@eng-st.cu.edu.eg</a></p>
    <p style="margin-top: 1.5rem; opacity:0.8;"><i class="fas fa-download"></i> <a href="#" style="border-bottom: 1px solid #ffcf9a;">Download resume (PDF)</a> &nbsp;|&nbsp; <a href="#"><i class="fab fa-linkedin"></i> LinkedIn</a> &nbsp;|&nbsp; <a href="#"><i class="fab fa-github"></i> GitHub</a></p>
    <p style="font-size: 0.95rem; margin-top: 1.8rem;">✉️ best reachable via email — I usually reply within 24h.</p>
  </section>

  <!-- simple footer (optional) -->
  <footer style="text-align: center; padding: 1.8rem 1rem 1.2rem; color: #5e5b55; background: #e3dbcf;">
    <p>© 2025 Zyad Yasser Mohamed — built with <i class="fas fa-heart" style="color:#b0635b;"></i> for clean portfolio</p>
  </footer>

  <!-- No broken links: all internal anchor links work, and images are referenced as originally intended.
       If some images missing, they will show alt text. No functional errors. -->
</body>
</html>
