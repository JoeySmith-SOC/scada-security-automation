# SCADA Security & Automation

## 🔐 Project Overview

This project demonstrates practical techniques for securing SCADA systems in industrial environments. It is divided into two key phases:

- **Phase 1: SCADA Security Enhancement**
  - Network segmentation using VLANs and firewalls
  - Role-based access control
  - Intrusion detection via Snort
  - Traffic analysis with Wireshark

- **Phase 2: ICS Process Automation**
  - Python and Ansible-based automation scripts
  - Secure task scheduling and configuration deployment
  - Log parsing and behavior monitoring
  - Grafana integration for dashboards

## 🛠️ Technologies Used

- Python 3.x
- Ansible
- iptables
- Snort IDS
- Wireshark
- Grafana
- Modbus tools
- VirtualBox (for simulation)

## 📁 Project Structure

```bash
scada-security-automation/
├── diagrams/
│   └── network-architecture.png
├── scripts/
│   ├── plc_task_scheduler.py
│   └── log_parser.py
├── playbooks/
│   └── secure_deploy.yml
├── docs/
│   └── full_documentation.md
├── logs/
│   └── snort_alerts.log
├── LICENSE
├── .gitignore
└── README.md
