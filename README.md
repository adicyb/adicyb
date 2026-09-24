<!-- ==========================================================
     ADITYA KHANDELWAL | CYBERSECURITY ENGINEERING
     GitHub Profile: adicyb
     ========================================================== -->

<div align="center">

  <!-- Animated Header -->

  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:0b132b,45:1c3b57,100:007f86&height=220&section=header&text=ADITYA%20KHANDELWAL&fontSize=45&fontColor=ffffff&fontAlignY=38&desc=Cybersecurity%20Engineering%20%7C%20Detection%20Systems%20%7C%20Applied%20ML&descSize=16&descAlignY=58&descColor=7df9ff&animation=fadeIn"
    width="100%"
    alt="Aditya Khandelwal - Cybersecurity Engineering"
  />

  <br/>

  <!-- Typing Animation -->

  <img
    src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=3000&pause=900&color=48D1CC&center=true&vCenter=true&width=750&lines=Building+practical+cybersecurity+systems;Detection+Engineering+%7C+Network+Defense+%7C+Endpoint+Security;Security+Monitoring+%7C+SIEM+%7C+Applied+Machine+Learning;Turning+Telemetry+Into+Actionable+Security+Signals"
    alt="Cybersecurity engineering introduction"
  />

  <br/><br/>

  <!-- Social Links -->

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

  <img
    src="https://img.shields.io/badge/Focus-Detection%20Engineering-007f86?style=flat-square"
    alt="Detection Engineering"
  />

  <img
    src="https://img.shields.io/badge/Domain-Cybersecurity-1c3b57?style=flat-square"
    alt="Cybersecurity"
  />

  <img
    src="https://img.shields.io/badge/Certification-RHCSA-cc0000?style=flat-square"
    alt="RHCSA"
  />

  <img
    src="https://img.shields.io/badge/Open%20To-Internships%20%26%20Collaboration-238636?style=flat-square"
    alt="Open to internships and collaboration"
  />

</div>

---

# 👨‍💻 About Me

Hi, I'm **Aditya Khandelwal**, a B.Tech Computer Science and Engineering student specializing in Cyber Security at **SRM Institute of Science and Technology**.

My primary interest lies in **building practical cybersecurity systems** that help identify suspicious activity, analyze security events, and improve visibility across networks and endpoints.

I enjoy working at the intersection of cybersecurity, systems engineering, and applied machine learning. Rather than treating security as a collection of theoretical concepts, I focus on understanding how attacks manifest in real environments, what telemetry can reveal about them, and how detection mechanisms can turn that telemetry into useful information for an analyst.

My work includes developing network intrusion detection systems, behavioral endpoint monitoring tools, wireless security experiments, and machine-learning-based detection approaches.

I also work with security infrastructure and monitoring platforms, exploring how SIEM solutions, intrusion detection systems, log analysis pipelines, and security automation tools can be used to support security operations.

I believe a useful detection system should do more than generate alerts. It should provide meaningful evidence, make its detection logic understandable, and be evaluated with appropriate testing methods.

I am particularly interested in the distinction between unusual behavior and confirmed malicious activity, and in understanding the limitations of the techniques used to identify threats.

**Currently seeking:** SOC Analyst, Security Engineering, and Detection Engineering internship opportunities.

---

# 🎯 Technical Interests

<div align="center">

<table>
  <tr>
    <td align="center" width="33%">
      <h3>🛡️ Network Defense</h3>
      <p>Network traffic analysis, intrusion detection, packet inspection, and threat investigation.</p>
    </td>
    <td align="center" width="33%">
      <h3>🖥️ Endpoint Security</h3>
      <p>Process telemetry, behavioral monitoring, endpoint detection, and risk scoring.</p>
    </td>
    <td align="center" width="33%">
      <h3>🧠 Applied ML</h3>
      <p>Anomaly detection, graph learning, feature engineering, and security analytics.</p>
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

<div align="center">

  <a href="https://github.com/adicyb/NetGaurd-AI">
    <img
      src="https://github-readme-stats.vercel.app/api/pin/?username=adicyb&repo=NetGaurd-AI&theme=tokyonight&hide_border=true"
      alt="NetGuard AI repository"
    />
  </a>

  <a href="https://github.com/adicyb/zerosight-edr">
    <img
      src="https://github-readme-stats.vercel.app/api/pin/?username=adicyb&repo=zerosight-edr&theme=tokyonight&hide_border=true"
      alt="ZeroSight EDR repository"
    />
  </a>

  <a href="https://github.com/adicyb/wifi-security-ids">
    <img
      src="https://github-readme-stats.vercel.app/api/pin/?username=adicyb&repo=wifi-security-ids&theme=tokyonight&hide_border=true"
      alt="WiFi Security IDS repository"
    />
  </a>

  <a href="https://github.com/adicyb/zfh-core">
    <img
      src="https://github-readme-stats.vercel.app/api/pin/?username=adicyb&repo=zfh-core&theme=tokyonight&hide_border=true"
      alt="Zero Fault Horizon repository"
    />
  </a>

</div>

---

## 🛡️ NetGuard AI

### Hybrid-ML Network Intrusion Detection System

**Repository:** [NetGuard AI](https://github.com/adicyb/NetGaurd-AI)

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

**Repository:** [ZeroSight EDR](https://github.com/adicyb/zerosight-edr)

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

**Repository:** [WiFi Security IDS](https://github.com/adicyb/wifi-security-ids)

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

**Repository:** [Zero Fault Horizon](https://github.com/adicyb/zfh-core)

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

`Python` · `NetworkX` · `scikit-learn` · `Pandas`

> **Evaluation note:** The reported path-prediction accuracy of approximately 93% relates to the generated dataset. It has not been validated against real-world network conditions or an independent test environment.

---

# 🔬 Research Interests

My research interests include **multimodal security telemetry, graph-based machine learning, and lateral movement detection** in enterprise environments.

I am interested in exploring how relationships between identities, endpoints, and network activity can provide additional context for investigating suspicious behavior.

Areas of interest include:

| Research Area | Technical Focus |
|---|---|
| Identity telemetry | Authentication activity and relationships between users and systems |
| Network telemetry | Network flows, communication patterns, and host relationships |
| Endpoint telemetry | Process activity and host-level behavioral information |
| Behavioral analysis | Isolation Forest, One-Class SVM, and anomaly detection |
| Graph learning | GraphSAGE, Graph Attention Networks, and relational security analysis |
| Temporal analysis | Sliding-window temporal graphs and evolving activity patterns |
| Hybrid detection | Combining behavioral, graph, and temporal evidence |
| Evaluation | Detection latency, attack-chain analysis, and model ablation studies |

These interests reflect my exploration of machine-learning approaches to cybersecurity. They are not claims of a completed or publicly released research system.

---

# 🖥️ Security Tooling & Lab Experience

I have worked with a range of security tools and platforms through hands-on learning, experimentation, and lab environments.

<div align="center">

<table>
  <tr>
    <th align="center">Category</th>
    <th align="center">Tools & Platforms</th>
  </tr>

  <tr>
    <td><b>SIEM & Security Monitoring</b></td>
    <td>Wazuh, Splunk</td>
  </tr>

  <tr>
    <td><b>Network Security</b></td>
    <td>Suricata, Nmap, Wireshark, Cisco Packet Tracer</td>
  </tr>

  <tr>
    <td><b>Security Automation & Case Management</b></td>
    <td>Shuffle, TheHive</td>
  </tr>

  <tr>
    <td><b>Search & Security Analytics</b></td>
    <td>OpenSearch, Tenzir</td>
  </tr>

  <tr>
    <td><b>Linux & Systems</b></td>
    <td>Linux, Bash, VirtualBox</td>
  </tr>

  <tr>
    <td><b>Cloud & Infrastructure</b></td>
    <td>AWS EC2, Docker</td>
  </tr>

  <tr>
    <td><b>Development & Analysis</b></td>
    <td>Python, Flask, Streamlit, Git, GitHub</td>
  </tr>
</table>

</div>

### Security Engineering Concepts

- Security event monitoring and analysis.
- Network traffic inspection and intrusion detection.
- Linux administration and system hardening.
- Vulnerability assessment and network enumeration.
- Endpoint telemetry and behavioral monitoring.
- Alert investigation and incident-response concepts.
- Security automation and tool integration.
- Detection rule development and controlled testing.

---

# 🎓 Certification

<div align="center">

  <img
    src="https://img.shields.io/badge/Red%20Hat-Certified%20System%20Administrator%20(RHCSA)-EE0000?style=for-the-badge&logo=redhat&logoColor=white"
    alt="Red Hat Certified System Administrator"
  />

</div>

### Red Hat Certified System Administrator (RHCSA)

Red Hat certification demonstrating Linux system administration knowledge and practical skills.

---

# 🧰 Technical Skills

<div align="center">

<table>
  <tr>
    <th>Domain</th>
    <th>Skills & Technologies</th>
  </tr>

  <tr>
    <td><b>Programming</b></td>
    <td>Python, C, C++, Java, SQL, Bash</td>
  </tr>

  <tr>
    <td><b>Cybersecurity</b></td>
    <td>Network Security, IDS/IPS, EDR Concepts, Security Monitoring, Threat Analysis, Vulnerability Assessment</td>
  </tr>

  <tr>
    <td><b>Network Analysis</b></td>
    <td>Scapy, Wireshark, Nmap, Packet Analysis, Network Enumeration</td>
  </tr>

  <tr>
    <td><b>Machine Learning</b></td>
    <td>Isolation Forest, One-Class SVM, RandomForest, Feature Engineering, Anomaly Detection</td>
  </tr>

  <tr>
    <td><b>Security Platforms</b></td>
    <td>Wazuh, Splunk, Suricata, Shuffle, TheHive, OpenSearch, Tenzir</td>
  </tr>

  <tr>
    <td><b>Systems & Cloud</b></td>
    <td>Linux Administration, Docker, AWS EC2, VirtualBox</td>
  </tr>

  <tr>
    <td><b>Development</b></td>
    <td>Flask, Streamlit, SQLite, MySQL, Git, GitHub</td>
  </tr>

</table>

</div>

---

## 💻 Technology Stack

<div align="center">

  <h3>Programming Languages</h3>

  <img
    src="https://skillicons.dev/icons?i=python,c,cpp,java,bash&theme=dark"
    alt="Python, C, C++, Java, and Bash"
  />

  <br/><br/>

  <h3>Frameworks, Libraries & Data</h3>

  <img
    src="https://skillicons.dev/icons?i=flask,sqlite,mysql,pandas,numpy,sklearn&theme=dark"
    alt="Flask, SQLite, MySQL, Pandas, NumPy, and scikit-learn"
  />

  <br/><br/>

  <h3>Infrastructure & Development</h3>

  <img
    src="https://skillicons.dev/icons?i=linux,docker,aws,prometheus,grafana,git,github&theme=dark"
    alt="Linux, Docker, AWS, Prometheus, Grafana, Git, and GitHub"
  />

  <br/><br/>

  <h3>Hardware & Platforms</h3>

  <img
    src="https://skillicons.dev/icons?i=arduino,raspberrypi,ubuntu,vscode&theme=dark"
    alt="Arduino, Raspberry Pi, Ubuntu, and Visual Studio Code"
  />

</div>

---

# 📊 GitHub Analytics

<div align="center">

  <!-- GitHub Statistics -->

  <img
    height="180"
    src="https://github-readme-stats.vercel.app/api?username=adicyb&show_icons=true&theme=tokyonight&hide_border=true"
    alt="GitHub statistics"
  />

  <!-- Most Used Languages -->

  <img
    height="180"
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=adicyb&layout=compact&theme=tokyonight&hide_border=true&langs_count=8"
    alt="Most used programming languages"
  />

  <br/><br/>

  <!-- Contribution Streak -->

  <img
    src="https://streak-stats.demolab.com?user=adicyb&theme=tokyonight&hide_border=true"
    alt="GitHub contribution streak"
  />

</div>

---

## 📈 Contribution Activity

<div align="center">

  <img
    src="https://github-readme-activity-graph.vercel.app/graph?username=adicyb&theme=tokyo-night&hide_border=true&area=true"
    width="100%"
    alt="GitHub contribution activity graph"
  />

</div>

---

## 🏆 GitHub Achievements

<div align="center">

  <img
    src="https://github-profile-trophy.vercel.app/?username=adicyb&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8&column=6"
    width="100%"
    alt="GitHub profile trophies"
  />

</div>

---

# 📫 Connect With Me

I'm interested in connecting with people working in cybersecurity, detection engineering, security operations, and applied machine learning.

I'm open to technical discussions, project collaboration, and internship opportunities related to cybersecurity engineering.

<div align="center">

  <a href="https://github.com/adicyb">
    <img
      src="https://img.shields.io/badge/GitHub-Explore%20My%20Projects-181717?style=for-the-badge&logo=github&logoColor=white"
      alt="Explore my GitHub projects"
    />
  </a>

  <a href="https://www.linkedin.com/in/aditya-khandelwal2006/">
    <img
      src="https://img.shields.io/badge/LinkedIn-Let's%20Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"
      alt="Connect on LinkedIn"
    />
  </a>

  <br/><br/>

  <a href="https://github.com/adicyb?tab=repositories">
    <img
      src="https://img.shields.io/badge/View-All%20Repositories-007f86?style=for-the-badge&logo=github&logoColor=white"
      alt="View all repositories"
    />
  </a>

</div>

---

<div align="center">

  <sub>
    Building practical cybersecurity systems through experimentation,
    engineering, and continuous learning.
  </sub>

  <br/><br/>

  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:007f86,45:1c3b57,100:0b132b&height=120&section=footer"
    width="100%"
    alt="Profile footer"
  />

</div>
