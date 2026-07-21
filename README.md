# MY-PROFOLIO-PROJECT1
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Creative Portfolio</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      min-height: 100vh;
      background: #fafafa;
      color: #333;
    }
    /* Sidebar */
    aside {
      width: 220px;
      background: #222;
      color: #fff;
      padding: 30px 20px;
      position: fixed;
      height: 100%;
    }
    aside h2 {
      margin-bottom: 20px;
      font-size: 1.5em;
      border-bottom: 2px solid #444;
      padding-bottom: 10px;
    }
    aside nav a {
      display: block;
      color: #ddd;
      text-decoration: none;
      margin: 12px 0;
      transition: color 0.3s;
    }
    aside nav a:hover {
      color: #fff;
    }
    /* Main content */
    main {
      margin-left: 220px;
      padding: 40px;
      flex: 1;
    }
    .hero {
      background: linear-gradient(135deg, #6a11cb, #2575fc);
      color: #fff;
      padding: 60px;
      border-radius: 12px;
      margin-bottom: 40px;
      text-align: center;
    }
    .hero h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 1.2em;
    }
    section {
      margin-bottom: 50px;
    }
    section h2 {
      margin-bottom: 20px;
      font-size: 1.8em;
      color: #444;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.08);
      transition: transform 0.3s;
    }
    #about img {
  width: 150px;
  border-radius: 50%;
  
}

    .card:hover {
      transform: translateY(-5px);
    }
    footer {
      text-align: center;
      padding: 20px;
      color: #666;
      border-top: 1px solid #ddd;
    }
  </style>
</head>
<body>

  <aside>
    
    <section id="about">
    <img src="ACHU.jpg" alt="Your Photo">
    </section>
    <h2>D.ACHYUTH KUMAR</h2>
  </aside>

  <main>
    <div class="hero">
      <h1>Hello, I'm D.ACHYUTHKUMAR</h1>
      <p>WEB Developer & Creative Designer</p>
    </div>

    <section id="about">
      <h2>About Me</h2>
      <p>
      Hello! I'm a passionate developer skilled in HTML, CSS,PHP and JavaScript<br>
    A young frontend developer sits quietly, refining their skills and polishing small projects, while waiting for the right opportunity to showcase their talent.<br>
     Each day feels like a test of patience, but beneath the calm exterior lies a restless ambition — a determination to prove that their creativity and code can bring ideas to life.<br>
      They know that when the chance finally arrives, they'll be ready to step forward with confidence and passion. </p>
    </section>

    <section id="work">
        <h2>Projects</h2>
      <h3>PCS</h3>
      <p>PCS(PLASTIC COLLECTING SERVICES)<br>
             Experienced in organizing and managing plastic waste collection initiatives focused on sustainability and environmental impact.<br>
        Skilled in coordinating logistics for collection, segregation, and safe disposal of plastic materials.<br>
        Familiar with community outreach programs to raise awareness about recycling practices and reducing plastic pollution.<br>
        Strong commitment to eco-friendly solutions and contributing to circular economy efforts.
      
    </section>

    <section id="skills">
      <h2>Skills</h2>
      <p>HTML, CSS, JavaScript,PHP,MYSQL,Responsive Layouts</p>
    </section>
     <section id="resume">
    <h2>Resume</h2>
   <a href="achuuu resume.pdf" download>Download My Resume</a>
  </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>Email: achyuthdeva440@gmail.com</p>
      <p>Phone: +91 9000561099</p>
    </section>

    <footer>
      <p>&copy; 2026 D.ACHYUTH KUMAR. Built with passion.</p>
    </footer>
  </main>

</body>
</html>
