# ðŸš€ DevOps Laboratory Experiments 

<div align="center">



<br/>

[![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)](https://git-scm.com/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/)
[![Apache Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)](https://maven.apache.org/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/)
[![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)](https://www.ansible.com/)
[![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)](https://www.jenkins.io/)
[![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white)](https://gradle.org/)
[![Java](https://img.shields.io/badge/Java%2017-ED8B00?style=flat-square&logo=openjdk&logoColor=white)](https://openjdk.org/)
[![Status](https://img.shields.io/badge/Lab%20Status-Complete%20%26%20Verified-success?style=flat-square)](#)

<p align="center">
  <b>Comprehensive repository containing source code, configurations, automation scripts, and detailed execution guides for all 7 DevOps laboratory experiments.</b>
</p>

</div>

---

## ðŸ“– Course Overview
- **Course Title:** DevOps Laboratory / DevOps Tools & Techniques (DTT)
- **Course Outcome:** **P405.1** - Apply modern DevOps practices including Distributed Version Control, Automated Build Systems, Containerization, Configuration Management, and Continuous Integration & Deployment (CI/CD) pipelines.
- **Repository Maintainer:** **Hari Saravanan M** ([@harisaravananm](https://github.com/harisaravananm))

---

## ðŸ“‘ Index of Experiments

| Ex. No | Experiment Title | Primary Tools | Directory Link | Status |
|:---:|:---|:---:|:---:|:---:|
| **01** | **Git Version Control & Branch Management**<br>_Initializing, cloning, staging, committing, pushing, and branching._ | `Git`, `CLI` | [ðŸ“‚ Experiment-01-Git](./Experiment-01-Git) | âœ… Completed |
| **02** | **Apache Maven & Java Project Setup**<br>_Installing Maven, standard project hierarchy, `pom.xml`, compile, test, package._ | `Maven`, `Java 17`, `JUnit` | [ðŸ“‚ Experiment-02-Maven](./Experiment-02-Maven) | âœ… Completed |
| **03** | **Docker Container Installation & Management**<br>_Pulling images, running containers, interactive shells, resource management._ | `Docker`, `Docker Desktop`, `Alpine` | [ðŸ“‚ Experiment-03-Docker](./Experiment-03-Docker) | âœ… Completed |
| **04** | **Ansible YAML Playbook Automation**<br>_Inventory creation, declarative playbooks, tasks, variables, and idempotency._ | `Ansible`, `YAML`, `Python` | [ðŸ“‚ Experiment-04-Ansible](./Experiment-04-Ansible) | âœ… Completed |
| **05** | **Jenkins CI/CD Pipeline (Maven + Docker)**<br>_Declarative pipeline with Checkout, Maven Build, and Docker Image creation._ | `Jenkins`, `Maven`, `Docker` | [ðŸ“‚ Experiment-05-Jenkins](./Experiment-05-Jenkins) | âœ… Completed |
| **06** | **GitHub Account, Repository Creation & App Push**<br>_Remote hosting, Personal Access Tokens, local-to-remote tracking, verification._ | `GitHub`, `Git`, `Java` | [ðŸ“‚ Experiment-06-GitHub](./Experiment-06-GitHub) | âœ… Completed |
| **07** | **Building Application Using Gradle**<br>_Gradle DSL, application plugin, tasks execution, dependency management, JAR build._ | `Gradle`, `Groovy DSL`, `Java` | [ðŸ“‚ Experiment-07-Gradle](./Experiment-07-Gradle) | âœ… Completed |

---

## ðŸ“ Repository Directory Structure

```text
DevOpslab_exp/
â”œâ”€â”€ docs/                                   # Official College Manuals & Expected Outputs
â”‚   â”œâ”€â”€ DTT lab manual 2026-27 final rec.pdf
â”‚   â”œâ”€â”€ DTT lab manual 2026-27.docx
â”‚   â””â”€â”€ DevOps_2026_27_Experiment_Outputs.docx
â”‚
â”œâ”€â”€ Experiment-01-Git/                      # Ex 1: Git Version Control
â”‚   â”œâ”€â”€ README.md                           # Comprehensive guide & verified outputs
â”‚   â”œâ”€â”€ git_demo.sh                         # Linux/Git Bash automation script
â”‚   â”œâ”€â”€ git_demo.bat                        # Windows CMD automation script
â”‚   â””â”€â”€ sample-project/                     # Demo project with sample code & .gitignore
â”‚
â”œâ”€â”€ Experiment-02-Maven/                    # Ex 2: Apache Maven
â”‚   â”œâ”€â”€ README.md                           # Step-by-step procedure & output logs
â”‚   â”œâ”€â”€ pom.xml                             # Configured Maven POM with plugins & dependencies
â”‚   â”œâ”€â”€ build.bat / build.sh                # 1-Click build & test runner scripts
â”‚   â””â”€â”€ src/                                # Application code (main) & unit tests (test)
â”‚
â”œâ”€â”€ Experiment-03-Docker/                   # Ex 3: Docker Containers
â”‚   â”œâ”€â”€ README.md                           # Docker architecture & command reference
â”‚   â”œâ”€â”€ Dockerfile                          # Production-ready containerfile
â”‚   â”œâ”€â”€ docker-compose.yml                  # Declarative orchestration file
â”‚   â”œâ”€â”€ docker_commands.bat / .sh           # Reference execution scripts
â”‚   â””â”€â”€ app/index.html                      # Sample web application served by container
â”‚
â”œâ”€â”€ Experiment-04-Ansible/                  # Ex 4: Ansible Automation
â”‚   â”œâ”€â”€ README.md                           # Playbook guide, modules & idempotency demo
â”‚   â”œâ”€â”€ hosts.ini / ansible.cfg             # Inventory and Ansible runtime settings
â”‚   â”œâ”€â”€ setup.yml                           # Standard Ansible playbook from lab manual
â”‚   â”œâ”€â”€ setup_windows.yml                   # Windows-adapted playbook
â”‚   â””â”€â”€ simulate_ansible.py                 # Standalone Python runner simulating execution
â”‚
â”œâ”€â”€ Experiment-05-Jenkins/                  # Ex 5: Jenkins CI/CD Pipeline
â”‚   â”œâ”€â”€ README.md                           # Pipeline architecture & Jenkins UI guide
â”‚   â”œâ”€â”€ Jenkinsfile                         # Declarative CI/CD pipeline script
â”‚   â”œâ”€â”€ pom.xml / Dockerfile                # Build descriptors for pipeline stages
â”‚   â”œâ”€â”€ docker-compose-jenkins.yml          # Ready-to-run containerized Jenkins server
â”‚   â””â”€â”€ src/main/java/.../DevOpsApp.java    # Source code tested in pipeline
â”‚
â”œâ”€â”€ Experiment-06-GitHub/                   # Ex 6: GitHub Cloud Push
â”‚   â”œâ”€â”€ README.md                           # Account, PAT auth, and remote push guide
â”‚   â”œâ”€â”€ HelloWorld.java                     # Application code from lab syllabus
â”‚   â””â”€â”€ setup_and_push.bat / .sh            # Interactive automated Git push helpers
â”‚
â””â”€â”€ Experiment-07-Gradle/                   # Ex 7: Gradle Build System
    â”œâ”€â”€ README.md                           # Gradle DSL reference & tasks guide
    â”œâ”€â”€ build.gradle / settings.gradle      # Build script with application plugin
    â”œâ”€â”€ build.bat / build.sh                # Build and execution helper scripts
    â””â”€â”€ src/                                # Java source and unit test suites
```

---

## ðŸ’» Prerequisites & Environment Setup

### 1. Git Installation
- **Windows:** Download and install from [git-scm.com](https://git-scm.com/download/win).
- **Linux:**
  ```bash
  sudo apt update && sudo apt install -y git
  ```
- **Configuration:**
  ```bash
  git config --global user.name "Your Name"
  git config --global user.email "you@example.com"
  ```

### 2. Java Development Kit (JDK 17)
- **Windows:** Download Temurin OpenJDK 17 or Oracle JDK 17 and configure `JAVA_HOME`.
- **Linux:**
  ```bash
  sudo apt install -y openjdk-17-jdk
  export JAVA_HOME=/usr/lib/jvm/java-17-openjdk-amd64
  ```

### 3. Apache Maven
- Download binary ZIP from [maven.apache.org](https://maven.apache.org/download.cgi), extract, and add the `bin` directory to `PATH`.
- Verify: `mvn -version`.

### 4. Gradle
- Download binary ZIP from [gradle.org/releases](https://gradle.org/releases/), extract, and add `bin` to `PATH`.
- Verify: `gradle -version`.

### 5. Docker Desktop / Engine
- **Windows:** Install Docker Desktop with WSL2 backend.
- **Linux:** Install via `get-docker.sh` and enable the service:
  ```bash
  curl -fsSL https://get.docker.com -o get-docker.sh && sudo sh get-docker.sh
  sudo usermod -aG docker $USER
  ```

### 6. Ansible
- Install on Linux or Windows WSL2:
  ```bash
  sudo apt install -y ansible
  # OR via pip:
  pip install ansible
  ```

### 7. Jenkins
- Run natively or with Docker:
  ```bash
  docker run -d -p 8080:8080 -p 50000:50000 --name jenkins jenkins/jenkins:lts-jdk17
  ```

---

## ðŸŽ¯ Program Outcomes (PO) & Program Specific Outcomes (PSO) Mapping

On completion of this laboratory curriculum, the following outcomes are attained:

| Course Outcome | PO1 | PO2 | PO3 | PO4 | PO5 | PO6 | PO7 | PO8 | PO9 | PO10 | PO11 | PO12 | PSO1 | PSO2 | PSO3 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:----:|:----:|:----:|:----:|:----:|:----:|
| **P405.1** | **3** | **3** | **3** | **3** | **3** | **2** | **2** | **2** | **3** | **3** | **3** | **3** | **3** | **2** | **3** |

*Key:* `3` = Substantial (High) Mapping, `2` = Moderate (Medium) Mapping, `1` = Slight (Low) Mapping.

---

## ðŸš€ How to Clone and Use This Repository

```bash
# 1. Clone the repository
git clone https://github.com/harisaravananm/DevOpslab_exp.git

# 2. Navigate into the repository
cd DevOpslab_exp

# 3. Explore any experiment folder
cd Experiment-02-Maven
mvn clean package
```

---