# 🗣️ Our Voice, Our Rights  
### Transparency Platform for MGNREGA District Performance — Maharashtra  

> Empowering citizens to easily understand how their district is performing under the **Mahatma Gandhi National Rural Employment Guarantee Act (MGNREGA)** using open government data.

---

## 🌍 Overview

The Government of India provides MGNREGA performance data via an [Open API on data.gov.in](https://www.data.gov.in/catalog/mahatma-gandhi-national-rural-employment-guarantee-act-mgnrega).  
However, most citizens in rural areas cannot access or interpret raw API data.  
This project bridges that gap by offering a **simple, bilingual (English + Marathi)** web dashboard that visualizes district-level MGNREGA performance for **Maharashtra**.

---

## 🎯 Features

✅ Citizens can select their **district** and view:
- Total number of households benefiting from MGNREGA  
- Employment days generated  
- Fund utilization & progress over time  
- Comparative insights across districts  
- Bilingual display (English + Marathi)  
- Optional **voice output** for low-literacy users  

✅ **Technical Highlights**
- ETL Worker (Python) fetches & caches data from data.gov.in  
- ExpressJS Backend with PostgreSQL + Redis cache  
- React Frontend with chart visualizations and local language support  
- Dockerized microservices for production reliability  
- Fallback system for when the data.gov.in API is offline  
- Map view using LeafletJS (GeoJSON overlay for Maharashtra)  

---

## 🧩 Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | React + Chart.js + LeafletJS |
| Backend | Node.js (Express) |
| Database | PostgreSQL (with optional PostGIS) |
| Worker | Python (ETL cron) |
| Caching | Redis |
| Deployment | Docker & Docker Compose |
| Hosting | Render / VPS (Ubuntu) |

---

## 🏗️ Project Structure

