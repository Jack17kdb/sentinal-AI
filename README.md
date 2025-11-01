# 🛡️ Sentinel AI — Autonomous Threat Detection & Response Platform

> **AI + Cybersecurity + DevOps + MERN Stack in one powerful project.**
> A self-learning, full-stack AI platform that monitors, detects, and mitigates cyber threats autonomously — while providing real-time analytics through a modern dashboard.

---

## 🚀 Overview

**Sentinel AI** is an intelligent cybersecurity and infrastructure monitoring system that integrates:

- 🧠 **AI-based anomaly detection** — learns and predicts malicious activity in system/network logs.
- 🌐 **MERN web dashboard** — provides real-time visualization and control of all detections and automated responses.
- ⚙️ **DevOps automation** — deploys securely with Docker/Terraform and performs automatic incident responses..
- 💀 **Hacking simulation engine** — safely generates attacks to test and demonstrate system defense capabilities.

This project demonstrates mastery across **AI/ML**, **Full-Stack Development**, **DevOps**, and **Cybersecurity** — built for real-world application and portfolio presentation.

---

## 🧩 Features

| Category | Description |
|-----------|-------------|
| 🧠 **AI Detection Engine** | Machine learning models (e.g., LSTM, Isolation Forest) that classify log entries as normal or malicious. |
| 🌐 **MERN Dashboard** | React + Node.js interface showing live threat feeds, analytics, and system status. |
| ⚙️ **DevOps Automation** | Dockerized microservices, CI/CD pipeline, and optional Terraform-managed infrastructure. |
| 💀 **Attack Simulator** | Generates ethical test attacks (port scans, brute force, etc.) for defense validation. |
| 🔐 **Auto Response** | Automatically isolates compromised services or bans attacker IPs. |
| 📊 **Analytics & Logs** | Charts, visual trends, and full event history stored in MongoDB. |

---

## 🧠 AI Module

- Trains on synthetic or real network/system log data.
- Detects anomalies using:
  - Logistic Regression / Random Forest (baseline)
  - LSTM or Autoencoder (advanced)
- Exports predictions to the Node.js backend for real-time streaming to the dashboard.

**Tech Stack:** 
`Python`, `Scikit-learn`, `PyTorch`, `Pandas`, `Matplotlib`, `Keras`

---

## 🌐 Web Dashboard (MERN Stack)

### Main Pages
- **Login / Auth (JWT-based)** — secure access to admin panel.
- **Threat Feed** — real-time suspicious activity logs.
- **Analytics Panel** — visualizes patterns, model confidence scores, and activity graphs.
- **Response Center** — approve, reject, or trigger automated responses.
- **System Logs** — history of actions and retraining results.

**Tech Stack:**
`MongoDB`, `Express.js`, `React.js`, `Node.js`, `Socket.io`, `Chart.js`

---

## ⚙️ DevOps Layer

- **Containerization:** All services packaged with Docker.
- **Infrastructure as Code:** Managed with Terraform.
- **CI/CD Pipeline:** Automated testing, build, and deployment via GitHub Actions.
- **Monitoring & Alerts:** Optional integration with Prometheus + Grafana.

**Automated Response Examples:**
- Stop a compromised container.
- Block IP via firewall rule.
- Restart affected service.
- Notify admin via webhook or email.

---

## 💻 Hacking Simulation (Ethical Testing)

A contained "Red Team" environment that safely tests Sentinel AI’s response:
- Simulate **port scans**, **brute-force attacks**, **malicious scripts**, etc.
- Logs generated feed directly into the AI model.
- Demonstrates **attack → detection → automated defense** pipeline.

**Stack:**
`Python`, `Nmap`, `Scapy`, `Custom Scripts`

---

## 🏗️ System Architecture
