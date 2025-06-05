<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sridhar Parshana | Portfolio</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }

    body {
      background-color: #f4f4f4;
      color: #333;
    }

    header {
      background-color: #1a1a1a;
      color: white;
      padding: 3rem 1rem;
      text-align: center;
    }

    header img {
      width: 120px;
      border-radius: 50%;
      margin-top: 1rem;
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }

    header p {
      font-size: 1.2rem;
      color: #aaa;
    }

    nav {
      background-color: #333;
      padding: 1rem;
      display: flex;
      justify-content: center;
      gap: 2rem;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 2rem 1rem;
      max-width: 1100px;
      margin: 0 auto;
    }

    .section-title {
      font-size: 2rem;
      margin-bottom: 1rem;
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
    }

    .skill {
      background-color: #e0e0e0;
      padding: 0.5rem 1rem;
      border-radius: 1rem;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
    }

    .project {
      background: white;
      padding: 1rem;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
    }

    .project img {
      max-width: 100%;
      border-radius: 10px;
    }

    .project h3 {
      margin-top: 1rem;
    }

    .project a {
      color: #007bff;
      text-decoration: none;
      margin-right: 1rem;
    }

    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      color: #aaa;
    }
  </style>
</head>

<body>
  <header>
    <h1>Sridhar Parshana</h1>
    <p>Senior Data Analyst | Power BI | SQL | Python | E-commerce Specialist</p>
    <img src="https://raw.githubusercontent.com/sridharparshana/BI-reports/myones/IMG20231008145502.jpg" alt="Sridhar Parshana">
  </header>

  <nav>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="https://github.com/sridharparshana" target="_blank">GitHub</a>
  </nav>

  <section id="skills">
    <h2 class="section-title">Skills</h2>
    <div class="skills">
      <span class="skill">Power BI</span>
      <span class="skill">SQL</span>
      <span class="skill">Python</span>
      <span class="skill">Data Visualization</span>
      <span class="skill">E-commerce Analytics</span>
      <span class="skill">ETL</span>
      <span class="skill">Inventory Forecasting</span>
    </div>
  </section>

  <section id="projects">
    <h2 class="section-title">Projects</h2>
    <div class="projects">
      <div class="project">
        <img src="https://i.imgur.com/U3vTGjX.png" alt="Sales Dashboard">
        <h3>Sales Dashboard (Power BI)</h3>
        <p>Interactive report showing product movement, stock trends, and KPIs for Amazon and Shopify.</p>
        <a href="https://github.com/sridharparshana/sales-dashboard" target="_blank">GitHub</a>
      </div>
      <div class="project">
        <img src="https://i.imgur.com/tH6L8Xt.png" alt="LinkedIn Classification">
        <h3>LinkedIn Job Classification</h3>
        <p>Classified job roles from LinkedIn listings into Engineering vs Non-Engineering using NLP and ML models.</p>
        <a href="https://github.com/sridharparshana/linkedin-classifier" target="_blank">GitHub</a>
        <a href="https://colab.research.google.com/drive/xyz" target="_blank">Open in Colab</a>
      </div>
      <div class="project">
        <img src="https://i.imgur.com/3hZ8cEm.png" alt="AWS EC2 Automation">
        <h3>AWS EC2 Shutdown Script</h3>
        <p>Automated script to shut down AWS EC2 instances using Bash, reducing cloud costs.</p>
        <a href="https://github.com/sridharparshana/aws-ec2-shutdown" target="_blank">GitHub</a>
      </div>
    </div>
  </section>

  <footer>
    Hosted on GitHub Pages — Portfolio by Sridhar Parshana
  </footer>
</body>

</html>
