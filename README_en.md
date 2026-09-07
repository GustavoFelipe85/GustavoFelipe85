<img width="2048" height="682" alt="Gustavo F. Paluch profile banner" src="https://github.com/user-attachments/assets/bd97a2bf-4a18-4f81-84b0-412fa0bff8f8" />

# Gustavo F. Paluch

🌐 **[Versão em Português](./README.md)**

**Computer Engineer • Cybersecurity • IT Infrastructure • DevOps • IoT • Applied AI**  
Cascavel, Paraná — Brazil

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Gustavo%20Paluch-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/gustavofpaluch/)
[![ORCID](https://img.shields.io/badge/ORCID-Profile-A6CE39?style=flat&logo=orcid)](https://orcid.org/0009-0008-0989-8913)
[![Curriculum Lattes](https://img.shields.io/badge/Lattes-Curriculum-004A80?style=flat)](http://lattes.cnpq.br/3233095819966467)
[![Zenodo](https://img.shields.io/badge/DOI-Zenodo-024dad?style=flat&logo=zenodo)](https://doi.org/10.5281/zenodo.21706931)

---

### 👨‍💻 About Me

I am a **Computer Engineer** focused on **cybersecurity, IT infrastructure, DevOps, Internet of Things (IoT), and applied artificial intelligence**.

I build systems that integrate **embedded hardware, secure communication channels, data pipelines, containerization, observability, and computational experimentation**, following the **Secure by Design** principle and maintaining rigorous technical documentation.

* **Certification:** Cisco Certified CyberOps Associate
* **Research Focus:** Proxy interview threat analysis, social engineering vectors targeting GitHub users, and corporate security governance.

---

### 🔬 Core Competencies & Research Areas

- **Cybersecurity & Governance:** Threat modeling, social engineering containment, and secure runtime environments.
- **Infrastructure & DevOps:** Linux administration, Docker containerization, and automated CI/CD pipelines.
- **Cyber-Physical Systems & IoT:** Sensor networks, telemetry protocols, and precision agriculture.
- **Computer Architecture & HPC:** Empirical performance benchmarking, memory hierarchy profiling, cache miss analysis, and parallel computing with OpenMP and MPI.
- **Data Engineering:** Distributed pipelines, time-series data storage, and real-time system telemetry.

---

### 🛡️ Featured Publication — Social Engineering via GitHub

**When GitHub Becomes a Social Engineering Vector: The Threat of "Proxy Interviews" in Remote Hiring**

A real-world case study analyzing targeted reconnaissance via GitHub, examining the mechanics of identity fraud, insider threat risks across CI/CD pipelines, compliance/NDA breaches, and operational hygiene practices for developers.

🔗 [Article on LinkedIn Pulse](https://www.linkedin.com/pulse/quando-o-github-vira-vetor-de-engenharia-social-risco-gustavo-xfcgf/) | [Publication on TabNews](https://www.tabnews.com.br/GustavoFPaluch/quando-o-github-vira-vetor-de-engenharia-social-o-risco-dos-proxy-interviews-no-recrutamento-remoto)

---

### 🚜 Featured Project — Smart Farm IoT System

The **Smart Farm IoT System** is a modular, secure, and reproducible IoT architecture designed for continuous environmental monitoring and scalable agricultural automation.

**Architecture Pipeline:**
```text
[Sensors / ESP32] ──(MQTT/TLS QoS 1)──> [Mosquitto Broker] ──> [Python Consumer] ──> [InfluxDB] ──> [Grafana Dashboard]
                                                                        │
                                                            (JSON Schema Validation)

```

**Key Architectural Features:**

* Authenticated MQTT transport with QoS 1;
* Versioned data contracts enforced via strict JSON Schema validation prior to persistence;
* Ingestion pipeline normalization exposing REST endpoints via FastAPI;
* Isolated, reproducible runtime orchestration managed with Docker Compose;
* End-to-end operational observability utilizing InfluxDB and Grafana dashboards;
* Continuous Integration (CI) automated with GitHub Actions.

**Empirical Benchmarks:**

* Average pipeline latency of approximately **118 ms** under strict schema enforcement;
* Sustained throughput exceeding **10,000 messages/hour**;
* **100% rejection rate** of malformed payloads during automated stress testing.

🔗 [View Repository](https://github.com/GustavoFelipe85/smart-farm-iot-system)

📚 [Technical & Academic Documentation](https://github.com/GustavoFelipe85/smart-farm-iot-system/blob/main/README.md)

---

### 🎓 Academic Background & Research

* **B.S. in Computer Engineering** — UNISA (2024).
* **Special Student in Computer Architecture (2026):** Graduate Program in Computer Science (PPGComp/UNIOESTE) — 60 hours, 4 credits.
* Empirical investigations covering processor microarchitectures, cache memory hierarchies, memory profiling with Valgrind (Callgrind/Cachegrind), and parallel scalability with OpenMP and MPI (MPICH).

---

### 🛠️ Technical Stack

* **Languages:** Python, C, C++, Bash
* **Frameworks & Specifications:** FastAPI, JSON Schema, MQTT (Mosquitto)
* **DevOps & Infrastructure:** Linux (Ubuntu/Debian), Docker, Docker Compose, GitHub Actions, CI/CD
* **Data & Observability:** InfluxDB, Grafana, Time-Series Databases
* **HPC & Profiling:** Valgrind (Cachegrind, Callgrind), OpenMP, MPI (MPICH)

---

### 🔗 Academic & Professional Links

* 💼 [LinkedIn Profile](https://www.linkedin.com/in/gustavofpaluch/)
* 🧪 [ORCID Profile](https://orcid.org/0009-0008-0989-8913)
* 📚 [Curriculum Lattes (CNPq)](http://lattes.cnpq.br/3233095819966467)
* 📦 [Smart Farm IoT System Repository](https://github.com/GustavoFelipe85/smart-farm-iot-system)
* 🧠 [CELUS Design Studio](https://app.celus.io/workspaces/62bcb5b7-98f0-40a1-8b20-6d3f2fd2e6b4)
* 📄 [Preprint / DOI (Zenodo)](https://www.google.com/url?sa=E&source=gmail&q=https://doi.org/10.5281/zenodo.21706931)

---

*Engineering systems driven by security, reproducibility, empirical analysis, and rigorous documentation.*

```

```
