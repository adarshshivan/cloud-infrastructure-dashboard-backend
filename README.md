# 🧩 Cloud Infrastructure Dashboard – Backend  

## Author: Adarsh Shivan  
## Part of: CloudOps Suite  

---

### ⚙️ Overview  
The **Cloud Infrastructure Dashboard Backend** is the **core data service** that powers the frontend dashboard.  
It fetches, structures, and prepares **AWS resource data** (EC2, S3, IAM, etc.) to be consumed by the frontend UI.  

This backend demonstrates how real cloud monitoring systems work — built using **AWS CLI**, **Python**, and **Linux automation scripts**, following DevOps-aligned workflows.  

---

### 🧠 Learning Outcomes  
🔹 Learn to **interact with AWS resources** via the AWS CLI.  
🔹 Understand **IAM permissions** and roles for secure data access.  
🔹 Automate **data fetching and transformation** for cloud dashboards.  
🔹 Practice **bash scripting** for command execution and output parsing.  
🔹 Simulate **end-to-end cloud monitoring pipelines** without direct SDK integration.  

---

### 🧩 Tech Stack  

| Layer | Technology Used |
|:------|:----------------|
| **Language** | Python |
| **Cloud Platform** | AWS (EC2, S3, IAM) |
| **Automation Tools** | AWS CLI, Bash Scripts |
| **Data Format** | JSON |
| **Environment** | Linux |
| **Version Control** | Git & GitHub |
| **Deployment** | AWS Console & CLI Integration |

---

## 🧱 Architecture  


### AWS Resources → AWS CLI Commands → JSON Output → Backend Scripts → Frontend Dashboard


1. AWS CLI Commands collect real resource details.

2. Bash scripts automate data fetching and organize JSON output.

3. Python processing scripts structure data into a unified format.

4. Frontend fetches this processed JSON for visualization

---

## 🧾 Features

- ✅ Fetches live-like AWS data (EC2 & S3) through CLI commands
- ✅ Automates process via Bash scripting
- ✅ Stores resource data in real_dashboard_data.json
- ✅ Provides reusable JSON structure for visualization
- ✅ Demonstrates secure IAM configuration best practices

---

## 📸 Backend Execution Screenshots

| No. | Screenshot Description        |
| :-: | :---------------------------- |
|  01 | 01-AWS-CLI-INSTALLED          |
|  02 | 02-IAM-User-Creation-Name     |
|  03 | 03-IAM-User-Policies          |
|  04 | 04-IAM-AccessKey-Created      |
|  05 | 05-AWS-CLI-Configured         |
|  06 | 06-EC2-Launch-Page            |
|  07 | 07-EC2-Configuration          |
|  08 | 08-EC2-Running                |
|  09 | 09-EC2-Describe-Instances     |
|  10 | 10-S3-Bucket-Config           |
|  11 | 11-S3-Bucket-List             |
|  12 | 12-IAM-Add-Permissions        |
|  13 | 13-IAM-S3FullAccess-Attached  |
|  14 | 14-S3-Upload-Success          |
|  15 | 15-S3-Bucket-File-List        |
|  16 | 16-Boto3-Installed            |
|  17 | 17-Boto3-STS-Verified         |
|  18 | 18-EC2-Data-Fetched           |
|  19 | 19-EC2-Data-File              |
|  20 | 20-AWS-Full-Data              |
|  21 | 21-AWS-Data-File              |


🖼️ Each screenshot is placed inside the /screenshots directory in this repository for detailed workflow reference.

---

## 🧠 Future Enhancements

- Add API layer using Flask/FastAPI for dynamic data fetch

- Integrate CloudWatch metrics for deeper insights

- Store and visualize metrics over time

- Enable real-time updates from AWS using event triggers

---

## 🏁 Conclusion

This backend system forms the foundation of the Cloud Infrastructure Dashboard, connecting AWS resource data with a user-friendly visualization layer.
It showcases end-to-end AWS understanding, DevOps automation, and data handling proficiency — perfect for cloud portfolio presentation.

---

## 🔗 Related Repositories

### 👉 Frontend Repository:

🔗 [Cloud Infrastructure Dashboard Frontend](https://github.com/adarshshivan/cloud-infrastructure-dashboard-frontend)

---

### ☁️ Part of the CloudOps Suite



