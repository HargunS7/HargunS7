<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=250&text=Hargun%20Singh&fontAlign=50&fontAlignY=40&color=gradient" />

<h1 align="center">Hi, I'm Hargun</h1>
<h3 align="center">Backend Engineer / Access Control & Security</h3>

<p align="center">
  I build backends for access control and security telemetry. Most of my recent work has been on IAM systems, permissioned blockchain, and anomaly detection.<br/>
  Just finished a research internship at National Formosa University, Taiwan. My first-author paper from it was accepted at ICEA 2026 (ACM ICPS).
</p>

<p align="center">
  <a href="https://hargun-dev.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-hargun--dev.vercel.app-000000?style=flat-square&logo=vercel&logoColor=white" />
  </a>
  <a href="mailto:hargun3574@gmail.com">
    <img src="https://img.shields.io/badge/Email-informational?style=flat-square&logo=gmail&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/hargun-singh1/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
</p>

---

## Work

### Behavior-Aware Access Control and Anomaly Detection (NFU Taiwan, research internship)

A permissioned blockchain with access-control enforcement, behavioral telemetry, and ML-based anomaly detection on top.

- Ran a 4-node private Ethereum network (Hyperledger Besu, QBFT) with access policies enforced in smart contracts: role-scoped operation sets, approval gates on high-value transfers, admin-only account freezes
- Emitted structured behavioral events from the contracts (actor, role, operation, outcome, timestamp) into a detection pipeline
- Compared global and per-user models on low-history (~750 events) and high-history (~2,800 events) profiles. Global models mostly learned transaction size (anomaly F1 0.66), per-user Isolation Forest failed under class imbalance, and supervised per-user models with relative features reached precision 1.00 and recall 0.50 in a diagnostic evaluation
- Caught temporal data leakage behind near-perfect early scores and removed time-derived features from the pipeline
- First author of *Behavior-Aware Access Control and Transaction Anomaly Detection in a Private Ethereum-Based Financial System*, accepted at [ICEA 2026](https://icea-conf.github.io/2026/) (to appear in ACM ICPS proceedings)
- [Recommendation letter from Prof. Ming-Shen Jian](https://hargun-dev.vercel.app/letters/Hargun-Singh-Recommendation-NFU.pdf)

Hyperledger Besu, Solidity, QBFT, Python, scikit-learn, ethers.js

---

### IdentityFlow (IAM system)

<a href="https://identity-flow-mu.vercel.app/"><img src="https://img.shields.io/badge/Live_Demo-000000?style=flat-square&logo=vercel&logoColor=white" /></a>
<a href="https://github.com/HargunS7/IdentityFlow"><img src="https://img.shields.io/badge/Source-181717?style=flat-square&logo=github&logoColor=white" /></a>

An identity and access management backend built on zero-trust assumptions.

- JWT access/refresh flows with token rotation, authorization enforced in middleware
- Least-privilege permissions engine: temporary and permanent grants, automated expiry, audit logging, session and device tracking
- Layered MVC backend that keeps authentication, authorization, and validation in separate middleware stages

Node.js/Express, PostgreSQL, Prisma, JWT, RBAC, Docker

---

### Momento (event management)

<a href="https://momento-mu-drab.vercel.app"><img src="https://img.shields.io/badge/Live_Demo-000000?style=flat-square&logo=vercel&logoColor=white" /></a>
<a href="https://github.com/HargunS7/Momento"><img src="https://img.shields.io/badge/Source-181717?style=flat-square&logo=github&logoColor=white" /></a>

Multi-tenant, multi-role backend where the event lifecycle is the security boundary.

- Enforced state machine (request, review, approval, publish) that blocks unauthorized transitions across user, admin, and club roles
- REST APIs behind access control, with approval workflows and tamper-evident audit trails
- Tenant isolation pushed down to the storage layer using PostgreSQL row-level security

Node.js/Express, Supabase (PostgreSQL), Docker

---

### PlayWay (retro gaming console on BeagleBone Black)

Turned a BeagleBone Black into an ARM RetroArch console.

- Cross-compiled in Docker to work around architecture-specific Debian dependencies
- Remote GUI over SSH, with the runtime trimmed down to reduce exposed surface on constrained ARM hardware

BeagleBone Black, Debian, Docker, RetroArch, Linux debugging

---

## Stack

Day to day I work in **Node.js/Express** with **PostgreSQL** and **Prisma**, containerized with **Docker**, deployed on **AWS EC2** and Vercel. Auth work is JWT and RBAC. Most of what I've shipped lives here.

**Also worked in:** Python (the ML detection pipeline: scikit-learn, pandas), Solidity and Hardhat against Hyperledger Besu, Java and Spring Boot from coursework and interview prep, C++, MongoDB.

**Comfortable with:** Linux, Git, GitHub Actions, cross-compilation for ARM.

---

## Certifications

- CCNA: Enterprise Networking, Security & Automation (Cisco Networking Academy)
- Deep Learning with PyTorch, Keras & TensorFlow (IBM, Coursera)
- Data Structures & Algorithms Workshop (GeeksforGeeks @ IIT Roorkee)

Full archive: [github.com/HargunS7/certifications](https://github.com/HargunS7/certifications)
