<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sridhar's Project Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f8f9fa;
    }
    header {
      background: #343a40;
      color: white;
      padding: 20px 40px;
      text-align: center;
    }
    h1 {
      margin: 0;
      font-size: 2.5em;
    }
    .filters {
      text-align: center;
      margin: 20px 0;
    }
    .filters button {
      background: #e9ecef;
      border: none;
      padding: 10px 20px;
      margin: 5px;
      border-radius: 4px;
      cursor: pointer;
    }
    .filters button.active,
    .filters button:hover {
      background: #007bff;
      color: white;
    }
    .projects {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      padding: 20px;
    }
    .project-card {
      background: white;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      width: 300px;
      overflow: hidden;
      transition: transform 0.3s ease;
    }
    .project-card:hover {
      transform: scale(1.02);
    }
    .project-card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }
    .project-content {
      padding: 20px;
    }
    .project-content h3 {
      margin-top: 0;
    }
    .project-content p {
      color: #555;
    }
    .project-links a {
      display: inline-block;
      margin-top: 10px;
      margin-right: 10px;
      color: #007bff;
      text-decoration: none;
    }
  </style>
</head>

<body>
  <header>
    <h1>My Latest Projects</h1>
    <p>Explore my hands-on work in data analytics, ML, and visualization</p>
  </header>

  <div class="filters">
    <button class="active" onclick="filterProjects('all')">Show all</button>
    <button onclick="filterProjects('data-viz')">Data Viz</button>
    <button onclick="filterProjects('ml')">Machine Learning</button>
    <button onclick="filterProjects('web-dev')">Web Development</button>
  </div>

  <div class="projects">
    <!-- LinkedIn Job Classification Project -->
    <div class="project-card" data-category="ml">
      <img src="https://raw.githubusercontent.com/sridharparshana/python_projects/myones/linkedin_image.png" alt="LinkedIn ML" />
      <div class="project-content">
        <h3>LinkedIn Job Classification</h3>
        <p>Classified job roles from LinkedIn listings into Engineering vs Non-Engineering using NLP and ML models.</p>
        <small><i>May 2025</i></small>
        <div class="project-links">
          <a href="https://github.com/sridharparshana/python_projects/blob/myones/Linkedin_Job_Classification.ipynb" target="_blank">GitHub</a>
          <a href="https://colab.research.google.com/github/sridharparshana/python_projects/blob/myones/Linkedin_Job_Classification.ipynb" target="_blank">Open in Colab</a>
        </div>
      </div>
    </div>

    <!-- Add more projects here as needed -->
    <!-- Example Placeholder -->
    <div class="project-card" data-category="data-viz">
      <img src="https://raw.githubusercontent.com/sridharparshana/assets/main/project_images/powerbi_dashboard.png" alt="Dashboard" />
      <div class="project-content">
        <h3>Sales Dashboard (Power BI)</h3>
        <p>Interactive report showing product movement, stock trends, and KPIs for Amazon and Shopify.</p>
        <small><i>Apr 2025</i></small>
        <div class="project-links">
          <a href="https://github.com/sridharparshana/bi_dashboards" target="_blank">GitHub</a>
        </div>
      </div>
    </div>

  </div>

  <script>
    function filterProjects(category) {
      const buttons = document.querySelectorAll('.filters button');
      buttons.forEach(btn => btn.classList.remove('active'));
      event.target.classList.add('active');

      const cards = document.querySelectorAll('.project-card');
      cards.forEach(card => {
        if (category === 'all' || card.getAttribute('data-category') === category) {
          card.style.display = 'block';
        } else {
          card.style.display = 'none';
        }
      });
    }
  </script>
</body>

</html>
