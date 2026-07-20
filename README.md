<div align="center">

# 🚀 AWS Infrastructure Automation using Ansible

### Automating AWS EC2 Infrastructure Deployment with Ansible & Docker

<p>
<img src="https://img.shields.io/badge/AWS-EC2-orange?style=for-the-badge&logo=amazonaws">
<img src="https://img.shields.io/badge/Automation-Ansible-red?style=for-the-badge&logo=ansible">
<img src="https://img.shields.io/badge/Platform-Amazon%20Linux%202023-yellow?style=for-the-badge&logo=amazonlinux">
<img src="https://img.shields.io/badge/Container-Docker-blue?style=for-the-badge&logo=docker">
<img src="https://img.shields.io/badge/Version%20Control-Git-black?style=for-the-badge&logo=git">
</p>

**Infrastructure Automation • Configuration Management • AWS • DevOps**

</div>


# 📖 Project Overview

This project demonstrates how to automate the deployment and configuration of multiple AWS EC2 instances using **Ansible**. The automation includes infrastructure provisioning, passwordless SSH authentication, package installation, Apache web server deployment, reusable Ansible Roles, and infrastructure recreation in another AWS Region using GitHub.

The project is divided into two missions:

- **Mission 1** – Build and automate a complete Ansible environment.
- **Mission 2** – Recreate the same infrastructure in a new AWS Region using the existing Git repository.



# 🎯 Objectives

- Deploy AWS EC2 infrastructure
- Configure passwordless SSH authentication
- Install Docker and Ansible Navigator
- Create reusable Ansible Playbooks
- Build reusable Ansible Roles
- Deploy Apache automatically
- Store the project in GitHub
- Clone and recreate the environment in another AWS Region



# 🏗️ Architecture Diagram

![Architecture Diagram](screenshots/01.png)



# ⚙️ Technologies Used

| Technology | Purpose |
|------------|---------|
| AWS EC2 | Cloud Infrastructure |
| Amazon Linux 2023 | Operating System |
| Ansible | Configuration Management |
| Ansible Navigator | Playbook Execution |
| Docker | Execution Environment |
| SSH | Secure Communication |
| Apache HTTP Server | Web Server |
| Git | Version Control |
| GitHub | Source Code Repository |



# ✨ Key Features

- Infrastructure automation using Ansible
- Passwordless SSH configuration
- Inventory management
- Docker-based Ansible execution
- Apache deployment using Roles
- Jinja2 templates
- Git-based infrastructure recreation
- Multi-region deployment
- Automated server configuration



# 📂 Repository Structure

```text
AWS-Infrastructure-Automation-using-Ansible
│
├── architecture/
├── docs/
├── inventory/
├── playbooks/
├── roles/
├── templates/
├── screenshots/
├── ansible.cfg
└── README.md
```



# 🔄 Workflow

```text
Launch EC2 Instances
        │
        ▼
Create Users
        │
        ▼
Configure SSH Keys
        │
        ▼
Install Docker
        │
        ▼
Install Ansible Navigator
        │
        ▼
Configure Inventory
        │
        ▼
Execute Playbooks
        │
        ▼
Deploy Apache
        │
        ▼
Push to GitHub
        │
        ▼
Clone Repository
        │
        ▼
Recreate Infrastructure
```



# 🚀 Project Workflow

## Mission 1

- Launch AWS EC2 instances
- Configure the Control Node
- Configure Client Nodes
- Install Docker
- Install Ansible Navigator
- Configure Inventory
- Create Playbooks
- Create Roles
- Deploy Apache
- Push project to GitHub



## Mission 2

- Launch a new AWS environment
- Clone the GitHub repository
- Update inventory
- Verify SSH connectivity
- Execute Ansible Playbooks
- Verify successful deployment




# 📸 Project Screenshots

### ☁️ AWS Infrastructure

Launched the AWS EC2 Control Node and Managed Nodes required for the automation environment. The infrastructure consists of one Control Node and two Client Nodes running in the Mumbai Region.

![AWS Infrastructure](screenshots/02.png)



### 🔑 Passwordless SSH Authentication
Verifies successful SSH connectivity between the control node and managed nodes.

![SSH Authentication](screenshots/03.png)



### 📋 Ansible Inventory Configuration
Static inventory configured for managing AWS EC2 instances.

![Inventory Configuration](screenshots/03.png)



### ✅ Ansible Connectivity Test
Successful `ansible all -m ping` verification.

![Ansible Connectivity](screenshots/04.png)



### 🌐 Apache Web Server Deployment
Apache installed and configured automatically using Ansible.

![Apache Deployment](screenshots/05.png)



### 🖥️ Web Server Verification
Default Apache web page successfully served from the managed node.

![Web Server Output](screenshots/06.png)



### 🚀 Mission 2 Infrastructure Recreation
Infrastructure recreated successfully in a new AWS Region using the cloned GitHub repository and Ansible playbooks.

![Mission 2 Deployment](screenshots/07.png)



# 📚 Skills Demonstrated

- AWS EC2
- Amazon Linux
- Linux Administration
- Docker
- Ansible
- Ansible Navigator
- SSH Authentication
- Infrastructure Automation
- Apache Administration
- Git & GitHub



# 📄 Documentation

Complete project documentation is available in the **docs/** directory.



# 🎯 Learning Outcomes

- Automated AWS infrastructure deployment
- Reduced manual server configuration
- Implemented Infrastructure as Code
- Reused automation across AWS Regions
- Improved deployment consistency
- Built reusable Ansible Roles and Playbooks



# 👨‍💻 Author

## Nandu Sivadas

**Cloud & DevOps Enthusiast**

- GitHub: https://github.com/nandusivadas
- LinkedIn: *(Add your LinkedIn profile)*

---

<div align="center">

⭐ If you like this project, don't forget to star the repository.

</div>
