
---

# DevOps Roadmap: Infrastructure & Automation (Windows-Native Edition)

## Layer 1: Yearly Mission (The 6-Month to 1-Year Horizon)

**Goal:** Become a Senior-level DevOps Engineer capable of designing, provisioning, and maintaining production-grade, automated environments in AWS.

* **Objective 1: End-to-End Automation:** Implement full **CI/CD Pipelines** (Jenkins/GitHub Actions) that handle the entire lifecycle—from code commit to production.
* **Objective 2: Reliable IaC:** Manage 100% of cloud resources using **Terraform**, ensuring environment consistency across Dev, Staging, and Production.
* **Objective 3: System Reliability:** Deploy a comprehensive **Observability** stack (CloudWatch, Prometheus, Grafana) for metrics and automated alerting.
* **Objective 4: Advanced Orchestration:** (Final Stage) Migrate specialized workloads to **Kubernetes (EKS)** for high-scale container management.

> **Mastery Check:** You can destroy an entire AWS environment and recreate it, including the networking, database, and application layers, using only code (**Terraform** + **Pipeline**) in under 30 minutes.

---

## Layer 2: Quarterly Goals (The 3-Month Horizon)

| Quarter | Strategic Focus | Key Deliverables |
| --- | --- | --- |
| **Q1** | **The Automation Foundation** | Setup **WSL 2**, master **Linux CLI**, **Git** workflows, and **Python** scripting basics. |
| **Q2** | **Infrastructure & CI/CD** | Master **AWS Core Services** (VPC, EC2, IAM) and **Terraform**. Build first **CI/CD Pipelines**. |
| **Q3** | **Containers & Observability** | Master **Docker** and **Docker Compose**. Implement centralized logging and metrics dashboards. |
| **Q4** | **Orchestration & Scale** | Master **Kubernetes (EKS)** fundamentals: Pods, Deployments, Services, and Helm. |

---

## Layer 3: Monthly Sprints (The 1-Month Horizon - First Quarter)

### Month 1: Version Control & Windows-DevOps Bridge

* **Focus:** Bridging **Windows** and **Linux** via **WSL 2** and mastering **Git**.
* **Key Tasks:** * Setup **WSL 2** (Ubuntu) and **Windows Terminal**.
* Integrate **VS Code** with the **WSL Remote** extension.
* Learn **Git** via CLI (no GUI allowed): Branching, **Merge Conflicts**, and **SSH Keys**.
* **Linux** basics: File system, permissions, and **Bash** scripting.


* **Mastery Check:** Create a **Bash** script inside **WSL** that automates the setup of a project folder, initializes a **Git Repo**, and pushes it to **GitHub**.

### Month 2: Python for Automation & AWS CLI

* **Focus:** Using **Python** (Boto3) and **AWS CLI** from within your Windows environment.
* **Key Tasks:** * Setup **AWS CLI** and configure **IAM Credentials**.
* Learn **Python** data structures (Lists, Dicts) for JSON parsing.
* Write scripts to automate **AWS** tasks (e.g., list all **S3 Buckets**, start/stop **EC2 Instances**).


* **Mastery Check:** Write a **Python** script that audits an **AWS Account** and lists all resources (EC2, S3) that don't have a "Cost-Center" tag.

### Month 3: Infrastructure as Code (Terraform) Essentials

* **Focus:** Moving from manual console clicks to **Terraform**.
* **Key Tasks:** * Understand **Terraform State**, **Providers**, and **Resources**.
* Write **Terraform** code to provision a full **VPC** (Public/Private Subnets, IGW, NAT).
* Deploy a **Web Server** on **EC2** with a **Security Group** using only **Terraform**.


* **Mastery Check:** Run `terraform apply` to build a network, server, and storage in **AWS**, then `terraform destroy` to clean it up perfectly.

---