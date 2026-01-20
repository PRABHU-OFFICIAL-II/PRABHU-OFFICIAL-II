<!-- Header Section -->
<h1 align="center">👋 Hey, I'm Prabhu Prasad Penthoi</h1>
<h3 align="center">Software Engineer | Informatica from Salesforce</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=PRABHU-OFFICIAL-II&label=Profile%20Views&color=blueviolet&style=for-the-badge" alt="profile views"/>
</p>

---

## 🧭 About Me

💡 **Informatica IICS Engineer** and **Full-Stack Developer** passionate about designing automation tools, system integrations, and data-driven applications.  

I specialize in:
- 🔁 **Automation Utilities** using Java, REST APIs, and Informatica Cloud.
- ☁️ **Cloud & Integration Engineering** (AWS, Azure ADLS Gen2, REST, OAuth).
- 💻 **Full-Stack Development** (React.js, Node.js, MongoDB, Next.js).
- 🧠 **AI, IoT, and Intelligent Monitoring** systems.

📍 Based in India | 🌍 Working on projects that bridge **data, automation, and intelligence**.

---

## 🧠 Tech Stack & Tools

### 💻 **Languages**
`Java` • `JavaScript (ES6+)` • `Python` • `Dart` • `C++` • `Shell Script` • `SQL`

### ⚙️ **Frameworks & Tools**
`React.js` • `Node.js / Express.js` • `Next.js` • `Spring Boot` • `Informatica IICS` • `AWS Lambda` • `Azure SDK`

### ☁️ **Cloud & DevOps**
`AWS (EC2, S3, Lambda)` • `Azure ADLS Gen2` • `GitHub Actions` • `Docker` • `OAuth 2.0` • `cURL`

### 🧱 **Databases**
`Snowflake` • `PostgreSQL` • `Oracle` • `MongoDB`

---

## 💼 Professional Experience

### 🧩 Informatica Intelligent Cloud Services (IICS) Engineer — *2023–Present*
- Built and deployed **automation utilities** for asset import/export, OAuth token refresh, and agent health monitoring.  
- Created **Cross-org migration tools** for assets across environments with progress tracking.  
- Integrated **AWS Lambda** with IICS to monitor taskflows asynchronously.  
- Developed **custom REST connectors** and utilities for platforms like Snowflake, SAP, Salesforce, and ADLS Gen2.  
- Contributed to **IICS internal enhancements**, shell scripts for alerts, and troubleshooting connectors.  
- Authored **knowledge docs and training utilities** for IICS REST APIs.

### 💻 Full-Stack Developer (Freelance & Personal Projects)
- Designed full-stack apps with **React + Node + MongoDB**.  
- Built **IoT-enabled monitoring systems** for medical data.  
- Created internal tools for **GitHub automation, SSH execution, and Excel conversions**.

---

## 🚀 Featured Projects

### 🔧 **Automation & IICS Tools**

| Project | Description | Tech Stack | Link |
|----------|--------------|------------|------|
| **IICSAssetExportUtility** | Automates export of assets from IICS via REST APIs. | Java, REST API | [Repo](https://github.com/PRABHU-OFFICIAL-II/IICSAssetExportUtility) |
| **Connect_My_Git** | Utility to access the Github properties through myJGit Libraries and test the accessibility of the Github repositories outside IDMC. | Java, REST API | [Repo](https://github.com/PRABHU-OFFICIAL-II/Connect_My_Git) |
| **Tomcat Log Parser** | Analyzes the tomcat logs for the Support Engineers to debug the Customer issue further. | Java | [Repo](https://github.com/PRABHU-OFFICIAL-II/Tomcat_Log_Parser) |
| **ODATA_SUCCESSFACTORa_OAuth** | OAuth automation and refresh management for SAP Successfactors connections involving Odta Connection functionalities. | Java | [Repo](https://github.com/PRABHU-OFFICIAL-II/ODATA_SUCCESSFACTOR) |
| **VCSPipelineMigration** | My own Product to solve the issues of the customers experiencing while trying to perform CI/CD Pipelines to Migrate Assets between Informatica orgs. | JavaScript | [Repo](https://github.com/PRABHU-OFFICIAL-II/VCSPipelineMigration) |

---

### ☁️ **Integration Utilities & API Tools**

| Project | Description | Tech Stack | Link |
|----------|--------------|------------|------|
| **SSHExecutor** | Executes remote shell commands via Java SSH. | Java, JSch | [Repo](https://github.com/PRABHU-OFFICIAL-II/SSHExecutor) |
| **SSHConnectionTester** | Lightweight tool to validate SSH connectivity and credentials. | Java | [Repo](https://github.com/PRABHU-OFFICIAL-II/SSHConnectionTester) |
| **ExcelToCSV** | Converts Excel files to CSV using Apache POI library. | Java | [Repo](https://github.com/PRABHU-OFFICIAL-II/ExcelToCSV) |
| **EncryptionOutsideIICSTest** | Custom encryption utility for secure API credential management. | Java | [Repo](https://github.com/PRABHU-OFFICIAL-II/EncryptionOutsideIICSTest) |

---

### 🌐 **Web & UI Projects**

| Project | Description | Tech Stack | Link |
|----------|--------------|------------|------|
| **iLanding** | Responsive landing page with clean UI/UX. | HTML, CSS, JS | [Repo](https://github.com/PRABHU-OFFICIAL-II/iLanding) |
| **Gp** | Modern static web project with front-end styling. | HTML, CSS, JS | [Repo](https://github.com/PRABHU-OFFICIAL-II/Gp) |
| **community_connect** | A community-driven app for local collaboration. | React, Firebase | [Repo](https://github.com/PRABHU-OFFICIAL-II/community_connect) |
| **TLSFuelEntry** | Full-stack fuel-entry management with validation & analytics. | React, Node, MongoDB | [Repo](https://github.com/PRABHU-OFFICIAL-II/TLSFuelEntry) |

---

### 📱 **Mobile & IoT Projects**

| Project | Description | Tech Stack | Link |
|----------|--------------|------------|------|
| **Ipu_recorder_WEB** | Web + Dart-based monitoring interface for IPU analytics. | Dart, Web | [Repo](https://github.com/PRABHU-OFFICIAL-II/Ipu_recorder_WEB) |
| **MeteringService-RecommendationEngine** | Smart metering system with intelligent recommendations. | Dart, ML | *(Private)* |

---

## 🧮 My Workflow (End-to-End Dev Pipeline)

💡 **Concept**  
⬇️  
🔍 **Research**  
⬇️  
⚙️ **Prototype**  
⬇️  
👨‍💻 **Build**  
⬇️  
✅ **Test & Debug**  
⬇️  
☁️ **Deploy**  
⬇️  
📊 **Monitor**  
⬇️  
🔁 **Automate**

---

## 🧩 Technical Snippet — IICS REST API Login (Java)

```java
String loginUrl = "https://dm-us.informaticacloud.com/saas/public/core/v3/login";
String payload = "{\"username\":\"user@domain.com\",\"password\":\"yourPassword\"}";

HttpURLConnection conn = (HttpURLConnection) new URL(loginUrl).openConnection();
conn.setRequestMethod("POST");
conn.setRequestProperty("Content-Type", "application/json");
conn.setDoOutput(true);

try (OutputStream os = conn.getOutputStream()) {
    os.write(payload.getBytes(StandardCharsets.UTF_8));
}

BufferedReader br = new BufferedReader(new InputStreamReader(conn.getInputStream()));
String response = br.lines().collect(Collectors.joining());
System.out.println("Login Response: " + response);
```

## 🏆 Achievements & Recognition

- ⚙️ Built **15+ automation & integration tools** for Informatica IICS.  
- ☁️ Implemented **REST API–based Taskflow Monitoring** via AWS Lambda.  
- 🧩 Created **cross-org migration utilities**, saving **100+ manual hours**.  
- 🚀 Improved **pipeline efficiency by 35%** with optimized connector logic.  
- 🧠 Published research paper on **IoT-based remote patient monitoring**.  
- 🧑‍🏫 Mentored developers on **REST V2, OAuth, and API orchestration**.

---

## 📊 GitHub Analytics

<p align="center">
  <img 
       src="https://github-readme-stats.vercel.app/api?username=PRABHU-OFFICIAL-II&show_icons=true&theme=tokyonight&cache_seconds=86400" 
       height="160px"/>
  <img 
       src="https://github-readme-streak-stats.herokuapp.com/?user=PRABHU-OFFICIAL-II&theme=tokyonight&cache_seconds=86400" 
       height="160px"/>
</p>

<p align="center">
  <img 
       src="https://github-readme-stats.vercel.app/api/top-langs/?username=PRABHU-OFFICIAL-II&layout=compact&theme=tokyonight&cache_seconds=86400" 
       height="160px"/>
</p>

---

## 🌐 Connect With Me

- [💼 LinkedIn](https://linkedin.com/in/prabhu2003)  
- [💻 GitHub Projects](https://github.com/PRABHU-OFFICIAL-II?tab=repositories)  
- [📧 Email Me](mailto:prabhulitu2003@gmail.com)

---

> 💬 “Turning complex integrations into seamless automations — one API call at a time.”  
> — *Prabhu Prasad Penthoi*
