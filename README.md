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

```bash
vi inventory
```

<p align="center">
  <img src="screenshots/04.png" width="900">
</p>



## ⚙ Ansible Configuration

Configured Ansible to use the local inventory and disabled host key checking.

```bash
vi ansible.cfg
```

<p align="center">
  <img src="screenshots/05.png" width="900">
</p>



## 📡 Connectivity Test

Verified connectivity using the Ansible Ping module.

```bash
ansible-navigator run ping.yml -m stdout
```

![](screenshots/06.png)

![](screenshots/07.png)



## 📦 Package Installation

Installed required packages using Ansible Playbooks.

```bash
ansible-navigator run packages.yml -m stdout
```

![](screenshots/08.png)

![](screenshots/09.png)



## 🚀 Apache Role Deployment

Executed Ansible Role for Apache installation and configuration.

```bash
ansible-navigator run myrole.yml -m stdout
```

![](screenshots/10.png)

## 📝 Issue File Configuration

Updated the `/etc/issue` file with environment-specific content for the **dev** and **test** groups using Ansible.

**Command**

```bash
ansible-navigator run issue.yml -m stdout
```

<p align="center">
<img src="screenshots/12.png" width="900">
</p>

---



## 🌐 Apache Service Verification

Verified Apache service status after deployment.

```bash
sudo systemctl status httpd
```

![](screenshots/11.png)



## 🛠 Custom Playbook Execution

Created custom web directory and deployed index page.

```bash
ansible-navigator run custom.yml -m stdout
```

![](screenshots/13.png)



## ✅ Localhost Verification

Verified Apache service and webpage output.

```bash
ls -ld /var/www/html
```
```bash
cat /webdev/index.html
```
```bash
sudo systemctl status httpd
```

![](screenshots/14.png)



## 📂 GitHub Repository

Successfully pushed the project to GitHub, making it accessible for version control, collaboration, and future updates.

The repository contains the complete source code, Ansible playbooks, roles, inventory, configuration files, screenshots, and project documentation.

![](screenshots/15.png)



## 🔄 Repository Clone

Successfully cloned the GitHub repository in the AWS Hyderabad Region to recreate the automation environment.

The cloned repository contains the complete project source code, Ansible playbooks, roles, inventory, configuration files, and documentation required to deploy the infrastructure.

### Clone Repository

```bash
git clone https://github.com/nandusivadas/AWS-Infrastructure-Automation-using-Ansible
```

![](screenshots/16.png)



## 🎉 Final Deployment Output

Apache website successfully deployed using reusable Ansible Roles.

![](screenshots/17.png)



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

Email id: nandusivadas98@gmail.com

Linkedln: www.linkedin.com/in/nandu-sivadas98
