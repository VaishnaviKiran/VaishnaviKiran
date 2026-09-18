# Hi there, I'm Sri Vaishnavi Kiran 👋

Software Engineer building AI-enabled systems, backend services, and full-stack applications, with interests in efficient AI systems and AI computing.

## 👩‍💻 About Me

- 💻 Software Engineer working across Java, Python, backend services, APIs, and database-backed applications
- 🤖 Experience building AI/LLM-integrated applications and production-oriented software systems
- 🧠 Interested in efficient AI systems, LLM inference, AI systems engineering, and resource-efficient computing
- ⚙️ Built a scaled dot-product attention implementation in SystemVerilog and validated it against a Python reference model
- ☁️ Experience with AWS, Docker, PostgreSQL, REST APIs, microservices, React, and TypeScript
- 🎓 M.S. in Information Systems, George Mason University | B.Tech in Electronics and Communication Engineering
- 📍 Bellevue, WA
- 💼 Open to Software Engineering, Backend, AI Engineering, and research opportunities

---

## 🚀 Featured Projects

### ⚙️ Scaled Dot-Product Attention Hardware

A SystemVerilog implementation of a 2×2 scaled dot-product attention datapath exploring how an AI operation behaves under fixed-point and resource constraints.

- Implemented Q/K/V projections, attention-score computation, fixed-point scaling, approximate softmax, and weighted-value output
- Reused a sequential matrix-multiplication engine across stages, trading additional latency for reduced hardware duplication
- Used Q8.8 fixed-point scaling and a LUT-based softmax approximation
- Validated against a Python floating-point reference model
- MAE: 0.005390 | Max absolute error: 0.020047

**Tech:** SystemVerilog • Icarus Verilog • Python • Fixed-Point Arithmetic

[View Repository](https://github.com/VaishnaviKiran/attention-hardware)

---

### 💰 SmartTaxAI

An AI-assisted tax application for transaction classification, user review, and tax estimation.

- Built a transaction pipeline from Plaid ingestion through normalization, PostgreSQL persistence, classification, review, and export
- Combined deterministic merchant rules with LLM reasoning and confidence thresholds
- Added merchant-level feedback so confirmed corrections influence later classifications
- Deployed the application using AWS and PostgreSQL RDS

**Tech:** React • TypeScript • Node.js/Express • PostgreSQL • Plaid • OpenAI • AWS • Docker

---

### 🎯 VoxOps Command Center

A voice-enabled AI incident-management platform built around backend services, event-driven workflows, and AI integration.

**Tech:** Java • Spring Boot • Next.js • PostgreSQL • Kafka • OpenAI • Docker • Prometheus • Grafana

---

## 🛠️ Technologies

**Languages**  
Java • Python • C++ • TypeScript • JavaScript • SQL • SystemVerilog • MATLAB

**Backend & Systems**  
Spring Boot • Node.js • Express • FastAPI • REST APIs • Microservices • Linux

**AI**  
OpenAI APIs • LLM Integration • RAG • Embeddings • Model/Reference Validation

**Cloud & DevOps**  
AWS • RDS • App Runner • Docker • GitHub Actions • CI/CD

**Data & Frontend**  
PostgreSQL • React • Next.js • TypeScript • Tailwind CSS
