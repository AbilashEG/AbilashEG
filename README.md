<!-- ========================= -->
<!--   CYBERPUNK ANIMATED BANNER   -->
<!-- ========================= -->
<p align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 260" width="100%" height="220" preserveAspectRatio="xMidYMid slice">
  <defs>
    <linearGradient id="g1" x1="0" x2="1" y1="0" y2="1">
      <stop offset="0%" stop-color="#00faff" />
      <stop offset="50%" stop-color="#8a2be2" />
      <stop offset="100%" stop-color="#ff007a" />
      <animate attributeName="x1" values="0;1;0" dur="8s" repeatCount="indefinite"/>
      <animate attributeName="x2" values="1;0;1" dur="8s" repeatCount="indefinite"/>
    </linearGradient>

    <filter id="glow">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>

    <radialGradient id="node" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#ffffff"/>
      <stop offset="40%" stop-color="#7fffd4"/>
      <stop offset="100%" stop-color="#8a2be2" stop-opacity="0"/>
    </radialGradient>

    <style>
      .bg { fill: url(#g1); opacity: 0.12; }
      .grid { stroke: rgba(120,0,200,0.35); stroke-width:1.5; filter:url(#glow); }
      .node { fill: url(#node); filter:url(#glow); }
      .title { font-family: 'Segoe UI'; font-weight:700; fill:white; }
      .subtitle { font-family:'Segoe UI'; fill:#a7f0ff; font-weight:600; }
      .tag { font-family:'Segoe UI'; fill:#ffd6f0; }
    </style>
  </defs>

  <rect class="bg" x="0" y="0" width="1200" height="260" rx="10"/>

  <path class="grid" d="M60 180 C200 40, 450 40, 620 160">
    <animate attributeName="d" dur="10s" repeatCount="indefinite"
      values="M60 180 C200 40, 450 40, 620 160;
              M60 160 C240 60, 480 20, 640 150;
              M60 180 C200 40, 450 40, 620 160"/>
  </path>

  <path class="grid" d="M300 120 C460 210, 760 210, 940 120">
    <animate attributeName="d" dur="12s" repeatCount="indefinite"
      values="M300 120 C460 210, 760 210, 940 120;
              M300 140 C480 230, 760 180, 940 140;
              M300 120 C460 210, 760 210, 940 120"/>
  </path>

  <circle class="node" cx="150" cy="60" r="10">
    <animate attributeName="r" values="8;14;8" dur="3s" repeatCount="indefinite"/>
  </circle>

  <circle class="node" cx="450" cy="40" r="12">
    <animate attributeName="cy" values="40;20;40" dur="4s" repeatCount="indefinite"/>
  </circle>

  <circle class="node" cx="760" cy="180" r="10">
    <animate attributeName="r" values="8;12;8" dur="3.5s" repeatCount="indefinite"/>
  </circle>

  <g transform="translate(70,80)">
    <text class="title" x="0" y="40" font-size="48">Abilash RG</text>
    <text class="subtitle" x="0" y="80" font-size="22">Data & AI Engineer • AWS • DevOps • Cloud Automation</text>
  </g>
</svg>
</p>

---

# 👋 Hi, I'm **Abilash RG**
**Data & AI Engineer** specializing in **AWS, Cloud Automation, Generative AI, ML Engineering, and Agentic AI Systems.**  
I build **production-grade, cloud-native, automated, AI-powered platforms at scale.**

---

# 🏆 Achievements & Recognition
- **Winner — Migratapalooza Hackathon 2025** (AWS Database Modernization)
- **Attended AWS Well-Architected Partner Workshop – Bengaluru**  
  → Focus: Integrating **GenAI & Agentic AI** into WAR reviews  
- **Production Deployment of L1 AWS Assessment Bot** (EC2 + Nginx + Gunicorn + React)

---

# 🎓 Certifications
- **AWS Certified Data Engineer – Associate (DEA-C01)**  
- **AWS Certified Cloud Practitioner**

---

# 🚀 Major Projects & Deliverables

## **1️⃣ L1 AWS Assessment & Activity Bot (Full Production System)**
✔️ Built on **EC2, Nginx, Gunicorn, Flask, React**  
✔️ Automated **CloudWatch compliance checks**, multi-region scans, cost analysis  
✔️ 11 AWS Regions scanned with **cross-account role automation**  
✔️ Generated **6MB+ branded DOCX reports** (charts, diagrams, insights)  
✔️ Reduced manual 4+ hour workload to **~60 seconds end-to-end**  
✔️ Automated **CloudWatch Agent installation** for Linux, Ubuntu & Windows  
✔️ Implemented **GP2→GP3 automated cost-saving workflow** with UI + chatbot integration  

---

## **2️⃣ Generative & Agentic AI Solutions**
### **HR Interview Management System**
- Cognito auth + S3 storage + Textract Resume Parsing  
- Amazon Bedrock (DeepSeek) for **behavioral + technical question generation**  
- Stores all candidate insights in DynamoDB  
- End-to-end workflow UI + dashboard

### **Agentic AI Farm Advisor**
- Built using GenAI + AgentCore concepts  
- Automated farm insights, crop suggestions, and cost predictions  

### **Healthcare Prescription Agent**
- Configured runtime agent flow  
- Designed DynamoDB schema + Lambda gateways  
- Automates patient prescription generation

### **Movie Booking Bot**
- Bedrock Agent + API Gateway + Lambda  
- Auto-fills missing booking details (seat, time, theater)

---

## **3️⃣ Data Engineering, ML & Visualization**
### **Diabetes Prediction Engine**
- Trained XGBoost/Logistic Regression (AUC **0.9908**)  
- Deployed via **SageMaker** & Flask UI  
- 3-tier clinical risk classification model  

### **Org Chart Visualization**
- Dynamic **D3.js + SVG** tree generation  
- Auto-scaling, responsive, relationship-aware rendering

### **QuickSight Dashboards**
- Cleaned datasets via Glue DataBrew  
- Employee data analytics dashboard

---

# 🧠 Technical Skills

### **Cloud & Infra**
- EC2, Lambda, S3, CloudWatch, SSM, IAM, API Gateway  
- Multi-account infra, cross-account automation  

### **AI / ML**
- Amazon Bedrock (Agents, Guardrails, DeepSeek, Titan)  
- SageMaker, Textract, Comprehend, Rekognition  
- Python ML Stack (Pandas, NumPy, Scikit-learn, XGBoost)  

### **Frontend & Backend Dev**
- Python (Flask), React.js, Node.js  
- Nginx, Gunicorn  
- D3.js for complex graphs

### **Data Engineering**
- Glue, Athena, Redshift, QuickSight  
- ETL pipelines, cost analytics, infra scans  

### **DevOps**
- Docker, GitHub Actions, CI/CD  
- Linux, shell scripting

---

# 📊 GitHub Analytics
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=abilasheg&show_icons=true&theme=tokyonight" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=abilasheg&layout=compact&theme=tokyonight" height="150" />
</p>

---

# 🔗 Connect With Me
- 🌐 Portfolio — https://abilasheg.vercel.app  
- 🔗 LinkedIn — https://linkedin.com/in/abilash-eg-202429251  
- ✉️ Email — abilashgomathi7@gmail.com  

---

> _“Build systems that think, automate, and scale — not just code.”_

