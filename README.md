# DevOps CI/CD Pipeline Project

## 📌 Project Overview
This project demonstrates a complete **CI/CD pipeline implementation** using Jenkins.  
The pipeline automates the process of **code integration, build, testing, and deployment** to ensure fast and reliable software delivery.

---

## 🏗️ Architecture


The CI/CD pipeline follows a multi-stage Jenkins workflow:

1. Developer commits code to GitHub
2. Jenkins triggers pipeline automatically
3. Source code is pulled from GitHub
4. Build and quality checks using Apache Ant
5. Automated testing using JUnit
6. Deployment to Apache Tomcat server
7. Test results are generated and published
   
<img width="1536" height="1024" alt="Project1" src="https://github.com/user-attachments/assets/1b5bddda-8180-4c91-900e-3b7f7aea1cd4" />


---

## 🛠️ Tools & Technologies
- **Jenkins** – CI/CD automation
- **Git & GitHub** – Version control
- **Apache Ant** – Build automation
- **JUnit** – Unit testing
- **Apache Tomcat** – Application server
- **Java** – Application development

---

## ⚙️ Jenkins Pipeline Jobs
| Job Name     | Description |
|--------------|------------|
| FirstJob     | Pulls source code from GitHub |
| SecondJob    | Builds project and checks quality using Ant |
| ThirdJob     | Executes automated test cases using JUnit |
| FourthJob    | Deploys application to Tomcat server |

---

## 🔌 Jenkins Plugins Used
- GitHub Plugin  
- Ant Plugin  
- JUnit Plugin  
- Deploy to Container Plugin  
- Pipeline Plugin  

---

## 📋 Prerequisites
- Git installed and configured  
- Java installed and configured  
- Apache Tomcat installed  
- Jenkins installed and running  
- Apache Ant configured  
- GitHub repository access  

---

## 🚀 How to Run the Project
1. Clone the GitHub repository
   ```bash
   git clone <repository-url>
