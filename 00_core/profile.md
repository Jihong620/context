# Master Profile — Alan Lin (林季鴻)

> This is a **structured source-of-truth profile** for generating customized resumes.
> When targeting a specific company, use this file as the AI context and specify which aspects to emphasize.

---

## Personal Information

- **Name**: Alan Lin (林季鴻)
- **Location**: Taichung, Taiwan (open to Hsinchu and Taipei)
- **Email**: jihong620@gmail.com
- **LinkedIn**: https://www.linkedin.com/in/alan-lin-543b761b1/
- **Medium**: https://medium.com/@Alan620
- **Vocus**: https://vocus.cc/user/68689deffd89780001c6dc1d

---

## Professional Identity

- **Title**: Senior Backend Engineer / Full-Stack Engineer
- **Experience**: ~7 years backend + ~4 years frontend
- **Core Specialization**: Backend development, system design, system integration, IoT integration
- **Domain Expertise**: Smart manufacturing, Industrial IoT, ESG data platforms, AI-assisted systems

---

## Professional Summary

Full-stack engineer with a strong backend foundation and deep experience in system integration,
data pipelines, and industrial IoT. Has delivered end-to-end solutions in real-world manufacturing
environments — from data ingestion and pipeline design to frontend dashboards and visualization.
Proven track record of automating manual workflows and delivering measurable business impact.
Experienced in leading technical decisions under ambiguous, resource-constrained conditions.

---

## Technical Stack

### Backend
- **Languages**: Python (primary), Java, Go, Node.js, JavaScript
- **Frameworks**: Django, Spring Boot (Java), Gin (Go), FastAPI
- **APIs**: RESTful API, gRPC

### Frontend
- **Languages**: JavaScript, TypeScript, HTML5, CSS3
- **Frameworks/Libraries**: React, Angular

### Databases
- **Relational**: MySQL, PostgreSQL
- **NoSQL**: MongoDB, Redis
- **Skills**: Schema design, query optimization, table partitioning

### DevOps & Tools
- Git, Docker, Kubernetes
- Grafana, Power BI (data visualization & dashboarding)
- Web scraping, SMTP automation

### IoT & Protocols
- LoRa, MQTT, Modbus

### AI / Machine Learning
- **Frameworks**: TensorFlow, Keras
- **Computer Vision**: OpenCV, YOLOv3
- **Data Science**: Pandas, NumPy, Matplotlib, Seaborn

### Auth & Security
- OAuth2 + OIDC

---

## Work Experience

### ASE Group / Sipin Precision (矽品精密) — Senior Software Engineer, Facilities
**2026/03 – Present | Taichung Science Park**

#### ESG Sustainability & Facilities Data Platform (Ongoing)
- Designing and developing a digitalized ESG platform covering carbon tracking, energy management,
  and water/gas/chemical data — replacing legacy manual recording workflows.
- Integrating heterogeneous data sources (cross-system) into a centralized reporting system.
- Significantly reducing report generation cycle time; enabling real-time digital monitoring
  across multiple sites.

#### Smart Manufacturing Initiatives (Ongoing)
- **AI Chiller Energy Optimization**: AI-based energy savings for industrial chiller systems.
- **AI NOSE**: Intelligent environmental sensing system.
- **Robot Dog**: Autonomous inspection robot integration.

---

### Wistron Software (緯創軟體) — Senior Software Engineer
**2024/11 – 2026/03 | Seconded to TSMC**

#### Security Daily Report System
- Integrated KPI indicators across multiple Fabs into a unified database.
- Built full-stack architecture (frontend + backend) for internal web UI.
- Automated data collection via web scraping and delivered daily reports via SMTP.
- Synced on-premise data to the cloud; built dashboards with Grafana and Power BI.
- **Impact**: Reduced daily manual reporting time from **2–3 hours to ~10 minutes**.
  Replaced handwritten emails with intuitive charts and structured tables.

#### IoT Metal Gate Dashboard (Ongoing at transition)
- Designed backend APIs and developed frontend dashboard UI.
- Implemented multi-site role-based access control (RBAC) system.
- Provided historical data analytics: personnel flow trends, detection item statistics.
- Integrated alerting system with Email and Tphone notifications.

---

### Inxyz International (英仕國際) — Software Engineer
**2023/11 – 2024/07**

- **Web Platform Backend**: Managed service onboarding, API design, and database maintenance.
- **Chat App Backend**: Implemented OAuth2 + OIDC authentication system;
  designed MongoDB-based backend architecture.

---

### Walsin Lihwa (華新麗華) — Software / Full-Stack / Automation Engineer
**2019/11 – 2023/08 | Technical Lead for IoT & AI Projects**

#### Key Projects & Outcomes

| Project | Tech Stack | Outcome |
|---|---|---|
| Steel Coil Batching UI | Java + Angular | Reduced operation time from 1.5 hrs → 20 min |
| Advanced Intelligent Scheduling System | Python | Automated scheduling for 21 workstations |
| Crane Remote Control Access Control | Python + FaceNet | Transparent device management via facial recognition |
| Oil Drum & License Plate Recognition | Python + YOLOv3 | Converted manual handwriting into automated digital flow |
| Rolling Mill Predictive Diagnostics | Python + ML | **97% accuracy**; saved ~NT$1M/year in consumable costs |
| Steel Rod Bend Detection System | Python + C# | Significantly improved product yield rate |

---

## Key Impact Highlights (Cross-Company)

- ⏱️ Reduced manual daily reporting from **2–3 hours to ~10 minutes** (TSMC project)
- 💰 Delivered ML model with **97% accuracy**, saving ~**NT$1M/year** in manufacturing costs
- ⚙️ Reduced steel coil batching operation time from **1.5 hours to 20 minutes**
- 🤖 Built and led multiple end-to-end IoT + AI projects in industrial environments
- 🌿 Currently building ESG data platforms enabling carbon tracking and environmental compliance

---

## Education

**National Kaohsiung University of Science and Technology (國立高雄科技大學)**
- M.S., Mold Engineering Department (2017–2019)
- Thesis Focus: Image Processing & CNN Deep Learning

**National Chin-Yi University of Technology (國立勤益科技大學)**
- B.S., Mechanical Engineering (2009–2013)

---

## How to Use This Profile for Resume Customization

When asking AI to generate a customized resume, provide this file as context and specify:

1. **Target Company**: Company name, size, industry
2. **Job Description**: Paste the full JD or key requirements
3. **Emphasis**: Which projects/skills to highlight
4. **Tone**: Formal corporate / startup-friendly / technical deep-dive
5. **Language**: English / Traditional Chinese / Bilingual
6. **Format**: Narrative summary / bullet points / one-page constraint

Example prompt:
> "Using the profile in `00_core/profile.md`, generate a tailored resume for [Company].
> The JD emphasizes [X, Y, Z]. Please highlight my [specific experience] and adjust tone to [formal/startup].
> Output in English, one-page format."