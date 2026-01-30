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


<img width="1264" height="605" alt="1st launch large ec2 with 30GB" src="https://github.com/user-attachments/assets/1d87be7f-beda-4acc-bd37-10155d764d3e" />




<img width="1238" height="672" alt="2build apply pipeline" src="https://github.com/user-attachments/assets/cd962f8b-05f1-4e6a-993e-ff7bf5c8d805" />

<img width="1262" height="553" alt="3 eks is building" src="https://github.com/user-attachments/assets/994830b2-e0ca-44ff-9178-94d47b8493ec" />

<img width="1271" height="677" alt="pipeline pic on own repo" src="https://github.com/user-attachments/assets/6bea8fc8-0622-4a1a-8ace-4e5e80dd966e" />

<img width="1246" height="674" alt="pipeline view" src="https://github.com/user-attachments/assets/4743e167-1b61-4bf7-9ae6-827721e97928" />

<img width="1243" height="670" alt="5 pileline success" src="https://github.com/user-attachments/assets/f831bfc5-5ca4-4b1c-bd4b-a3764e88fe80" />


<img width="1261" height="682" alt="9  sonarq  loginned" src="https://github.com/user-attachments/assets/4f702565-357b-4471-9c54-304625a7c994" />
<img width="1232" height="680" alt="7 sonar admin login" src="https://github.com/user-attachments/assets/1cd979e9-1f2c-4760-b036-2ce4b7d1a728" />
<img width="1264" height="726" alt="6 sonarqube instlaled" src="https://github.com/user-attachments/assets/aadfd5cb-e950-4d4b-83fb-2bb85a7425f9" />

<img width="1247" height="675" alt="11 installed grafana" src="https://github.com/user-attachments/assets/0e27a1c7-36ca-4c19-9f15-e87aa28bc9f9" />



<img width="1251" height="690" alt="34 command srun on mobaxter" src="https://github.com/user-attachments/assets/bc3b4497-3dfb-4f96-bbe6-85144ea4a480" />
<img width="1241" height="660" alt="13 setup graphan" src="https://github.com/user-attachments/assets/eef89ba4-dc3e-48b0-8a5e-068c058c045f" />

<img width="1260" height="690" alt="16 grafan for jenkings" src="https://github.com/user-attachments/assets/e1e6b8e5-8c7d-4d63-bfd1-f0cab560e283" />
<img width="1226" height="667" alt="19 sonar quality gat" src="https://github.com/user-attachments/assets/2942dcb9-14bd-4e20-ba9c-610bd689c173" />
<img width="1247" height="667" alt="17 installing plugins" src="https://github.com/user-attachments/assets/f19eba74-b881-4b93-89cf-15a63bcad9b3" />

<img width="1222" height="655" alt="pipeline working" src="https://github.com/user-attachments/assets/aeea5be9-a0f8-4343-9d03-1a5068d0da2e" />
<img width="1195" height="630" alt="full pipeline" src="https://github.com/user-attachments/assets/1c3749a5-a37a-4879-9a90-2dd8d23db1f3" />
<img width="1236" height="637" alt="22 pipeline sucs" src="https://github.com/user-attachments/assets/0518dbee-71b5-42b0-af10-9a612b58ea2a" />
<img width="1247" height="675" alt="11 installed grafana" src="https://github.com/user-attachments/assets/c63062e2-66b7-46c9-9fec-aba2004dc455" />




<img width="1262" height="697" alt="cluster eks created" src="https://github.com/user-attachments/assets/8a0f74a8-3a7f-452c-af49-fca53f804fdf" />
<img width="1222" height="620" alt="Capture" src="https://github.com/user-attachments/assets/5a3945b1-bfed-4998-94d8-b5f195e96aac" />
<img width="1272" height="616" alt="buil7" src="https://github.com/user-attachments/assets/94949e2d-b805-4fd5-a188-282594454a85" />
<img width="1250" height="674" alt="all done" src="https://github.com/user-attachments/assets/a639fd95-75c6-4d8e-8f42-f9f9fccf7b59" />


<img width="1232" height="622" alt="fggf" src="https://github.com/user-attachments/assets/bfbfc436-beb8-4576-9dbd-ed49a1a4bf2e" />
<img width="1253" height="669" alt="eks pipeline" src="https://github.com/user-attachments/assets/5b496949-231f-4e2e-a19f-1a440182a929" />
<img width="1255" height="598" alt="ec2 instance" src="https://github.com/user-attachments/assets/67c0720b-5b66-4bb6-8e05-dc70f3f4522e" />
<img width="1221" height="664" alt="dfdf" src="https://github.com/user-attachments/assets/bf34f1ea-376d-4348-942f-dc94e5987ba0" />

<img width="1247" height="642" alt="kube output" src="https://github.com/user-attachments/assets/3888d5e4-6b75-49f9-bcd5-579cef42df38" />
<img width="1240" height="658" alt="jenkis pipeline" src="https://github.com/user-attachments/assets/ca9a8f81-42ff-4b7c-ba0b-fef234fb7d51" />
<img width="1249" height="679" alt="jenkints isnta" src="https://github.com/user-attachments/assets/7c333be6-5832-45b0-bc03-8a3252a149ec" />
<img width="1279" height="693" alt="jenkinst" src="https://github.com/user-attachments/assets/2fe6c536-d0db-41b9-bea4-1694ecae9fe1" />
<img width="1246" height="665" alt="full fledz pipelein" src="https://github.com/user-attachments/assets/89729ce5-69a4-47a0-a691-5480c5df3805" />
<img width="1228" height="666" alt="for quality gates" src="https://github.com/user-attachments/assets/b43d2c7b-a839-4ff0-8cfe-10c04ad4fc8b" />


<img width="1261" height="671" alt="piple concsol" src="https://github.com/user-attachments/assets/f4134d2f-dcdc-4cb4-8ca6-d75e48871f3b" />
<img width="1248" height="695" alt="setup email notif" src="https://github.com/user-attachments/assets/28c1fde9-ceeb-41b2-ab15-e87abc73c085" />
<img width="1247" height="672" alt="pushed on docker" src="https://github.com/user-attachments/assets/df3159c7-d372-422f-8e7a-6964c58ac28c" />
<img width="1232" height="671" alt="ppeline done" src="https://github.com/user-attachments/assets/d9688194-0cc6-4579-93ac-f5b9b880ecd5" />


<img width="1259" height="685" alt="parminde pipel" src="https://github.com/user-attachments/assets/2af7ef51-aca0-4896-887d-a3a99b9dfbc7" />
<img width="1234" height="670" alt="sonarqube dashbo" src="https://github.com/user-attachments/assets/b3dff025-848f-4fa2-82ed-a319c3608f59" />
<img width="48%" alt="sonar token" src="https://github.com/user-attachments/assets/7b950afc-6bef-45a7-9d53-51458a1b9d43" />
<img width="48%" alt="sonar par" src="https://github.com/user-attachments/assets/ef248587-43f9-421a-b575-3fbac63dbcc9" />








<img width="1268" height="641" alt="netflic output" src="https://github.com/user-attachments/assets/4317502d-b611-4848-9474-007c37fd72ff" />



























