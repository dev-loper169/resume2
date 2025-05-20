<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Aryan Raj - Resume</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Roboto', sans-serif;
      background: linear-gradient(to right, #e0f7fa, #ffffff);
      color: #343a40;
      line-height: 1.6;
    }

    .resume-container {
      max-width: 1000px;
      margin: 50px auto;
      background: #fff;
      border-radius: 20px;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
      overflow: hidden;
      display: flex;
      flex-wrap: wrap;
    }

    .top-heading {
      width: 100%;
      text-align: center;
      background: #0d6efd;
      color: white;
      padding: 20px 0;
      font-size: 1.8em;
      font-weight: bold;
      letter-spacing: 1px;
    }

    .left-column {
      width: 65%;
      padding: 40px;
    }

    .right-column {
      width: 35%;
      background: #f1f3f5;
      text-align: center;
      padding: 40px;
    }

    .profile-pic {
      width: 140px;
      height: 140px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #0d6efd;
      margin-bottom: 20px;
    }

    h1 {
      font-size: 2em;
      color: #212529;
    }

    h2 {
      font-size: 1.1em;
      color: #495057;
      margin-bottom: 20px;
    }

    .contact p {
      font-size: 0.95em;
      margin: 12px 0;
      color: #495057;
    }

    .contact i {
      color: #0d6efd;
      margin-right: 10px;
    }

    .summary p {
      margin-bottom: 25px;
      font-size: 1em;
      color: #495057;
    }

    .section {
      margin-bottom: 35px;
    }

    .section h3 {
      font-size: 1.3em;
      color: #0d6efd;
      margin-bottom: 12px;
      border-bottom: 2px solid #dee2e6;
      padding-bottom: 6px;
    }

    .section ul {
      margin-left: 20px;
      list-style-type: disc;
    }

    .section ul li {
      margin-bottom: 10px;
    }

    @media screen and (max-width: 768px) {
      .resume-container {
        flex-direction: column;
      }

      .left-column, .right-column {
        width: 100%;
        padding: 20px;
      }

      .left-column {
        text-align: left;
      }
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    a:hover {
      color: #0a58ca;
    }
  </style>
</head>
<body>
  <div class="top-heading">Aryan Raj – Computer Science Resume</div>

  <div class="resume-container">
    <div class="left-column">
      <div class="summary">
        <p><strong>Aryan Raj</strong> is a passionate and motivated first-year Computer Science Engineering student with a growing understanding of web technologies. Currently learning C++ and HTML, eager to build responsive web apps and collaborate on open-source challenges.</p>
      </div>

      <div class="section">
        <h3>Experience</h3>
        <p><strong>Mar 2025 – Apr 2025</strong><br />
        <strong>Self-Initiated Projects</strong></p>
        <ul>
          <li>Developed a personal portfolio website using HTML, CSS, and JavaScript.</li>
          <li>Contributed to open-source repositories focused on front-end development.</li>
        </ul>
      </div>

      <div class="section">
        <h3>Education</h3>
        <p><strong>2024 – Present</strong><br />
        Computer Science Student<br />
        Government Polytechnic, Jagannathpur, Jharkhand, India</p>
      </div>

      <div class="section">
        <h3>Skills</h3>
        <ul>
          <li>HTML/CSS</li>
          <li>JavaScript Basics</li>
        </ul>
      </div>
    </div>

    <div class="right-column">
      <img src="n.jpg" alt="Profile photo of Aryan Raj" class="profile-pic" onerror="this.src='default-profile.jpg'">
      <h1>Aryan Raj</h1>
      <h2>CS Engineering Student</h2>
      <div class="contact">
        <p><i class="fas fa-phone-alt"></i><a href="tel:+919263096611">+91 92630 96611</a></p>
        <p><i class="fas fa-envelope"></i><a href="mailto:aryan991920@gmail.com">aryan991920@gmail.com</a></p>
        <p><i class="fas fa-map-marker-alt"></i>Jharkhand, India</p>
      </div>
    </div>
  </div>
</body>
</html>
