<!-- Add this inside your GitHub Profile README.md file -->

<!-- AOS for scroll animations -->
<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>

<!-- VanillaTilt for 3D card tilt effect -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/vanilla-tilt/1.7.0/vanilla-tilt.min.js"></script>

<style>
  .skill-section {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
    margin-bottom: 40px;
  }

  .skill-card {
    background: #0d1117;
    color: #c9d1d9;
    border: 1px solid #30363d;
    border-radius: 12px;
    padding: 20px;
    width: 220px;
    text-align: center;
    box-shadow: 0 0 10px #58a6ff50;
    transition: 0.3s ease;
  }

  .skill-card:hover {
    transform: translateY(-5px);
  }

  .section-title {
    color: #58a6ff;
    font-size: 1.5rem;
    margin: 20px 0;
    text-align: center;
  }
</style>

<!-- Section Title -->
<h2 class="section-title">🧠 Data Science Tools</h2>
<div class="skill-section">
  <div class="skill-card" data-aos="fade-up" data-tilt>Python</div>
  <div class="skill-card" data-aos="fade-up" data-tilt>Pandas</div>
  <div class="skill-card" data-aos="fade-up" data-tilt>Numpy</div>
  <div class="skill-card" data-aos="fade-up" data-tilt>Matplotlib</div>
  <div class="skill-card" data-aos="fade-up" data-tilt>Seaborn</div>
  <div class="skill-card" data-aos="fade-up" data-tilt>Scikit-learn</div>
  <div class="skill-card" data-aos="fade-up" data-tilt>Statsmodels</div>
  <div class="skill-card" data-aos="fade-up" data-tilt>Power BI</div>
  <div class="skill-card" data-aos="fade-up" data-tilt>Tableau</div>
</div>

<h2 class="section-title">🤖 Machine Learning & Deep Learning</h2>
<div class="skill-section">
  <div class="skill-card" data-aos="zoom-in" data-tilt>Linear Regression</div>
  <div class="skill-card" data-aos="zoom-in" data-tilt>Decision Tree</div>
  <div class="skill-card" data-aos="zoom-in" data-tilt>XGBoost</div>
  <div class="skill-card" data-aos="zoom-in" data-tilt>Random Forest</div>
  <div class="skill-card" data-aos="zoom-in" data-tilt>Neural Networks</div>
  <div class="skill-card" data-aos="zoom-in" data-tilt>TensorFlow</div>
  <div class="skill-card" data-aos="zoom-in" data-tilt>Keras</div>
  <div class="skill-card" data-aos="zoom-in" data-tilt>OpenCV</div>
</div>

<h2 class="section-title">📚 Natural Language Processing</h2>
<div class="skill-section">
  <div class="skill-card" data-aos="fade-right" data-tilt>NLP</div>
  <div class="skill-card" data-aos="fade-right" data-tilt>Spacy</div>
  <div class="skill-card" data-aos="fade-right" data-tilt>Tokenization</div>
  <div class="skill-card" data-aos="fade-right" data-tilt>Text Summarization</div>
  <div class="skill-card" data-aos="fade-right" data-tilt>Translation</div>
</div>

<h2 class="section-title">🔧 MLOps & Deployment</h2>
<div class="skill-section">
  <div class="skill-card" data-aos="fade-left" data-tilt>Flask</div>
  <div class="skill-card" data-aos="fade-left" data-tilt>Docker</div>
  <div class="skill-card" data-aos="fade-left" data-tilt>Git</div>
  <div class="skill-card" data-aos="fade-left" data-tilt>GitHub Actions</div>
  <div class="skill-card" data-aos="fade-left" data-tilt>Streamlit</div>
  <div class="skill-card" data-aos="fade-left" data-tilt>FastAPI</div>
</div>

<h2 class="section-title">🌐 Web & Full Stack</h2>
<div class="skill-section">
  <div class="skill-card" data-aos="flip-left" data-tilt>HTML</div>
  <div class="skill-card" data-aos="flip-left" data-tilt>CSS</div>
  <div class="skill-card" data-aos="flip-left" data-tilt>JavaScript</div>
  <div class="skill-card" data-aos="flip-left" data-tilt>React.js</div>
  <div class="skill-card" data-aos="flip-left" data-tilt>Node.js</div>
  <div class="skill-card" data-aos="flip-left" data-tilt>MongoDB</div>
</div>

<script>
  AOS.init(); // Initialize AOS
  VanillaTilt.init(document.querySelectorAll("[data-tilt]"), {
    max: 15,
    speed: 400,
    glare: true,
    "max-glare": 0.2,
  });
</script>
