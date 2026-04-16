# 🌿 Mental Health Hub

A web application that helps students track and improve their mental health through **self-assessment modules** and **professional guidance**.  
This project promotes mental well-being and awareness through a digital, interactive platform.

---

## 🧩 Project Overview

The system provides a centralized platform where users can assess their mental health, access guidance, and manage their well-being effectively.

---

## 🚀 Features

- User registration and login  
- Mental health self-assessment modules  
- Personalized recommendations and guidance  
- Dashboard for tracking progress  
- User-friendly and responsive interface  

---

## 🧰 Tech Stack

- **Backend:** Java, Spring MVC, Servlet  
- **Frontend:** JSP, HTML, CSS  
- **Build Tool:** Maven  
- **Database:** MySQL  

---

## 💾 Installation & Setup

Follow these steps to set up the project locally:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Abdur009/Mental-Health-Literacy-Hub.git
   ```

2. **Navigate to the Project Directory**
   ```bash
   cd mental-health-hub
   ```

3. **Build the Project**
   ```bash
   mvn clean install
   ```

4. **Deploy to Apache Tomcat**
  - Locate the generated `.war` file in the `target/` folder.
  - Deploy it to your Tomcat server (either viea IDE or Tomcat Manager)

5. **Database Setup**
  - create database "mentalhealth_db" inside your MySQL server
  - export file "db.sql" into your database

---

## 🌐 Running the Application
Once the project is successfully deployed, open your browser and navigate to:

```bash
http://localhost:8585/mental-health-literacy-hub/
```

**⚠️ NOTE:**
The port (**8585**) may differ based on your Tomcat server configuration.
