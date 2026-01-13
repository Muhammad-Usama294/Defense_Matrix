# 🛡️ CyberAI Orchestrator - Defense Matrix

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-1.x-red.svg)
![AI](https://img.shields.io/badge/AI-Cybersecurity-green.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)

> **AI Agent Selection & Decision Support Framework**

A Streamlit-based cybersecurity orchestration platform for selecting and managing AI security agents. This project implements an intelligent decision support framework that helps security operations centers (SOCs) select the optimal AI-powered security agent for specific threat scenarios using multi-criteria decision analysis.

---

## 👥 Authors

This project is developed as part of the **Information Security** course project by:

- **Muhammad Usama** (SP23-BCS-021)
- **Muhammad Ehsan Mumtaz** (SP23-BCS-039)  
- **Aoun Muhammad** (SP23-BCS-111)

**Course:** Information Security  
**Section:** BCS-6A  
**Year:** 2025

---

## ✨ Features

### 🤖 25+ AI Security Agents Database

The framework includes a comprehensive database of industry-leading AI security agents:

- **CrowdStrike Falcon XDR** - Advanced endpoint detection and response
- **Darktrace Enterprise Immune** - AI-powered threat detection
- **Microsoft Defender AI** - Integrated threat protection
- **Vectra AI Cognito** - Network detection and response
- **SentinelOne Singularity** - Autonomous endpoint protection
- **Proofpoint Email Defense** - Email security and protection
- **Palo Alto Cortex XDR** - Extended detection and response
- **Splunk UEBA** - User and entity behavior analytics
- **IBM QRadar SIEM** - Security information and event management
- **Cloudflare Magic Firewall** - Network security
- **Abnormal Security** - Behavioral AI email security
- **Cybereason Defense Platform** - Endpoint protection
- **Cisco SecureX** - Integrated security platform
- **Fortinet FortiAI** - AI-driven security
- **Trellix XDR** - Extended detection and response
- **Exabeam UEBA** - User behavior analytics
- **Zscaler Zero Trust** - Zero trust security
- **TrendMicro Vision One** - Unified cybersecurity platform
- **Rapid7 InsightIDR** - Detection and response
- **Sophos Intercept X** - Next-gen endpoint security
- **Carbon Black Cloud** - Cloud-native endpoint protection
- **Securonix UEBA** - Security analytics
- **Symantec Endpoint Security** - Comprehensive endpoint protection
- **Chronicle Security** - Security analytics platform
- **Arctic Wolf MDR** - Managed detection and response

### 🚨 Threat Detection & Analysis

Comprehensive threat type coverage:

- **Ransomware** - File encryption attacks with ransom demands
- **Malware** - Malicious software infections
- **Advanced Persistent Threats (APT)** - Long-term targeted intrusions
- **Insider Threats** - Malicious internal actor activities
- **Phishing** - Credential harvesting via email campaigns
- **Lateral Movement** - Network propagation detection
- **Data Exfiltration** - Unauthorized data transfers
- **C2 Communication** - Command and control traffic
- **Zero-Day Exploits** - Unknown vulnerability exploitation
- **Credential Theft** - Account credentials compromise
- **Business Email Compromise** - Executive email takeovers
- **Privilege Escalation** - Unauthorized privilege elevation
- **DDoS Attacks** - Distributed denial of service
- **Web Application Attacks** - SQL injection, XSS detection
- **Bot Attacks** - Automated malicious traffic

### 🎯 Agent Selection Algorithm

Advanced multi-criteria decision making system:

- **Performance Metrics Analysis** - Comprehensive evaluation of agent capabilities
- **Cost-Benefit Optimization** - Balance between effectiveness and cost
- **Threat Coverage Mapping** - Match agents to specific threat types
- **False Positive Rate Analysis** - Minimize alert fatigue
- **Response Time Calculation** - Optimize incident response speed
- **Confidence Scoring** - AI-powered recommendation confidence levels

### 📊 Interactive Dashboard

Real-time visualization and analysis:

- **Threat Landscape Overview** - Visual threat severity indicators
- **Agent Performance Visualization** - Radar charts and comparative analysis
- **Top 5 Agent Recommendations** - Ranked by comprehensive scoring algorithm
- **Response Time Comparison** - Manual vs automated decision-making
- **Performance Metrics Display** - Effectiveness, speed, and cost analysis
- **PDF Report Generation** - Exportable incident response playbooks

### 📈 Performance Metrics

Each agent is evaluated across multiple dimensions:

- **Effectiveness Score** (0-1) - Detection accuracy and success rate
- **Speed Rating** (1-10) - Response time and processing speed
- **False Positive Rate** (0-1) - Error rate and alert accuracy
- **Cost Analysis** (USD/month) - Monthly licensing and operational costs
- **Coverage Mapping** - Threat types each agent can handle

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **Python 3.x** | Core programming language |
| **Streamlit** | Interactive web application framework |
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical computing and calculations |
| **Plotly** | Interactive data visualizations (Graph Objects & Express) |
| **FPDF** | PDF report generation |

---

## 🏗️ System Architecture

```
Defense_Matrix/
├── 📊 AI Agent Database
│   ├── 25+ Security Agents
│   ├── Performance Metrics
│   └── Threat Coverage Maps
│
├── 🧠 Decision Engine
│   ├── Multi-criteria Analysis Algorithm
│   ├── Scoring Formula Implementation
│   └── Optimization Engine
│
├── 📈 Visualization Layer
│   ├── Interactive Dashboard
│   ├── Real-time Performance Charts
│   ├── Radar Plot Comparisons
│   └── Response Time Analytics
│
└── 📄 Report Generator
    ├── PDF Playbook Creation
    ├── Threat Analysis Reports
    └── Agent Recommendations
```

---

## 🚀 Installation

### Prerequisites

- Python 3.x or higher
- pip package manager

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/Muhammad-Usama294/Defense_Matrix.git
   cd Defense_Matrix
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

   Required dependencies:
   - `streamlit` - Web application framework
   - `pandas` - Data manipulation
   - `numpy` - Numerical computing
   - `plotly` - Interactive visualizations
   - `fpdf` - PDF generation

---

## ▶️ How to Run

Launch the Streamlit application:

```bash
streamlit run project.py
```

The application will start and automatically open in your default web browser at:
```
http://localhost:8501
```

---

## 📖 Usage Guide

### 1. Select Threat Type
- Choose from 15 threat categories in the sidebar
- View threat severity and description
- Use "Random Attack" for quick testing

### 2. Analyze Alert
- Click "▶️ Analyze Alert" to run the decision engine
- Watch the real-time analysis process
- View comprehensive agent recommendations

### 3. Review Recommendations
- Examine top 5 recommended agents
- Compare performance metrics using radar charts
- Review effectiveness, speed, and cost data
- Check expected containment times

### 4. Generate Reports
- Click "Download PDF Incident Response Playbook"
- Export complete analysis with recommendations
- Share with security team members

### 5. Compare Response Times
- View automated vs manual decision-making times
- Calculate time savings per incident
- Optimize SOC operations efficiency

---

## 🗄️ Agent Database Schema

Each AI security agent in the database follows this structure:

```python
{
    "id": int,                      # Unique agent identifier
    "name": str,                    # Agent product name
    "effectiveness": float,         # Detection accuracy (0-1)
    "speed": float,                 # Response time rating (1-10)
    "fp_rate": float,              # False positive rate (0-1)
    "cost": float,                 # Monthly cost (USD)
    "coverage": str                # Comma-separated threat types
}
```

### Example Entry
```python
{
    "id": 1,
    "name": "CrowdStrike Falcon XDR",
    "effectiveness": 0.95,
    "speed": 8.5,
    "fp_rate": 0.02,
    "cost": 850,
    "coverage": "ransomware,malware,apt,lateral_movement"
}
```

---

## 📊 Key Metrics Explained

### Effectiveness Score (0-100%)
- Measures detection accuracy and success rate
- Higher values indicate better threat detection
- Based on real-world performance data

### Speed Rating (1-10)
- Response time and processing speed
- 10 = Fastest response time
- 1 = Slowest response time

### False Positive Rate (0-100%)
- Percentage of incorrect threat alerts
- Lower values are better (less alert fatigue)
- Critical for SOC efficiency

### Cost (USD/month)
- Monthly licensing and operational costs
- Includes subscription and maintenance
- Used in cost-benefit optimization

### Coverage
- List of threat types the agent can detect
- Direct coverage provides better results
- Multiple coverage areas increase versatility

---

## 🖼️ Screenshots

### Dashboard Overview
![Dashboard Overview](docs/screenshots/dashboard.png)
*Main dashboard showing threat selection and system information*

### Agent Selection Interface
![Agent Selection](docs/screenshots/agent-selection.png)
*Interactive agent selection with real-time analysis*

### Performance Comparison
![Performance Charts](docs/screenshots/performance-comparison.png)
*Radar charts comparing agent metrics*

### Report Preview
![PDF Report](docs/screenshots/report-preview.png)
*Generated incident response playbook*

> 📝 **Note:** Screenshots are illustrative. The actual interface may vary based on the latest version.

---

## 📚 Academic Paper

This implementation is based on the research paper:

**"A Cybersecurity AI Agent Selection and Decision Support Framework (2025)"**

The paper presents a novel approach to autonomous threat response through intelligent agent selection using multi-criteria decision analysis and machine learning techniques.

### Scoring Formula

The framework implements the following scoring algorithm:

```python
Score = (Effectiveness × 10) + 
        (Speed × 1.2) + 
        (FP_penalty × 0.8) + 
        (Coverage_bonus × 15) - 
        (Cost / 100)

where:
- FP_penalty = 1 / (FP_rate + 0.01)
- Coverage_bonus = 1.0 (direct) or 0.3 (indirect)
```

---

## 🔮 Future Enhancements

### Planned Features

- 🤖 **Machine Learning-Based Recommendations**
  - Train models on historical incident data
  - Predictive agent selection
  - Adaptive learning from outcomes

- 🌐 **Real-Time Threat Intelligence Integration**
  - Connect to external threat feeds
  - Dynamic agent database updates
  - Live threat landscape monitoring

- 🏢 **Multi-Organization Deployment**
  - Support for multiple tenants
  - Organization-specific configurations
  - Centralized management dashboard

- 📈 **Advanced Reporting & Analytics**
  - Trend analysis over time
  - Historical performance tracking
  - ROI calculations and cost savings

- 🔌 **API Integration**
  - RESTful API for agent management
  - Webhook support for alerts
  - Integration with existing SIEM/SOAR platforms

- 🎯 **Custom Agent Profiles**
  - User-defined agents and metrics
  - Import/export agent databases
  - Community-shared agent profiles

- 🔐 **Enhanced Security Features**
  - Role-based access control
  - Audit logging
  - Encrypted agent configurations

---

## 🤝 Contributing

We welcome contributions to the Defense Matrix project! Here's how you can help:

### Contribution Guidelines

1. **Fork the Repository**
   ```bash
   git fork https://github.com/Muhammad-Usama294/Defense_Matrix.git
   ```

2. **Create a Feature Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make Your Changes**
   - Follow existing code style
   - Add comments for complex logic
   - Update documentation as needed

4. **Test Your Changes**
   - Ensure the application runs without errors
   - Test all modified functionality
   - Verify UI/UX consistency

5. **Submit a Pull Request**
   - Provide a clear description of changes
   - Reference any related issues
   - Include screenshots for UI changes

### Areas for Contribution

- 🐛 Bug fixes and error handling
- ✨ New features and enhancements
- 📝 Documentation improvements
- 🎨 UI/UX enhancements
- 🧪 Testing and quality assurance
- 🌐 Localization and translations

---

## 📄 License

This project is licensed under the **MIT License**.

```
MIT License

Copyright (c) 2025 Muhammad Usama, Muhammad Ehsan Mumtaz, Aoun Muhammad

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🙏 Acknowledgments

### Special Thanks To

- **Information Security Course Instructors** - For guidance and support throughout the project
- **BCS-6A Classmates** - For valuable feedback and suggestions
- **Open Source Community** - For the amazing tools and libraries used in this project
- **Cybersecurity Research Community** - For inspiring this decision support framework

### Inspired By

- Academic research in AI-driven cybersecurity
- Real-world SOC operational challenges
- Industry best practices in threat detection and response

---

## 📞 Contact & Support

### Project Team

- **Muhammad Usama** - [@Muhammad-Usama294](https://github.com/Muhammad-Usama294)
- **Muhammad Ehsan Mumtaz** - Project Collaborator
- **Aoun Muhammad** - Project Collaborator

### Get Help

- 🐛 **Report Bugs:** Open an issue on GitHub
- 💡 **Feature Requests:** Submit an issue with the enhancement label
- 📧 **Email Support:** Contact through university email
- 💬 **Discussions:** Use GitHub Discussions for questions

---

## 📈 Project Status

![GitHub last commit](https://img.shields.io/github/last-commit/Muhammad-Usama294/Defense_Matrix)
![GitHub issues](https://img.shields.io/github/issues/Muhammad-Usama294/Defense_Matrix)
![GitHub pull requests](https://img.shields.io/github/issues-pr/Muhammad-Usama294/Defense_Matrix)

**Current Version:** 1.0.0  
**Status:** Active Development  
**Last Updated:** January 2025

---

## 🌟 Star History

If you find this project useful, please consider giving it a star ⭐ on GitHub!

---

<div align="center">

### Made with ❤️ for Cybersecurity

**Defense Matrix** | **CyberAI Orchestrator** | **Information Security BCS-6A**

🛡️ Protecting the Digital World, One Agent at a Time 🛡️

</div>
