<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=Sheema%20Shariq&fontSize=48&fontAlignY=38&animation=fadeIn&desc=BSc%20(Hons)%20Computer%20Science%20%7C%20Jamia%20Millia%20Islamia&descSize=16&descAlignY=60" alt="Sheema Shariq" width="100%" />

<a href="https://github.com/sheemashariq1">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=2F8D46&center=true&vCenter=true&width=640&lines=Building+AI-powered+apps;Exploring+ML+and+cloud+deployment;Improving+at+DSA+and+problem+solving;Open+to+internships+and+project+collabs" alt="Typing animation" />
</a>

<br />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sheema-shariq-436678366)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/SHEEMA_SHARIQ)
[![GeeksforGeeks](https://img.shields.io/badge/GeeksforGeeks-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white)](https://www.geeksforgeeks.org/profile/sheemash17x8)
![Location](https://img.shields.io/badge/New%20Delhi%2C%20IN-484F58?style=for-the-badge&logo=googlemaps&logoColor=white)
![Open to Internships](https://img.shields.io/badge/Open%20to%20Internships-238636?style=for-the-badge)

</div>

---

## 👋 About me

I am a second year BSc (Hons) Computer Science student at Jamia Millia Islamia, New Delhi. I like building full-stack apps that use LLMs, and I have been learning how to test, containerise and deploy them properly. Alongside that, I practise DSA regularly.

---

## 🚀 Featured projects

### [Exmentify](https://github.com/sheemashariq1/Exmentify) | AI-powered exam prep platform

[Live demo](https://d1vcdm3hqyivum.cloudfront.net/) · [GitHub](https://github.com/sheemashariq1/Exmentify)

> Personalised study content, structured cheat sheets and topic explanations

Uses the Gemini API with SSE streaming for real-time LLM responses. The full GATE CS syllabus is built, and other exam tracks are planned. It has flashcards, mistake diagnosis, goal tracking, Mermaid.js diagrams and client-side PDF export. Built as the final project of my IBM SkillsBuild internship.

```
FastAPI (Python)  ->  Gemini API (SSE streaming)  ->  Vanilla JS frontend
        |
Docker container  ->  AWS Elastic Beanstalk  ->  CloudFront (HTTPS)
```

<img src="https://skillicons.dev/icons?i=py,fastapi,js,html,css,docker,aws" alt="Exmentify stack" />

### [exmentify-ml](https://github.com/sheemashariq1/exmentify-ml) | Weak topic prediction for Exmentify

[Live dashboard](https://exmentify-ml.onrender.com/ml/dashboard) · [GitHub](https://github.com/sheemashariq1/exmentify-ml)

An ML layer that predicts which topics a student is weak in, trained with scikit-learn on simulated attempt data (ROC-AUC 0.70, about 67% accuracy). Predictions are served through FastAPI and deployed on Render, with a weak-topic heatmap dashboard and LangChain + Gemini explanations for each prediction.

<img src="https://skillicons.dev/icons?i=py,fastapi" alt="exmentify-ml stack" />
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini%20API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

### [MNC Management System](https://github.com/sheemashariq1/MNC_Management_System) | Full-stack employee management

[Live demo (login on request)](https://skillway-mnc.duckdns.org) · [GitHub](https://github.com/sheemashariq1/MNC_Management_System)

My Class 12 console project, rebuilt as a full-stack system with a FastAPI REST API (23 endpoints), a Streamlit dashboard and a normalised MySQL schema. It has JWT login with bcrypt hashing, role-based access (admin, HR, IT), login lockout and an audit log of every change. Covered by 178 automated tests running on GitHub Actions, containerised with Docker Compose and deployed on AWS EC2 with HTTPS.

<img src="https://skillicons.dev/icons?i=py,fastapi,mysql,docker,aws,githubactions" alt="MNC stack" />
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

### [KisanConnect](https://github.com/sheemashariq1/SIH_Project_2026) | Farmer-to-buyer agri marketplace

[Live demo](https://kisanconnect-sih.vercel.app) · [GitHub](https://github.com/sheemashariq1/SIH_Project_2026)

A team project for Smart India Hackathon 2026. A working prototype with separate farmer, buyer and admin portals in 8 Indian languages, an AI crop scan using the Gemini vision API through a serverless function, mandi price comparison, live bargaining and escrow-tracked settlement. It runs on in-memory demo data.

<img src="https://skillicons.dev/icons?i=react,ts,tailwind,vite,vercel" alt="KisanConnect stack" />

### [Python Projects](https://github.com/sheemashariq1/Python_Projects) | 100 Days of Code

Daily hands-on projects from the Udemy bootcamp, covering fundamentals, OOP, automation and web development. In progress.

---

## 💼 Experience

| Role | Organisation | Period |
|---|---|---|
| **AI/ML Intern** | IBM SkillsBuild x BharatCares (AICTE) | Aug 2026 – Sep 2026 |
| **Gen AI & Cloud Computing Intern** | IBM SkillsBuild x BharatCares (AICTE) | Jun 2026 – Jul 2026 |
| **Campus Representative** | GeeksforGeeks | Jun 2026 – Present |

**At IBM SkillsBuild**
- Built and deployed Exmentify end to end as the final internship project: FastAPI backend, Gemini streaming, Docker, AWS Elastic Beanstalk and CloudFront
- Built the ML layer for Exmentify (weak topic prediction), served through FastAPI and deployed on Render

## 🤝 Leadership and community

- Lead Organiser, HIVE Coding Society (JMI)
- Operations Co-Head, Coding Council (JMI)
- Technical Team Member, SoarJMI (JMI)

---

## 🛠️ Skills

**Languages**

<img src="https://skillicons.dev/icons?i=py,cpp,c,mysql,js,ts,html,css" alt="Languages" />

**Frameworks and libraries**

<img src="https://skillicons.dev/icons?i=fastapi,react,tailwind" alt="Frameworks" />
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)

**Tools and platforms**

<img src="https://skillicons.dev/icons?i=git,github,githubactions,vscode,docker,aws,vercel" alt="Tools" />
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

**Concepts**

`Data Structures & Algorithms` `OOP` `REST APIs` `JWT authentication` `LLM integration` `Prompt engineering`

---

## 📊 LeetCode

[![LeetCode Stats](https://leetcard.jacoblin.cool/SHEEMA_SHARIQ?theme=dark)](https://leetcode.com/u/SHEEMA_SHARIQ)

![Problems Solved](https://img.shields.io/badge/Problems%20Solved-200%2B-2F8D46?style=flat-square)
[![200 Day Badge](https://img.shields.io/badge/200%20Day%20Badge-🎉-purple?style=flat-square)](https://leetcode.com/u/SHEEMA_SHARIQ)
[![100 Day Badge](https://img.shields.io/badge/100%20Day%20Badge-🔥-orange?style=flat-square)](https://leetcode.com/u/SHEEMA_SHARIQ)
[![50 Day Badge](https://img.shields.io/badge/50%20Day%20Badge-⚡-yellow?style=flat-square)](https://leetcode.com/u/SHEEMA_SHARIQ)

---

## 📂 Repositories

| Repo | What is inside |
|---|---|
| [Exmentify](https://github.com/sheemashariq1/Exmentify) | AI exam prep platform: FastAPI, Gemini API, Docker, AWS |
| [exmentify-ml](https://github.com/sheemashariq1/exmentify-ml) | Weak topic prediction service for Exmentify |
| [MNC_Management_System](https://github.com/sheemashariq1/MNC_Management_System) | Full-stack employee management: FastAPI, Streamlit, MySQL |
| [SIH_Project_2026](https://github.com/sheemashariq1/SIH_Project_2026) | KisanConnect, Smart India Hackathon team project |
| [Python_Projects](https://github.com/sheemashariq1/Python_Projects) | Projects from the 100 Days of Code bootcamp |
| [DSA_Practice](https://github.com/sheemashariq1/DSA_Practice) | Striver's A2Z and the college DSA Sprint |
| [LeetCode-Solutions](https://github.com/sheemashariq1/LeetCode-Solutions) | Practised problems, synced with LeetHub |
| [SoarJMI-Tasks](https://github.com/sheemashariq1/SoarJMI-Tasks) | Technical projects from my time in the SoarJMI society |

---

## 🎓 Education and certifications

**Jamia Millia Islamia**, BSc (Hons) Computer Science *(2025 – Present, 2nd year)*

- IBM SkillsBuild x BharatCares ML & Applied AI Internship, certificate of training *(BHIBMML01303)*
- IBM SkillsBuild Gen AI & Cloud Computing Internship *(BHIBMAC06445)*
- NoviTech R&D, Full Stack Development and Data Analytics (30 days)
- Udemy, 100 Days of Code: The Complete Python Pro Bootcamp *(in progress)*
- DSA Sprint 2026, Coding Council JMI (6 weeks)
- GeeksforGeeks, 30-Day DSA Step-by-Step Learning Streak

---

<div align="center">

*Currently in 2nd year, learning cloud and AI, open to internships and project collabs*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=100&section=footer" alt="" width="100%" />

</div>
