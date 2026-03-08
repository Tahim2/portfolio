<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Abu Tahim Habiby | AI/ML Portfolio</title>
  <meta
    name="description"
    content="Portfolio of Abu Tahim Habiby - AI/ML Engineer focused on medical imaging, explainable AI, and applied research."
  />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;700&family=JetBrains+Mono:wght@400;500;700&display=swap"
    rel="stylesheet"
  />
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="bg-grid"></div>

  <header class="header">
    <div class="container nav">
      <a href="#home" class="logo">AbuTahim<span>.AI</span></a>

      <nav class="nav-links" id="navLinks">
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#publications">Publications</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
      </nav>

      <button class="menu-btn" id="menuBtn" aria-label="Open Menu">
        ☰
      </button>
    </div>
  </header>

  <main>
    <section class="hero section" id="home">
      <div class="container hero-grid">
        <div class="hero-text reveal">
          <p class="badge">AI/ML Engineer • Medical Imaging • XAI</p>
          <h1>Abu Tahim Habiby</h1>
          <h2>Research-Oriented AI/ML Engineer Building Practical Intelligent Systems</h2>
          <p class="hero-description">
            I work on medical imaging, explainable AI, and applied machine learning systems.
            My work combines research thinking with real implementation — from hybrid deep learning
            models to full-stack intelligent platforms.
          </p>

          <div class="hero-buttons">
            <a href="#projects" class="btn btn-primary">View My Work</a>
            <a href="assets/cv/Abu_Tahim_CV.pdf" class="btn btn-secondary" target="_blank">Download CV</a>
          </div>

          <div class="hero-links">
            <a href="https://github.com/Tahim2" target="_blank">GitHub</a>
            <a href="https://www.linkedin.com/" target="_blank">LinkedIn</a>
            <a href="mailto:habiby15-4750@diu.edu.bd">Email</a>
          </div>
        </div>

        <div class="hero-card reveal">
          <div class="profile-card">
            <div class="profile-image-wrap">
              <img src="assets/images/profile.jpg" alt="Abu Tahim Habiby" class="profile-image" />
            </div>

            <div class="profile-info">
              <h3>Current Focus</h3>
              <ul>
                <li>Medical Imaging AI</li>
                <li>Explainable Machine Learning</li>
                <li>Clinical Decision Support</li>
                <li>Research + Deployment</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="stats section">
      <div class="container stats-grid reveal">
        <div class="stat-card">
          <h3>3+</h3>
          <p>Featured Projects</p>
        </div>
        <div class="stat-card">
          <h3>3+</h3>
          <p>Research Works</p>
        </div>
        <div class="stat-card">
          <h3>Top 5</h3>
          <p>AI Competition Finalist</p>
        </div>
        <div class="stat-card">
          <h3>AI + Health</h3>
          <p>Core Domain Focus</p>
        </div>
      </div>
    </section>

    <section class="section" id="about">
      <div class="container">
        <div class="section-heading reveal">
          <p class="section-label">About Me</p>
          <h2>Who I Am</h2>
        </div>

        <div class="about-grid">
          <div class="about-card reveal">
            <p>
              I am a research-oriented Computer Science undergraduate with a strong interest in
              Artificial Intelligence, Machine Learning, medical imaging, and explainable AI.
              I enjoy building systems that are not only accurate, but also interpretable and useful
              in real-world decision support settings.
            </p>
            <p>
              My thesis work focuses on GI lesion classification using a hybrid deep learning approach.
              Alongside research, I also build practical AI applications, NLP systems, and data-driven
              full-stack platforms.
            </p>
          </div>

          <div class="about-card reveal">
            <h3>Highlights</h3>
            <ul class="highlight-list">
              <li>BSc in CSE at Daffodil International University</li>
              <li>Focused on medical imaging and explainable AI</li>
              <li>Built hybrid CNN–Transformer and ensemble models</li>
              <li>Experience with NLP, full-stack systems, and deployment</li>
              <li>Publication, preprint, and under-review research experience</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <section class="section" id="projects">
      <div class="container">
        <div class="section-heading reveal">
          <p class="section-label">Projects</p>
          <h2>Featured Work</h2>
        </div>

        <div class="projects-grid">
          <article class="project-card reveal">
            <img src="assets/images/clinfusion-net.png" alt="ClinFusion-Net Project" class="project-image" />
            <div class="project-content">
              <p class="project-tag">Thesis Project</p>
              <h3>ClinFusion-Net</h3>
              <p>
                A hybrid CNN–Transformer model for multi-class GI disease classification with
                explainability support and an interactive Hugging Face inference demo.
              </p>
              <div class="tech-stack">
                <span>Python</span>
                <span>PyTorch</span>
                <span>Medical Imaging</span>
                <span>XAI</span>
              </div>
              <div class="project-links">
                <a href="https://huggingface.co/spaces/Tahim2/ClinFusion_Net" target="_blank">Live Demo</a>
                <a href="https://github.com/Tahim2" target="_blank">GitHub</a>
              </div>
            </div>
          </article>

          <article class="project-card reveal">
            <img src="assets/images/sentiment-analysis.png" alt="Sentiment Analysis Project" class="project-image" />
            <div class="project-content">
              <p class="project-tag">NLP Project</p>
              <h3>Customer Sentiment Analysis</h3>
              <p>
                Built Amazon product review sentiment classifiers using TF-IDF, classical ML,
                and LSTM/GRU models with SHAP-based interpretability.
              </p>
              <div class="tech-stack">
                <span>Python</span>
                <span>NLP</span>
                <span>scikit-learn</span>
                <span>SHAP</span>
              </div>
              <div class="project-links">
                <a href="https://github.com/Tahim2/Sentiment-Analysis-on-Amazon-Product-Reviews" target="_blank">GitHub</a>
              </div>
            </div>
          </article>

          <article class="project-card reveal">
            <img src="assets/images/academic-hub.png" alt="Academic Hub Project" class="project-image" />
            <div class="project-content">
              <p class="project-tag">Full-Stack Platform</p>
              <h3>Academic Hub</h3>
              <p>
                A data-driven CGPA and course-management platform with Google OAuth and Google Drive
                API integration for academic productivity.
              </p>
              <div class="tech-stack">
                <span>JavaScript</span>
                <span>Full-Stack</span>
                <span>OAuth</span>
                <span>MySQL</span>
              </div>
              <div class="project-links">
                <a href="https://github.com/Tahim2/Academic-Hub" target="_blank">GitHub</a>
              </div>
            </div>
          </article>
        </div>
      </div>
    </section>

    <section class="section" id="publications">
      <div class="container">
        <div class="section-heading reveal">
          <p class="section-label">Research</p>
          <h2>Publications & Scholarly Work</h2>
        </div>

        <div class="publication-list">
          <div class="publication-card reveal">
            <h3>RXV: Interpretable RF-Stacked CNNs for Brain Tumor MRI Classification</h3>
            <p>IEEE WIECON-ECE 2025</p>
          </div>

          <div class="publication-card reveal">
            <h3>A High-Accuracy Stacking Ensemble Model for Precise Thyroid Disease Detection with SHAP and LIME Explanations</h3>
            <p>Informatics in Medicine Unlocked (Elsevier) — Manuscript Under Review</p>
          </div>

          <div class="publication-card reveal">
            <h3>An Explainable Stacking Ensemble Framework for Early Heart Attack Risk Detection</h3>
            <p>ResearchGate Preprint</p>
          </div>
        </div>
      </div>
    </section>

    <section class="section" id="skills">
      <div class="container">
        <div class="section-heading reveal">
          <p class="section-label">Skills</p>
          <h2>Technologies & Tools</h2>
        </div>

        <div class="skills-grid">
          <div class="skill-box reveal">
            <h3>Programming</h3>
            <div class="skill-tags">
              <span>Python</span>
              <span>C/C++</span>
              <span>Java</span>
            </div>
          </div>

          <div class="skill-box reveal">
            <h3>ML & Data</h3>
            <div class="skill-tags">
              <span>PyTorch</span>
              <span>TensorFlow/Keras</span>
              <span>scikit-learn</span>
              <span>pandas</span>
              <span>NumPy</span>
            </div>
          </div>

          <div class="skill-box reveal">
            <h3>Tools</h3>
            <div class="skill-tags">
              <span>Git</span>
              <span>GitHub</span>
              <span>Jupyter</span>
              <span>VS Code</span>
            </div>
          </div>

          <div class="skill-box reveal">
            <h3>Backend & DB</h3>
            <div class="skill-tags">
              <span>MySQL</span>
              <span>API Integration</span>
              <span>Google OAuth</span>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="section" id="achievements">
      <div class="container">
        <div class="section-heading reveal">
          <p class="section-label">Achievements</p>
          <h2>Recognition & Leadership</h2>
        </div>

        <div class="achievement-grid">
          <div class="achievement-card reveal">
            <h3>Top 5 Finalist</h3>
            <p>AI-FICATION 2025</p>
          </div>

          <div class="achievement-card reveal">
            <h3>Finalist</h3>
            <p>Crack Dataset Challenge 2024</p>
          </div>

          <div class="achievement-card reveal">
            <h3>Finalist</h3>
            <p>Take-Off Programming Contest 2022</p>
          </div>

          <div class="achievement-card reveal">
            <h3>Press Secretary</h3>
            <p>Daffodil AI Club</p>
          </div>
        </div>
      </div>
    </section>

    <section class="section contact-section" id="contact">
      <div class="container">
        <div class="section-heading reveal">
          <p class="section-label">Contact</p>
          <h2>Let’s Connect</h2>
        </div>

        <div class="contact-card reveal">
          <p>
            I’m interested in AI/ML research collaborations, internships, and impactful projects
            in healthcare AI, explainable systems, and applied machine learning.
          </p>

          <div class="contact-links">
            <a href="mailto:habiby15-4750@diu.edu.bd" class="btn btn-primary">Email Me</a>
            <a href="https://github.com/Tahim2" target="_blank" class="btn btn-secondary">GitHub</a>
            <a href="https://www.linkedin.com/" target="_blank" class="btn btn-secondary">LinkedIn</a>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer class="footer">
    <div class="container">
      <p>© 2026 Abu Tahim Habiby. Built with HTML, CSS, and JavaScript.</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>