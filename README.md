<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=250&text=Hargun%20Singh&fontAlign=50&fontAlignY=40&color=gradient" />

<h1 align="center">Hi, I'm Hargun 👋</h1>
<h3 align="center">Backend Engineer • Distributed Systems</h3>

<p align="center">
  I build production-grade backends — <b>IAM systems</b>, <b>permissioned blockchain infrastructure</b>, and <b>ML-based anomaly detection</b>.<br/>
  Recently completed a research internship on insider-threat detection at <b>National Formosa University, Taiwan</b>.
</p>

<p align="center">
  <a href="mailto:hargun3574@gmail.com">
    <img src="https://img.shields.io/badge/Email%20Me-informational?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/hargun-singh1/">
    <img src="https://img.shields.io/badge/LinkedIn%20Profile-blue?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

---

## 🧠 Featured Engineering Work

### 🔗 Blockchain-Based Insider-Threat Detection — Research Internship (NFU, Taiwan)
A permissioned-blockchain anomaly-detection platform combining access-control enforcement, behavioral telemetry, and unsupervised ML.
- Deployed a **5-node private Ethereum network** (Hyperledger Besu, QBFT consensus) with smart-contract-enforced access policies — role-scoped operation sets, approval-gated high-value transfers, admin-only account freezes
- Built a structured behavioral event pipeline via contract emissions (actor, role, operation, outcome, timestamp)
- Applied **Isolation Forest** and **Local Outlier Factor** to flag anomalies; studied detection accuracy for low-history (<100 ops) vs. high-history (>1000 ops) profiles
- Co-authored research paper on the system — *submitted, under review*

**Tech:** Hyperledger Besu • Solidity • QBFT • Python • Scikit-learn • ethers.js

---

### 🔐 IdentityFlow — IAM System
<a href="https://identity-flow-mu.vercel.app/"><img src="https://img.shields.io/badge/Live_Demo-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="https://github.com/HargunS7/IdentityFlow"><img src="https://img.shields.io/badge/Source-181717?style=for-the-badge&logo=github&logoColor=white" /></a>

A production-grade Identity & Access Management backend built on zero-trust principles.
- JWT access/refresh token flows with **token rotation** and middleware-enforced authorization
- Least-privilege permissions engine: temporary/permanent grants, automated expiry, full audit logging, session/device tracking
- Modular MVC backend with layered middleware separating authentication, authorization, and validation

**Tech:** Node.js/Express • PostgreSQL • Prisma • JWT • RBAC • Docker

---

### 🎟️ Momento — Event Management System
<a href="https://momento-mu-drab.vercel.app"><img src="https://img.shields.io/badge/Live_Demo-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="https://github.com/HargunS7/Momento"><img src="https://img.shields.io/badge/Source-181717?style=for-the-badge&logo=github&logoColor=white" /></a>

A multi-tenant, multi-role backend with a security-first event lifecycle.
- Enforced lifecycle: **request → review → approval → publish**, blocking unauthorized state transitions across user, admin, and club roles
- Access-controlled REST APIs with approval workflows and tamper-evident audit trails
- Data isolation enforced at the storage layer via PostgreSQL **row-level security (RLS)**

**Tech:** Node.js/Express • Supabase (PostgreSQL) • Docker

---

### 🎮 PlayWay — Retro Gaming Console (BeagleBone Black)
Turned a BeagleBone Black into an ARM RetroArch console.
- Docker-based cross-compilation resolving architecture-specific Debian dependencies
- Remote GUI over SSH; hardened runtime to reduce exposed footprint under constrained ARM hardware

**Tech:** BeagleBone Black • Debian • Docker • RetroArch • Linux debugging

---

## 🛠 Tech Stack

**Languages**
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)

**Backend & Databases**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

**Blockchain**
![Hyperledger Besu](https://img.shields.io/badge/Hyperledger_Besu-2F3134?style=for-the-badge&logo=hyperledger&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white)
![Hardhat](https://img.shields.io/badge/Hardhat-FFF04D?style=for-the-badge&logo=hardhat&logoColor=black)

**ML / Detection**
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**Tools / DevOps**
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_EC2-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## 📌 What I'm Good At
- Designing secure, multi-role backends with clean, layered architecture
- Access-control systems — RBAC, RLS, least-privilege, audit trails
- Permissioned blockchain infrastructure and behavioral event pipelines
- ML-based anomaly detection for security telemetry

---

## 🏆 Certifications
- **CCNA: Enterprise Networking, Security & Automation** — Cisco Networking Academy
- **Deep Learning with PyTorch, Keras & TensorFlow** — IBM (Coursera)
- **Data Structures & Algorithms Workshop** — GeeksforGeeks @ IIT Roorkee

📂 Full verified archive: [github.com/HargunS7/certifications](https://github.com/HargunS7/certifications)

---

⭐ Actively building and shipping. If you like the work, consider following.
