# docker-workshop
workshop codespaces

#  Dockerized Data Ingestion Pipeline

## 📌 Overview
This project demonstrates a **production-style data ingestion pipeline** that processes large-scale taxi trip data and loads it into a PostgreSQL database.

The pipeline is fully containerized using Docker, making it portable, reproducible, and easy to deploy.

---

##  Problem Statement
Handling large datasets efficiently and loading them into a database can be slow and error-prone when done manually.

This project solves that by:
- Automating data ingestion
- Processing data in chunks
- Ensuring consistent deployment using Docker

---

## 🏗️ Architecture

---

## ⚙️ Technologies Used

-  Python  
-  pandas  
-  PostgreSQL  
-  SQLAlchemy  
-  Docker  
-  pgAdmin  

---

## 🔧 Features

- ✅ Chunk-based data ingestion for large files  
- ✅ PostgreSQL database integration  
- ✅ Dockerized environment for portability  
- ✅ CLI parameterization for flexible execution  
- ✅ Persistent storage using Docker volumes  

---

## ▶️ How It Works

1. The script downloads or reads taxi trip data  
2. Data is processed in chunks using pandas  
3. Each chunk is inserted into PostgreSQL  
4. pgAdmin is used to visualize and manage the database  

---

