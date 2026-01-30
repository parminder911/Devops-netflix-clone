<!-- ✅ README.md (Copy-Paste Friendly for GitHub) -->
<!-- Netflix Clone DevSecOps CI/CD Project by Parminderjit Singh -->

<h1 align="center">🎬 Netflix Clone DevSecOps CI/CD Pipeline 🚀</h1>

<p align="center">
  <b>End-to-End DevSecOps Pipeline using Jenkins + SonarQube + Trivy + Docker + Kubernetes + Prometheus + Grafana</b>
</p>

<p align="center">
  <img alt="DevSecOps" src="https://img.shields.io/badge/DevSecOps-CI%2FCD-blue" />
  <img alt="AWS" src="https://img.shields.io/badge/AWS-Cloud-orange" />
  <img alt="Jenkins" src="https://img.shields.io/badge/Jenkins-Automation-red" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-Container-blue" />
  <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-Orchestration-blueviolet" />
  <img alt="Monitoring" src="https://img.shields.io/badge/Monitoring-Prometheus%20%26%20Grafana-success" />
</p>

<hr />

<h2>📌 Project Overview</h2>

<p>
This project demonstrates a complete <b>DevSecOps CI/CD pipeline</b> for a <b>Netflix Clone</b> application.
It automates the full process from code checkout → build → testing → security scanning → docker build & push →
deployment → monitoring.
</p>

<p>
The goal of this project is to show how modern companies deploy applications securely with
<b>CI/CD automation</b>, <b>security scanning</b> and <b>real-time monitoring</b>.
</p>

<hr />

<h2>🎯 Key Highlights</h2>

<ul>
  <li>✅ Automated CI/CD pipeline using <b>Jenkins</b></li>
  <li>✅ Code Quality analysis using <b>SonarQube</b> + Quality Gate</li>
  <li>✅ Security scanning using <b>Trivy</b> (Filesystem + Docker Image vulnerabilities)</li>
  <li>✅ Containerization using <b>Docker</b></li>
  <li>✅ Docker image pushed to <b>DockerHub</b></li>
  <li>✅ Deployment on <b>Docker container</b> and <b>Kubernetes cluster</b></li>
  <li>✅ Monitoring setup with <b>Prometheus</b> and <b>Grafana</b></li>
</ul>

<hr />

<h2>🛠️ Tools & Technologies Used</h2>

<ul>
  <li><b>AWS EC2</b> – Hosting Jenkins, Docker, SonarQube, Prometheus, Grafana</li>
  <li><b>Jenkins</b> – CI/CD automation pipeline</li>
  <li><b>SonarQube</b> – Static code analysis & Quality Gate</li>
  <li><b>Trivy</b> – Security scanning (FS + Image scan)</li>
  <li><b>Docker</b> – Build & run application container</li>
  <li><b>DockerHub</b> – Container image registry</li>
  <li><b>Kubernetes</b> – Deploy application using deployment & service manifests</li>
  <li><b>Prometheus</b> – Metrics monitoring (Jenkins metrics integration)</li>
  <li><b>Grafana</b> – Dashboard visualization & analytics</li>
</ul>

<hr />

<h2>🏗️ CI/CD Pipeline Workflow</h2>

<ol>
  <li><b>Checkout Source Code</b> from GitHub</li>
  <li><b>Install Dependencies</b> (Node.js + npm)</li>
  <li><b>SonarQube Analysis</b> (Code quality + security)</li>
  <li><b>Quality Gate Check</b></li>
  <li><b>Trivy FS Scan</b> (source code security scan)</li>
  <li><b>Docker Build</b> with TMDB API key</li>
  <li><b>Docker Push</b> to DockerHub</li>
  <li><b>Trivy Image Scan</b> (container vulnerability scan)</li>
  <li><b>Deploy App</b> (Docker container + Kubernetes deployment)</li>
  <li><b>Monitoring</b> using Prometheus + Grafana</li>
</ol>

<hr />

<h2>📊 Monitoring Setup (Prometheus + Grafana)</h2>

<ul>
  <li>Prometheus scrapes Jenkins metrics endpoint: <b>/prometheus</b></li>
  <li>Grafana shows Jenkins performance dashboards</li>
</ul>

<p>
<b>Grafana URL:</b> <code>http://&lt;prometheus-server-ip&gt;:3000</code><br />
<b>Prometheus URL:</b> <code>http://&lt;prometheus-server-ip&gt;:9090</code>
</p>

<hr />

<h2>🔐 Security & Quality (DevSecOps)</h2>

<ul>
  <li><b>SonarQube</b> ensures code quality, detects vulnerabilities and code smells</li>
  <li><b>Trivy FS Scan</b> scans dependencies and project files</li>
  <li><b>Trivy Image Scan</b> scans container for vulnerabilities</li>
</ul>

<hr />

<h2>📌 Jenkins Credentials Used</h2>

<ul>
  <li><b>sonar-token</b> – SonarQube authentication</li>
  <li><b>docker</b> – DockerHub credentials (<b>parminderj98</b>)</li>
  <li><b>k8s</b> – Kubernetes kubeconfig credential</li>
</ul>

<hr />

<h2>🧪 API Key Used</h2>

<p>
This app uses TMDB API to fetch movies data.
</p>

<ul>
  <li><b>TMDB API Key:</b> <code>541c45c0b777545gd12e2be08acf53c</code></li>
</ul>

<hr />

<h2>💡 What I Learned</h2>

<ul>
  <li>How real-world CI/CD pipelines are built using Jenkins</li>
  <li>Implementing DevSecOps practices in pipeline</li>
  <li>Handling pipeline failures and debugging issues (Docker version mismatch, networking, kubectl DNS errors)</li>
  <li>Monitoring Jenkins performance using Prometheus and Grafana dashboards</li>
  <li>Docker deployment & Kubernetes deployment automation</li>
</ul>

<hr />

<h2>👨‍💻 Author</h2>

<p>
<b>Parminderjit Singh</b><br />
📍 Ludhiana, India<br />
🔗 LinkedIn:
<a href="https://www.linkedin.com/in/parminderjit/" target="_blank">
  https://www.linkedin.com/in/parminderjit/
</a>
</p>

<hr />

<h2>⭐ Support</h2>

<p>
If you found this project helpful, please consider giving it a ⭐ on GitHub!
</p>





