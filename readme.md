<div align="center">

# ISP Network Automation using Python and n8n

<br>

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.x-blue)
![Docker](https://img.shields.io/badge/docker-enabled-2496ED)
![n8n](https://img.shields.io/badge/n8n-workflows-orange)
![Platform](https://img.shields.io/badge/platform-linux%20%7C%20windows-lightgrey)
![Status](https://img.shields.io/badge/status-active-success)

</div>

A hybrid network automation project designed for ISP and enterprise environments using **Python**, **n8n**, and network automation workflows.

This repository focuses on automating repetitive network operations such as:

- Device monitoring
- SSH automation
- Scheduled tasks
- Configuration backups
- Log collection
- Workflow orchestration
- Alerting and notifications
- API-based automation
- Infrastructure management

---

# Features

- Python-based network automation scripts
- n8n workflow orchestration
- SSH automation for routers/switches
- Task scheduling and automation
- REST API integrations
- Scalable workflow design
- Modular architecture
- Automation for ISP operational tasks
- Logging and monitoring support

---

# Technologies Used

- Python 3
- n8n
- Netmiko
- Paramiko
- REST APIs
- Docker
- Linux
- SSH
- JSON/YAML
- GitHub Actions (optional)

---

# Project Structure

```bash
ISP-Network-automation-using-Python-and-n8n/
│
├── scripts/              # Python automation scripts
├── workflows/            # n8n workflow files
├── configs/              # Device configs/templates
├── logs/                 # Automation logs
├── docker/               # Docker related files
├── requirements.txt      # Python dependencies
└── README.md
```

---

# Installation

## 1. Clone the Repository

```bash
git clone https://github.com/Ishaan2005/ISP-Network-automation-using-Python-and-n8n-.git

cd ISP-Network-automation-using-Python-and-n8n-
```

---

## 2. Create Virtual Environment

### Linux/macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

### Windows

```powershell
python -m venv venv
venv\Scripts\activate
```

---

## 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Docker Setup

Run the project using Docker:

```bash
docker compose up -d
```

---

# n8n Integration

This project uses **n8n** for workflow orchestration and automation pipelines.

Example workflow capabilities:

- Scheduled backups
- Automated SSH execution
- Device health monitoring
- Ticketing integration
- Alert notifications
- Data parsing and reporting

To import workflows:

1. Open n8n
2. Go to **Workflows**
3. Click **Import**
4. Select the workflow JSON file from `/workflows`

---

# Example Use Cases

## Device Configuration Backup

Automatically:

- Connect to devices via SSH
- Execute backup commands
- Save configurations
- Store logs
- Trigger alerts on failure

---

## Monitoring Workflow

- Ping devices periodically
- Check service availability
- Generate alerts
- Send notifications to Telegram/Discord/Email

---

# Security Notes

- Never commit credentials
- Use `.env` files for secrets
- Use SSH keys whenever possible
- Restrict API access
- Follow least privilege principles

---

# Future Improvements

- Grafana integration
- Prometheus monitoring
- AI-assisted anomaly detection
- Multi-vendor device support
- NetBox integration
- Kubernetes deployment
- Web dashboard
- Real-time telemetry

---

# Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

# License

This project is licensed under the MIT License.

---

# Author

**Ishaan Bhimajiyani**

- GitHub: https://github.com/Ishaan2005

---

# ⭐ Support

If you found this project useful:

- Star the repository
- Share it with others
- Contribute to the project
