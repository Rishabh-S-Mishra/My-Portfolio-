<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    /* Color scheme inspired by the reference */
    :root {
      --primary-bg: #282828;   /* Dark background */
      --primary-text: #f8f8f8; /* Light text */
      --accent-color: #c778dd; /* Accent color */
      --secondary-text: #c4c4c4; /* Secondary text color */
    }

    /* General styles */
    body {
      font-family: Arial, sans-serif;
      background-color: var(--primary-bg);
      color: var(--primary-text);
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      flex-direction: column;
    }

    h1, h2 {
      color: var(--accent-color);
    }

    .container {
      width: 90%;
      max-width: 800px;
      padding: 20px;
      border-radius: 10px;
      background-color: #333;
      box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
    }

    .section {
      margin-bottom: 20px;
    }

    .section p {
      color: var(--secondary-text);
    }

    .skills-list {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    .skill {
      background-color: var(--accent-color);
      color: var(--primary-bg);
      padding: 8px 12px;
      border-radius: 5px;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- About Section -->
    <div class="section">
      <h1>About Me</h1>
      <p>
        Hello! I'm a curious and passionate tech enthusiast with a huge fascination for innovation and technology, inspired by Iron Man.
        I am driven by the possibilities of the digital world and aim to push the boundaries of what's possible. My goal is to leverage my skills 
        to create impactful and meaningful projects that inspire and engage others.
      </p>
    </div>

    <!-- Career Interests Section -->
    <div class="section">
      <h2>Career Interests</h2>
      <p>
        I'm interested in:
        <ul>
          <li>Full-Stack Development</li>
          <li>Artificial Intelligence and Machine Learning</li>
          <li>Cybersecurity</li>
          <li>Data Science and Analytics</li>
        </ul>
      </p>
    </div>

    <!-- Skills Section -->
    <div class="section">
      <h2>What I’m Good At</h2>
      <div class="skills-list">
        <div class="skill">JavaScript</div>
        <div class="skill">Python</div>
        <div class="skill">HTML & CSS</div>
        <div class="skill">React</div>
        <div class="skill">Node.js</div>
        <div class="skill">Data Analysis</div>
        <div class="skill">UI/UX Design</div>
      </div>
    </div>
  </div>

  <!-- JavaScript (Optional for Interactivity) -->
  <script>
    // You can add interactive JavaScript here if needed
  </script>
</body>
</html># My-Portfolio-