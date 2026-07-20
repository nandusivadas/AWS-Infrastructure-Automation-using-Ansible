# 🚀 AWS Infrastructure Automation using Ansible

### Multi-Region Infrastructure Automation with AWS EC2, Ansible Navigator, Docker & GitHub

<p align="center">

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![EC2](https://img.shields.io/badge/EC2-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Amazon Linux](https://img.shields.io/badge/Amazon%20Linux-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

</p>



# 📖 Project Overview

This project demonstrates **Infrastructure Automation** using **Ansible Navigator**, **Docker**, and **GitHub** across two AWS regions.

The automation was first developed in the **Mumbai Region** and pushed to GitHub. The same repository was then cloned into the **Hyderabad Region**, where the playbooks were reused to automate a second environment. This project showcases Infrastructure as Code (IaC), reusable automation, and version-controlled deployments.



# 🏗 Project Architecture

<p align="center">
<img src="screenshots/01.png" width="900">
</p>



# ✨ Features

- Multi-Region Deployment
- Infrastructure as Code (IaC)
- Ansible Navigator
- Docker Execution Environment
- SSH Automation
- GitHub Version Control
- Inventory Management
- Apache Deployment
- Package Automation
- Role-Based Automation



# 🛠 Technologies Used

| Category | Technology |
|-----------|------------|
| Cloud | AWS EC2 |
| Operating System | Amazon Linux 2023 |
| Automation | Ansible Navigator |
| Container | Docker |
| Version Control | Git & GitHub |
| Configuration | YAML |
| Connectivity | SSH |



# 📁 Project Structure

```text
Ansible-Automation-Project/
│
├── roles/
│     └── myrole/
│
├── ansible.cfg
├── inventory
├── packages.yml
├── issue.yml
├── custom.yml
├── myrole.yml
├── README.md
└── screenshots/
```



# ⚙ Workflow

## Mission 1 - Mumbai Region

- Configure Control Node
- Configure Inventory
- Establish SSH Connectivity
- Create Ansible Playbooks
- Execute Playbooks
- Push Project to GitHub

## Mission 2 - Hyderabad Region

- Launch Control Node
- Clone Repository from GitHub
- Update Inventory
- Execute Existing Playbooks
- Verify Successful Deployment



# 📸 Project Screenshots

## ☁ AWS Infrastructure

Control Node and Client instances running successfully.

![](screenshots/02.png)



## 🔐 SSH Authentication

Passwordless SSH connection established between Control Node and Client instances.

![](screenshots/03.png)



## 📄 Inventory Configuration

Configured inventory with Dev and Test groups.

![](screenshots/04.png)



## ⚙ Ansible Configuration

Configured Ansible to use the local inventory and disabled host key checking.

![](screenshots/05.png)



## 📡 Connectivity Test

Verified connectivity using the Ansible Ping module.

![](screenshots/06-ping.png)

![](screenshots/07-ping-result.png)



## 📦 Package Installation

Installed required packages using Ansible Playbooks.

![](screenshots/08-packages.png)

![](screenshots/09-packages-result.png)



## 🚀 Apache Role Deployment

Executed Ansible Role for Apache installation and configuration.

![](screenshots/10-role.png)



## 🌐 Apache Service Verification

Verified Apache service status after deployment.

![](screenshots/11.png)



## 🛠 Custom Playbook Execution

Created custom web directory and deployed index page.

![](screenshots/12.png)



## ✅ Localhost Verification

Verified Apache service and webpage output.

![](screenshots/13.png)



## 📂 GitHub Repository

Successfully pushed the project to GitHub.

![](screenshots/14.png)



## 🔄 Repository Clone

Successfully cloned the repository in the Hyderabad Region.

![](screenshots/15.png)



## 🎉 Final Deployment Output

Apache website successfully deployed using reusable Ansible Roles.

![](screenshots/16.png)



# 📂 Repository Contents

- Ansible Configuration
- Inventory File
- Playbooks
- Roles
- GitHub Integration
- Screenshots



# 📚 Learning Outcomes

- AWS EC2 Administration
- Infrastructure Automation
- Ansible Playbooks
- Ansible Roles
- Docker Execution Environment
- GitHub Version Control
- SSH Authentication
- Multi-Region Deployment



# 🚀 Future Improvements

- Dynamic Inventory
- Ansible Galaxy Roles
- CI/CD Integration
- Terraform Automation
- AWS Systems Manager Integration

---

# 👨‍💻 Author

**Nandu Sivadas**

Cloud & DevOps Enthusiast

GitHub: https://github.com/nandusivadas
