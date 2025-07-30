<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Abhishek Upadhyay | AI Engineer & Data Scientist</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"/>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #1e1e2f, #2e2e48);
      color: #fff;
      text-align: center;
      overflow-x: hidden;
    }
    .hero {
      padding: 50px 20px;
    }
    .hero img {
      width: 160px;
      border-radius: 50%;
      border: 5px solid #00ffff;
      box-shadow: 0 0 30px #00ffff;
    }
    .hero h1 {
      font-size: 2.5rem;
      margin: 20px 0 10px;
    }
    .hero h3 {
      color: #aaa;
      font-weight: normal;
      margin-bottom: 30px;
    }
    .tech-stack, .contact, .projects {
      padding: 30px 20px;
    }
    .badges img {
      margin: 5px;
    }
    .typing {
      color: #00ffff;
      font-weight: bold;
      height: 30px;
    }
    .button {
      background: #00ffff;
      color: #000;
      padding: 10px 20px;
      border-radius: 10px;
      font-weight: bold;
      text-decoration: none;
      transition: background 0.3s ease;
    }
    .button:hover {
      background: #00cccc;
    }
    footer {
      margin: 40px 0 10px;
      color: #777;
    }
  </style>
</head>
<body>
  <section class="hero">
    <img src="https://avatars.githubusercontent.com/u/113229960?v=4" alt="Abhishek Upadhyay" />
    <h1><span class="typing" id="typing"></span></h1>
    <h3>🚀 AI | ML | GenAI | Full Stack | Data Science Enthusiast</h3>
    <p><a class="button" href="mailto:abhishekupadhyay9336@gmail.com">Hire Me</a></p>
  </section>

  <section class="tech-stack">
    <h2>🧠 Tech Stack</h2>
    <div class="badges">
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
      <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
      <img src="https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
      <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" />
      <img src="https://img.shields.io/badge/Pinecone-7A42F4?style=for-the-badge&logo=data&logoColor=white" />
      <img src="https://img.shields.io/badge/HuggingFace-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black" />
      <img src="https://img.shields.io/badge/LangChain-4CAF50?style=for-the-badge&logo=langchain&logoColor=white" />
    </div>
  </section>

  <section class="contact">
    <h2>🔗 Connect With Me</h2>
    <p>
      <a href="https://www.linkedin.com/in/abhishek-upadhyay-35b183259/" class="button">LinkedIn</a>
      <a href="https://github.com/Abhishek4209" class="button">GitHub</a>
    </p>
  </section>

  <footer>
    <p>&copy; 2025 Abhishek Upadhyay. All rights reserved.</p>
  </footer>

  <script>
    const words = ["Abhishek Upadhyay", "Data Scientist", "AI Engineer", "Full Stack Developer"];
    let i = 0, timer;
    function typingEffect() {
      let word = words[i].split("");
      let loopTyping = function () {
        if (word.length > 0) {
          document.getElementById("typing").innerHTML += word.shift();
        } else {
          deletingEffect();
          return;
        }
        timer = setTimeout(loopTyping, 150);
      };
      loopTyping();
    }
    function deletingEffect() {
      let word = words[i].split("");
      let loopDeleting = function () {
        if (word.length > 0) {
          word.pop();
          document.getElementById("typing").innerHTML = word.join("");
        } else {
          i = (i + 1) % words.length;
          typingEffect();
          return;
        }
        timer = setTimeout(loopDeleting, 80);
      };
      loopDeleting();
    }
    typingEffect();
  </script>
</body>
</html>
