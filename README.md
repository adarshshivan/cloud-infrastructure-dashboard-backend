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

```text
AWS Resources → AWS CLI Commands → JSON Output → Backend Scripts → Frontend Dashboard

AWS CLI Commands collect real resource details.

Bash scripts automate data fetching and organize JSON output.

Python processing scripts structure data into a unified format.

Frontend fetches this processed JSON for visualization

🧾 Features

✅ Fetches live-like AWS data (EC2 & S3) through CLI commands
✅ Automates process via Bash scripting
✅ Stores resource data in real_dashboard_data.json
✅ Provides reusable JSON structure for visualization
✅ Demonstrates secure IAM configuration best practices


📸 Backend Execution Screenshots

| No. | Screenshot Description        |
| :-: | :---------------------------- |
|  1  | AWS IAM Configuration         |
|  2  | EC2 Instance Setup            |
|  3  | S3 Bucket Creation            |
|  4  | AWS CLI Configuration         |
|  5  | Verifying AWS Identity        |
|  6  | Listing EC2 Instances         |
|  7  | Listing S3 Buckets            |
|  8  | Fetching EC2 Instance Details |
|  9  | Fetching S3 Bucket Details    |
|  10 | Combining JSON Data           |
|  11 | Bash Script Execution         |
|  12 | Generated Output File         |
|  13 | Data Validation               |
|  14 | Folder Structure Overview     |
|  15 | Python Data Formatter Script  |
|  16 | Resource Summary              |
|  17 | Linux Environment Output      |
|  18 | Final JSON Data Ready         |
|  19 | Integration with Frontend     |
|  20 | AWS Console Verification      |
|  21 | Final Backend Output Preview  |


🖼️ Each screenshot is placed inside the /screenshots directory in this repository for detailed workflow reference.


🔗 Related Repositories
Component	Repository Link
Frontend	Cloud Infrastructure Dashboard Frontend

🧠 Future Enhancements

Add API layer using Flask/FastAPI for dynamic data fetch

Integrate CloudWatch metrics for deeper insights

Store and visualize metrics over time

Enable real-time updates from AWS using event triggers


🏁 Conclusion

This backend system forms the foundation of the Cloud Infrastructure Dashboard, connecting AWS resource data with a user-friendly visualization layer.
It showcases end-to-end AWS understanding, DevOps automation, and data handling proficiency — perfect for cloud portfolio presentation.

📸 Screenshot Summary

Total Screenshots: 21

Directory: /screenshots

Type: AWS Console + CLI Outputs

Created with 💻 by Adarsh Shivan

☁️ Part of the CloudOps Suite Project Collection