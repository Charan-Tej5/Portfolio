# Hi, I'm Charan Tej 

Computer Science Engineering | AI & Machine Learning

## Featured Projects

### 1. Identity Sprawl Privilege Abuse Detection
Built an enterprise security pipeline that detects risky user accounts across systems like AWS IAM, Active
Directory, and Okta
• Combined rule-based scoring, ML anomaly detection (Isolation Forest), and graph analysis to generate a risk score
per user in under 5 seconds
• Used Claude API with async concurrent calls to auto-generate JSON incident reports with remediation
recommendations
• Built a Flask dashboard with interactive privilege graph visualization and analyst false-positive feedback

Tech: Python, Flask, Scikit-learn, NetworkX, Claude API

[[View Project →](https://github.com/Charan-Tej5/IDENTITY-SPRAWL-PRIVILEGE-ABUSE-DETECTION)]

---

### 2. Mini Distributed Cloud Platform
Built a distributed cloud platform across 4 machines simulating AWS compute, storage, and serverless execution
with custom-built orchestration in Python
• Implemented a resource-aware task scheduler and heartbeat-based dead node detection to distribute workloads and
handle failures automatically
• Designed chunked file storage with 2× replication and background re-replication when nodes go down, with MD5
checksum verification
• Set up Prometheus and Grafana for real-time cluster monitoring with structured JSON logging across all nodes

Tech: Python, FastAPI, Docker, Redis, PostgreSQL

[[View Project →](https://github.com/theabhishekc/distributed_cloud_platform)]

---
