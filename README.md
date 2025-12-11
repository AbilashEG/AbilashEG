<p align="center">
<svg width="100%" height="260" viewBox="0 0 1200 260" xmlns="http://www.w3.org/2000/svg">

  <defs>
    <!-- Glow Filter -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- Node Burst Gradient -->
    <radialGradient id="nodeGrad" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#ffffff"/>
      <stop offset="40%" stop-color="#7fffd4"/>
      <stop offset="100%" stop-color="#8a2be2" stop-opacity="0"/>
    </radialGradient>

    <!-- Cyberpunk Background -->
    <linearGradient id="bgGrad" x1="0" x2="1" y1="0" y2="1">
      <stop offset="0%" stop-color="#0a0014"/>
      <stop offset="100%" stop-color="#140031"/>
    </linearGradient>
  </defs>

  <!-- Background -->
  <rect width="1200" height="260" fill="url(#bgGrad)"/>

  <!-- ANIMATED NODES -->
  <g filter="url(#glow)">
    <circle cx="150" cy="80" r="14" fill="url(#nodeGrad)">
      <animate attributeName="r" values="12;20;12" dur="3.8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="320" cy="170" r="10" fill="url(#nodeGrad)">
      <animate attributeName="r" values="10;18;10" dur="4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="540" cy="90" r="16" fill="url(#nodeGrad)">
      <animate attributeName="r" values="16;26;16" dur="3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="720" cy="140" r="13" fill="url(#nodeGrad)">
      <animate attributeName="r" values="13;23;13" dur="3.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="900" cy="100" r="18" fill="url(#nodeGrad)">
      <animate attributeName="r" values="18;28;18" dur="3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1050" cy="160" r="12" fill="url(#nodeGrad)">
      <animate attributeName="r" values="12;22;12" dur="4s" repeatCount="indefinite"/>
    </circle>

    <!-- Extra cyberpunk nodes -->
    <circle cx="250" cy="210" r="8" fill="url(#nodeGrad)">
      <animate attributeName="r" values="8;16;8" dur="4.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="450" cy="200" r="10" fill="url(#nodeGrad)">
      <animate attributeName="r" values="10;20;10" dur="4.2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="650" cy="210" r="14" fill="url(#nodeGrad)">
      <animate attributeName="r" values="14;24;14" dur="3.2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="850" cy="190" r="9" fill="url(#nodeGrad)">
      <animate attributeName="r" values="9;17;9" dur="4s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- CONNECTING CYBER LINES -->
  <g stroke="#a754ff" stroke-width="2" opacity="0.6" filter="url(#glow)">
    <line x1="150" x2="450" y1="80" y2="200">
      <animate attributeName="opacity" values="0.2;1;0.2" dur="4s" repeatCount="indefinite"/>
    </line>
    <line x1="450" x2="850" y1="200" y2="190">
      <animate attributeName="opacity" values="1;0.3;1" dur="5s" repeatCount="indefinite"/>
    </line>
    <line x1="900" x2="1050" y1="100" y2="160">
      <animate attributeName="opacity" values="0.3;1;0.3" dur="3.8s" repeatCount="indefinite"/>
    </line>
  </g>

  <!-- NAME + TITLE -->
  <text x="50%" y="125" text-anchor="middle" font-size="48" fill="#ffffff" font-family="Segoe UI" filter="url(#glow)">
    ABILASH RG
  </text>
  <text x="50%" y="170" text-anchor="middle" font-size="26" fill="#7fffd4" font-family="Segoe UI" filter="url(#glow)">
    DATA & AI ENGINEER
  </text>

</svg>
</p>

---

# 🧠 About Me
Data & AI Engineer with hands-on experience building real-time automation systems, generative AI platforms, agentic workflows, ML deployments, and production-grade applications using AWS cloud.

---

# 🚀 Key Projects & Deliverables

## **1️⃣ L1 AWS Assessment & Activity Bot (Production)**
- EC2 + Flask + React + Nginx + Gunicorn  
- Reduced manual assessment time **4+ hours → 60 seconds**  
- Multi-account scanning across **11 AWS regions**  
- Automated CloudWatch Agent installation for Linux/Windows/Ubuntu (SSM)  
- 3-month cost analysis (Cost Explorer API)  
- GP2 → GP3 automation  
- Generates **6MB+ DOCX reports** (Matplotlib charts + diagrams)

---

## **2️⃣ Generative & Agentic AI Solutions**

### **HR Interview Management System**
- Cognito auth  
- Textract parsing  
- Bedrock DeepSeek questions  
- DynamoDB storage  
- Dashboard integration  

### **Agentic AI Farm Advisor**  
- AgentCore concepts  
- Backend reasoning chain  

### **Healthcare Agent**  
- Prescription automation  
- DynamoDB + API Gateway  

### **Movie Booking Bot**  
- Bedrock Agent  
- Auto seat/time/theater filling  

---

## **3️⃣ ML & Visualization**
- **Diabetes Model** (XGBoost + Logistic Regression)  
  - 94.5% accuracy, AUC 0.9908  
  - SageMaker deployment  

- **D3.js Org Chart**  
  - Dynamic auto-layout  

- **QuickSight Dashboards**  
  - DataBrew ETL pipelines  

---

# 🧩 Tech Stack

### ☁ Cloud  
EC2, Lambda, S3, SSM, IAM, CloudWatch, API Gateway, DynamoDB  

### 🤖 AI  
Bedrock Agents, DeepSeek, SageMaker, Textract, Comprehend, Rekognition  

### 🗄 Data  
Glue, Athena, Redshift, QuickSight, IoT Core, Kinesis  

### 🛠 Dev  
Python, Flask, Node.js, React.js, Docker, Nginx, D3.js  

---

# 🏆 Achievements & Certifications
- 🥇 **Winner — Migratapalooza Hackathon 2025**  
- 🎓 **AWS Data Engineer Associate**  
- 🎓 **AWS Cloud Practitioner**  
- 🏛 **AWS Well-Architected Partner Workshop**  

---

<p align="center">⚡ Cyberpunk Neural-Network Powered README ⚡</p>
