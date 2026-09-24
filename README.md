<!-- ==========================================================
     ADITYA KHANDELWAL | CYBERSECURITY ENGINEERING
     GitHub Profile: adicyb
     ========================================================== -->

<div align="center">

<!-- ===================== HEADER ===================== -->

<img
  src="https://capsule-render.vercel.app/api?type=waving&color=0:0b132b,45:1c3b57,100:007f86&height=220&section=header&text=ADITYA%20KHANDELWAL&fontSize=45&fontColor=ffffff&fontAlignY=38&desc=Cybersecurity%20Engineering%20%7C%20Detection%20Systems%20%7C%20Applied%20ML&descSize=16&descAlignY=58&descColor=7df9ff&animation=fadeIn"
  width="100%"
  alt="Aditya Khandelwal - Cybersecurity Engineering"
/>

<br/>

<img
  src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=3000&pause=900&color=48D1CC&center=true&vCenter=true&width=750&lines=Cybersecurity+Engineering;Detection+Engineering+%7C+Network+Defense;Endpoint+Security+%7C+Security+Monitoring;Applied+Machine+Learning+for+Cybersecurity"
  alt="Cybersecurity engineering introduction"
/>

<br/><br/>

<!-- ===================== SOCIAL LINKS ===================== -->

<a href="https://github.com/adicyb">
  <img
    src="https://img.shields.io/badge/GitHub-adicyb-181717?style=for-the-badge&logo=github&logoColor=white"
    alt="GitHub"
  />
</a>

<a href="https://www.linkedin.com/in/aditya-khandelwal2006/">
  <img
    src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"
    alt="LinkedIn"
  />
</a>

<br/><br/>

<img src="https://img.shields.io/badge/Focus-Detection%20Engineering-007f86?style=flat-square" alt="Detection Engineering"/>
<img src="https://img.shields.io/badge/Domain-Cybersecurity-1c3b57?style=flat-square" alt="Cybersecurity"/>
<img src="https://img.shields.io/badge/Certification-RHCSA-cc0000?style=flat-square" alt="RHCSA"/>
<img src="https://img.shields.io/badge/Open%20To-Internships%20%26%20Collaboration-238636?style=flat-square" alt="Open to internships and collaboration"/>

</div>

---

# 🎯 Areas of Interest

<div align="center">

<table>
  <tr>
    <td align="center" width="33%">
      <h3>🛡️ Network Defense</h3>
      <p>Network traffic analysis, packet inspection, intrusion detection, and threat investigation.</p>
    </td>
    <td align="center" width="33%">
      <h3>🖥️ Endpoint Security</h3>
      <p>Process telemetry, behavioral monitoring, endpoint detection, and risk scoring.</p>
    </td>
    <td align="center" width="33%">
      <h3>🧠 Applied Machine Learning</h3>
      <p>Anomaly detection, feature engineering, graph learning, and security analytics.</p>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%">
      <h3>🔎 Security Operations</h3>
      <p>SIEM platforms, alert investigation, event analysis, and incident-response workflows.</p>
    </td>
    <td align="center" width="33%">
      <h3>🐧 Linux & Systems</h3>
      <p>Linux administration, system hardening, scripting, and infrastructure security.</p>
    </td>
    <td align="center" width="33%">
      <h3>⚙️ Security Automation</h3>
      <p>Security tool integration, event pipelines, and automated investigation workflows.</p>
    </td>
  </tr>
</table>

</div>

My broader interests include:

- Security Operations Center (SOC) workflows and alert investigation.
- Security information and event management (SIEM).
- Linux administration and system hardening.
- Threat detection and incident-response workflows.
- Security automation and tool integration.
- Graph-based analysis of identities, endpoints, and network activity.
- Evaluation of machine-learning techniques for cybersecurity.

---

# 🚀 Featured Projects

My projects explore different aspects of cybersecurity and systems engineering, from network traffic inspection to endpoint monitoring and wireless security.

### Project Index

| Project | Focus | Repository |
|---|---|---|
| **NetGuard AI** | Hybrid-ML network intrusion detection | [Open repository](https://github.com/adicyb/NetGaurd-AI) |
| **ZeroSight EDR** | Behavioral endpoint detection and response | [Open repository](https://github.com/adicyb/zerosight-edr) |
| **WiFi Security IDS** | Wireless threat detection using ESP8266 | [Open repository](https://github.com/adicyb/wifi-security-ids) |
| **Zero Fault Horizon** | Intelligent rerouting on simulated networks | [Open repository](https://github.com/adicyb/zfh-core) |


<div align="center">

<a href="https://github.com/adicyb/NetGaurd-AI">
  <img
    src="https://img.shields.io/badge/🛡️%20NetGuard%20AI-Network%20Intrusion%20Detection-007f86?style=for-the-badge"
    alt="NetGuard AI repository"
  />
</a>

<a href="https://github.com/adicyb/zerosight-edr">
  <img
    src="https://img.shields.io/badge/🔍%20ZeroSight%20EDR-Behavioral%20Endpoint%20Detection-1c3b57?style=for-the-badge"
    alt="ZeroSight EDR repository"
  />
</a>

<br/><br/>

<a href="https://github.com/adicyb/wifi-security-ids">
  <img
    src="https://img.shields.io/badge/📡%20WiFi%20Security%20IDS-Wireless%20Threat%20Detection-6a4c93?style=for-the-badge"
    alt="WiFi Security IDS repository"
  />
</a>

<a href="https://github.com/adicyb/zfh-core">
  <img
    src="https://img.shields.io/badge/🧬%20Zero%20Fault%20Horizon-Intelligent%20Network%20Rerouting-405d9b?style=for-the-badge"
    alt="Zero Fault Horizon repository"
  />
</a>

</div>

---

## 🛡️ NetGuard AI

### Hybrid-ML Network Intrusion Detection System

**[View Repository](https://github.com/adicyb/NetGaurd-AI)**

NetGuard AI is a network intrusion detection project focused on identifying unusual traffic patterns through unsupervised machine learning and rule-based analysis.

The system captures network traffic using Scapy, extracts features over short time windows, and evaluates observations using an Isolation Forest and One-Class SVM ensemble.

It combines model outputs with rule-based indicators to produce confidence tiers that can help an analyst prioritize suspicious activity.

### Key Components

- Live packet capture and traffic feature extraction using Scapy.
- One-second traffic analysis windows.
- Isolation Forest and One-Class SVM anomaly detection.
- Rule-based indicators for scanning, flooding, and potential exfiltration activity.
- HIGH / MEDIUM / LOW heuristic confidence tiers.
- SQLite-based event logging.
- Streamlit-based monitoring dashboard.
- Built-in traffic simulation for controlled testing.

### Technology Stack

`Python` · `Scapy` · `scikit-learn` · `Streamlit` · `SQLite`

> **Detection note:** The confidence tiers are heuristic outputs based on model agreement and rule thresholds. They are not calibrated probabilities of malicious activity, and anomalous traffic is not necessarily malicious.

---

## 🔍 ZeroSight EDR

### Behavioral Endpoint Detection & Response

**[View Repository](https://github.com/adicyb/zerosight-edr)**

ZeroSight EDR is a lightweight endpoint monitoring project designed to identify processes that exhibit behavior worth investigating.

It collects process telemetry and applies a behavioral risk-scoring engine to highlight suspicious activity without relying exclusively on known-malicious signatures.

The project explores how endpoint telemetry can be collected, analyzed, and presented through an analyst-facing interface.

### Key Components

- Real-time process telemetry collection using `psutil`.
- Behavioral risk-scoring engine.
- Identification of processes requiring further investigation.
- Interactive Streamlit dashboard.
- Manual process isolation functionality.
- Incident logging using SQLite.
- Behavioral detection concepts that complement signature-based approaches.

### Technology Stack

`Python` · `psutil` · `Streamlit` · `Plotly` · `SQLite`

> **Detection note:** Behavioral alerts are investigative leads rather than definitive malware classifications. Detection capability depends on the implemented telemetry, features, and detection logic.

---

## 📡 WiFi Security IDS

### ESP8266-Based Evil-Twin and Rogue Access Point Detection

**[View Repository](https://github.com/adicyb/wifi-security-ids)**

WiFi Security IDS explores hardware-assisted wireless security monitoring using an ESP8266-based scanning device and a Flask server.

The device collects information about nearby wireless networks and applies rule-based scoring to identify access points that may warrant investigation.

The project demonstrates how lightweight hardware can participate in a security monitoring pipeline.

### Key Components

- ESP8266-based wireless network scanning.
- SSID, BSSID, channel, and RSSI observation.
- On-device rule-based risk scoring.
- Detection indicators involving BSSID conflicts, signal-strength anomalies, and channel mismatches.
- HTTP-based telemetry transmission.
- Flask-based event logging and alert presentation.

### Technology Stack

`C++` · `Arduino` · `ESP8266` · `Flask` · `Python`

> **Detection note:** Wireless indicators can produce false positives. Similar SSIDs, changing signal strength, and channel differences require contextual investigation before an access point can be classified as malicious.

---

## 🧬 Zero Fault Horizon

### Intelligent Rerouting on Simulated Network Topologies

**[View Repository](https://github.com/adicyb/zfh-core)**

Zero Fault Horizon explores intelligent traffic rerouting in simulated network environments.

The system models network topologies using NetworkX, introduces link failures, and uses a rule-based teacher to generate training examples for a RandomForest classifier.

The classifier is then used to predict routing decisions intended to route traffic around simulated failures.

### Key Components

- Network topology modeling using NetworkX.
- Simulated link failures and fault injection.
- Synthetic dataset generation using a rule-based teacher.
- RandomForest-based path prediction.
- Weight-aware rerouting logic.
- Evaluation of path-prediction performance on generated data.

### Technology Stack

`Python` · `NetworkX` · `scikit-learn`

---
