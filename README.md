<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Anand Jha Portfolio</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bulma@0.9.3/css/bulma.min.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
  <style>
    body {
      font-family: 'Helvetica Neue', Arial, sans-serif;
      background-color: #f4f4f4;
      color: #333;
    }
    .hero {
      background-color: #4CAF50;
      color: white;
      padding: 50px 20px;
      text-align: center;
    }
    .section {
      padding: 30px;
    }
    .content h3 {
      color: #4CAF50;
    }
    .is-rounded {
      border-radius: 50%;
    }
    .progress {
      height: 12px;
    }
  </style>
</head>
<body>

<!-- Header Section -->
<section class="hero">
  <div class="hero-body">
    <div class="columns is-vcentered">
      <div class="column is-one-third">
        <figure class="image is-128x128">
          <img src="https://github.com/anandj25/Portfolio/blob/main/1711243457585.jpeg.jpg?raw=true" alt="Anand Jha Photo" class="is-rounded">
        </figure>
      </div>
      <div class="column">
        <h1 class="title">
          Anand Jha
        </h1>
        <p class="subtitle">
          Master of Science in Data Science | University of Michigan, Dearborn
        </p>
        <p>
          <a href="mailto:anandjha@umich.edu" class="button is-link"><i class="fas fa-envelope"></i> anandjha@umich.edu</a>
          <a href="https://www.linkedin.com/in/anandjha25" class="button is-link"><i class="fab fa-linkedin"></i> LinkedIn</a>
        </p>
      </div>
    </div>
  </div>
</section>

<!-- About Me Section -->
<section class="section">
  <div class="container content">
    <h2 class="title is-3">About Me</h2>
    <p>
      I am a highly motivated Master of Science in Data Science student at the University of Michigan Dearborn, with a GPA of 3.90. I specialize in data analytics, machine learning, cloud platforms, and ETL processes, with a passion for leveraging data to solve complex problems.
    </p>
  </div>
</section>

<!-- Technical Skills Section -->
<section class="section">
  <div class="container content">
    <h2 class="title is-3">Technical Skills</h2>
    <p><strong>Data Analysis:</strong></p>
    <progress class="progress is-success" value="90" max="100">90%</progress>
    <p><strong>Machine Learning:</strong></p>
    <progress class="progress is-warning" value="80" max="100">80%</progress>
    <p><strong>Data Visualization (Power BI, Tableau):</strong></p>
    <progress class="progress is-info" value="85" max="100">85%</progress>
  </div>
</section>

<!-- Professional Experience Section -->
<section class="section">
  <div class="container content">
    <h2 class="title is-3">Professional Experience</h2>

    <h3>Accenture – Infra Business Analyst (Bangalore, India) | Aug 2019 – July 2023</h3>
    <ul>
      <li>Achieved 100% SLA compliance and improved quality across IT Ops teams for various clients.</li>
      <li>Designed SQL-based ETL packages with SSIS, automating processes and optimizing ETL by 15%.</li>
      <li>Developed Power BI dashboards, accelerating ticket resolution by 20% with real-time insights.</li>
      <li>Implemented Python automation scripts, leading to $40k annual savings and reducing filesystem alerts by 95%.</li>
    </ul>

    <h3>PeopleClick Tech Solutions – Data Analytics Intern | Mar 2019 – Aug 2019</h3>
    <ul>
      <li>Engineered health-tracking dashboards, enhancing system reliability and performance by 15%.</li>
      <li>Applied SQL and Python machine learning libraries to foster data-driven decision-making.</li>
    </ul>
  </div>
</section>

<!-- Projects Section -->
<section class="section">
  <div class="container content">
    <h2 class="title is-3">Projects</h2>

    <h3><i class="fas fa-heartbeat"></i> Predictive Model for Heart Stroke Identification</h3>
    <p>Developed a machine learning model with a 95.2% accuracy for early diagnosis of heart stroke.</p>

    <h3><i class="fas fa-bicycle"></i> Power BI Dashboards for Bike Manufacturer</h3>
    <p>Created dashboards that optimized sales tracking and inventory management.</p>

    <h3><i class="fas fa-laptop"></i> Product Recommendation System</h3>
    <p>Processed 8 million Amazon data rows with Spark, achieving an RMSE of 0.13.</p>

    <h3><i class="fas fa-chart-line"></i> Customer Churn Prediction</h3>
    <p>Achieved 87% accuracy using Python and Tableau for telecom dataset analysis.</p>

    <h3><i class="fas fa-comments"></i> Chatbot for University of Michigan</h3>
    <p>Increased user interaction by 15% with a chatbot leveraging the Gemini API and Python.</p>
  </div>
</section>

<!-- Certifications Section -->
<section class="section">
  <div class="container content">
    <h2 class="title is-3">Certifications and Accomplishments</h2>
    <ul>
      <li>Microsoft Certified AZ-900 Professional</li>
      <li>Power BI for Business Intelligence</li>
      <li>SQL Bootcamp Certified</li>
      <li>Torch Bearer Award at Accenture</li>
      <li>Oracle Cloud Fundamentals</li>
      <li>Global Innovation Award at Accenture</li>
      <li>SPOT Award for Delivery Excellence</li>
    </ul>
  </div>
</section>

</body>
</html>
