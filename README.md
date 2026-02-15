# Hi, I'm Chinmay Jog! 👋

## 🚀 DevOps & Cloud Infrastructure Engineer

I am a **seasoned IT professional with over 20 years of experience**, specializing in bridging legacy infrastructure and modern Cloud-Native ecosystems. Throughout my career, I've worn many hats—Support Engineer, Systems Administrator, Technical Consultant, DevOps Engineer, Cloud Architect, and Technical Manager.

---

### 🏛️ Solution Architecture

I have organized my work into two primary **Integrated Solutions** and one supporting **Toolkit**:

#### 🏢 Solution A: Enterprise LAMP Hosting (VM-Based)
*A complete legacy-to-cloud transition showcase.*
- **[azure-lamp-hosting (IaC)](https://github.com/chinmaymjog/azure-lamp-hosting)**: The foundational multi-tier Azure infrastructure.
- **[jenkins-ansible (Control Plane)](https://github.com/chinmaymjog/jenkins-ansible)**: The self-service dashboard for managing the platform.

#### ☸️ Solution B: Modern WP Ecosystem (K8s-Based)
*A cloud-native scalability and standardization showcase.*
- **[aks-tf (Infrastructure)](https://github.com/chinmaymjog/aks-tf)**: Enterprise AKS landing zone following hub-and-spoke networking.
- **[wordpress-boilerplate (Ecosystem)](https://github.com/chinmaymjog/wp-boilerplate)**: Standardization for high-traffic CMS deployments.

#### 🛠️ Supporting Layer: DevOps Toolkit
*The "Glue" for both solutions.*
- **[devops-toolkit](https://github.com/chinmaymjog/cicd-toolkit)**: Reusable CI/CD templates for both VM and K8s environments.

---

### 📊 Other Projects
- **[AzRBAC-Insight](https://github.com/chinmaymjog/AzRBAC-Insight)**: Automated Azure Governance and RBAC auditing.
- **[cis-ubuntu24-hardening](https://github.com/chinmaymjog/cis-ubuntu24-hardening)**: Security compliance automation.

---

## 🚀 Zero-Touch Deployment Guide

This portfolio is designed to be deployed as a cohesive ecosystem. To get started:

1.  **Foundational IaC**: Start with **[azure-lamp-hosting](https://github.com/chinmaymjog/azure-lamp-hosting)**. Run `ssh-keygen -t rsa -f webadmin_rsa` in `terraform/`, then `terraform apply`.
2.  **VM Control Plane**: Terraform generates `hosts` and `database_vars.yml`. Copy these (and your private key) to the **[jenkins-ansible/ansible](https://github.com/chinmaymjog/jenkins-ansible)** directory and run `docker compose up -d`.
3.  **Cloud-Native Scale**: Deploy the **[aks-tf](https://github.com/chinmaymjog/aks-tf)** landing zone. It generates a `.wp-env` file.
4.  **App Deployment**: Copy the `.wp-env` to the **[wp-boilerplate](https://github.com/chinmaymjog/wp-boilerplate)** directory and run the `deploy` scripts to launch your K8s-based WordPress ecosystem.

---

### 🧰 Technical Toolbelt
...
- **Cloud & OS:** ![Azure](https://img.shields.io/badge/Azure-0078D4?logo=Microsoft-Azure) ![AWS](https://img.shields.io/badge/AWS-FF9900?logo=Amazon-Web-Services) ![GCP](https://img.shields.io/badge/GCP-4285F4?logo=Google-Cloud-Platform) ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?logo=ubuntu) ![Linux](https://img.shields.io/badge/Linux-05122A?logo=linux)
- **IaC & Automation:** ![Terraform](https://img.shields.io/badge/Terraform-623CE4?logo=terraform) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?logo=ansible)
- **Containerization:** ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes)
- **CI/CD:** ![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?logo=gitlab) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-24292E?logo=GitHub)
- **Observability:** ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus) ![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana) ![Elasticsearch](https://img.shields.io/badge/Elasticsearch-F46800?logo=elasticsearch)

---

### 📫 Connect with me:
- **Medium**: [Read my technical deep-dives](https://medium.com/@chinmaymjog)
- **LinkedIn**: [Chinmay Jog](https://www.linkedin.com/in/chinmaymjog/)
- **Email**: [chinmaymjog@gmail.com](mailto:chinmaymjog@gmail.com)

<!-- Add your GitHub Stats or Top Languages here if you like! -->
