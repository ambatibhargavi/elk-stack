# ELK Stack with Filebeat & Logstash for Docker Logs

This project sets up the **ELK Stack (Elasticsearch, Logstash, Kibana)** along with **Filebeat** to collect and analyze logs from Docker containers.

## 📌 Architecture
1. **Filebeat** collects Docker container logs.
2. **Logstash** processes and enriches logs.
3. **Elasticsearch** stores indexed logs.
4. **Kibana** visualizes logs with dashboards.
![ScreenRecording2025-03-14at17 05 46-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/d0dd896f-481a-42ee-904d-dbcfa674c6ab)
## 📋 Prerequisites

Ensure you have the following installed:
- Docker & Docker Compose
- Elasticsearch, Logstash, Kibana (ELK Stack)
- Filebeat for log forwarding



## ⚙️ Setup

1️⃣ **Clone the repository**  
Clone the GitHub repository to your local machine.

2️⃣ **Update credentials in configuration files**  
Modify the necessary authentication details for Elasticsearch.

3️⃣ **Start the ELK Stack**  
Use Docker Compose to bring up the ELK stack services.

4️⃣ **Verify Elasticsearch is running**  
Ensure Elasticsearch is accessible and responding to queries.

5️⃣ **Check Filebeat logs**  
Monitor Filebeat logs to confirm successful log collection.


## 🔍 Viewing Logs in Kibana

- Open Kibana in your web browser.
- Navigate to **Discover** and select the appropriate index pattern.
- Analyze logs using Kibana’s visualization tools.


## 🛠 Configuration Overview

### **Filebeat Configuration**
Filebeat is set up to collect logs from Docker containers, enrich them with metadata, and forward them to Logstash or Elasticsearch.

### **Logstash Configuration**<img width="1434" alt="Screenshot 2025-03-13 at 20 16 02" src="https://github.com/user-attachments/assets/9a0c37e0-a1db-4f73-8c20-c4ca20dbab8b" />
<img width="1433" alt="Screenshot 2025-03-12 at 16 09 22" src="https://github.com/user-attachments/assets/ae9d7326-2fae-4a37-b503-f5f42f3e8af8" />

Logstash processes incoming logs, applies filters, and forwards structured data to Elasticsearch.

### **Docker Compose Setup**
The `docker-compose.yml` file defines the ELK stack services, including Elasticsearch, Kibana, Logstash, and Filebeat.


## 🚀 Contribution

Feel free to **fork** this repo, add improvements, and create a PR! 💡

### 🔗 Connect with Me
https://www.linkedin.com/in/ambatibhargavi/
![Screenshot 2025-03-13 at 21 00 40](https://github.com/user-attachments/assets/c1b5e7b4-c8dc-4deb-b20d-7ceb48a2872d)

<img width="1423" alt="Screenshot 2025-03-13 at 20 29 36" src="https://github.com/user-attachments/assets/2b6f34ba-0a63-4369-8369-d8bc8cd5b30e" />
<img width="1437" alt="Screenshot 2025-03-13 at 20 24 46" src="https://github.com/user-attachments/assets/6d3112f4-5f9b-4b79-9ca2-eb39e8c69c77" />
