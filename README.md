# Integrated Cybersecurity Risk Reduction Dashboard

## Overview
The **Integrated Cybersecurity Risk Reduction Dashboard** is a unified solution that integrates vulnerability scanning, threat intelligence correlation, and incident response into a streamlined pipeline. This project demonstrates actionable cybersecurity measures tailored for a hybrid environment, showcasing core skills in vulnerability management, threat intelligence, and incident response.

## Features
1. **Automated Vulnerability Data Collection**: Integration with a mock vulnerability scanner or dataset.
2. **Threat Intelligence Correlation**: Mapping vulnerabilities to threats using the MITRE ATT&CK framework.
3. **Incident Response Automation**: Basic response workflows, such as isolating vulnerable systems, using Ansible.
4. **Interactive Dashboard**: Visualization of risk metrics, including severity distribution, threat categories, and correlated vulnerabilities.
5. **Comprehensive Documentation**: Clear setup instructions, usage guidelines, and insights into each module.

---

## Tech Stack
- **Programming Language**: Python
- **Libraries**: Pandas, Requests, Streamlit, Plotly, Tabulate
- **Tools**:
  - Mock vulnerability scanner (e.g., Tenable.io dataset)
  - MITRE ATT&CK framework (CSV/JSON data)
  - Ansible for automation
- **Environment**: Docker (for consistent deployment)

---

## Directory Structure
```plaintext
/cyber-risk-reduction-dashboard
├── data/
│   ├── vulnerabilities.json       # Mock vulnerability data
│   ├── mitre.csv                  # MITRE ATT&CK dataset
├── scripts/
│   ├── vulnerability_parser.py    # Parses and normalizes vulnerability data
│   ├── threat_correlation.py      # Correlates vulnerabilities with threats
│   ├── isolate_system.yml         # Ansible playbook for incident response
├── dashboard/
│   ├── app.py                     # Streamlit-based interactive dashboard
├── docs/
│   ├── screenshots/               # Dashboard screenshots
├── requirements.txt               # Project dependencies
├── README.md                      # Project documentation
