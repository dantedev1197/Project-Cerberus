# Project Cerberus

A custom DevSecOps homelab and enterprise simulation environment.

## 👥 The Team
* **Dante:** Full-Stack Engineering & CI/CD Pipeline Architecture
* **Jim:** Cybersecurity, Zero-Trust Networking & Infrastructure

## 🎯 Project Goals
1. **Enterprise Simulation:** Build a fully functional DevSecOps environment that mirrors modern, secure corporate infrastructures.
2. **Full-Stack Mastery (Dante):** Establish a reliable CI/CD pipeline to rapidly build, test, and deploy robust web applications and database architectures.
3. **Advanced Security (Jim):** Implement Zero-Trust networking, automated vulnerability scanning, and proactive threat monitoring to secure the infrastructure.
4. **The "Build & Break" Cycle:** Create an active feedback loop where developers build applications, security tests and breaks them, and developers patch the vulnerabilities.

## 💻 Hardware Infrastructure
* **Compute Server:** HP ProLiant DL360 G7 (48GB RAM, 16 Core)
* **Core Switch:** Aruba 2530 48G PoE+ (J9775a)
* **Management/SIEM Node:** HP Mini G4 (i5 7th Gen, 8/16GB RAM)

## 🏗️ Project Architecture 
This repository serves as the single source of truth for both the application codebase and the infrastructure documentation. 

* `/app` - Contains the full-stack application payload (Frontend & Backend).
* `/infra` - Contains deployment manifests, Docker Compose files, and hypervisor configurations.
* `/docs` - Contains network layouts, API specifications, and vulnerability reports.

## 🚀 Quick Links
* [Network & Infrastructure Setup](docs/infrastructure.md)
* [Application API Specs](docs/api-specs.md)
* [Penetration & Security Reports](docs/security-reports.md)
* [Deployment Runbooks](docs/runbooks.md)