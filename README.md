# 👋 Bhaumik Yadav

**Software Engineer | ML Systems & Backend Architecture**

*Bridging the gap between Jupyter Notebooks and production environments.*

I am a Hybrid Engineer specialized in building high-throughput, memory-efficient AI systems. Currently a **Programmer Analyst at Argusoft** and Lead at **DataVerse (600+ members)**. I build systems where scale, latency, and cost are the primary constraints.

---

## 🚀 Selected Engineering Impact

### ⚖️ **plAIntiff: Quantized Legal Retrieval (RAG)**
*Engineered a memory-optimized RAG pipeline for large-scale legal corpora.*
- **The "Why":** Standard FP32 embeddings created a memory bottleneck that exceeded available hardware limits.
- **Engineering Wins:**
  - Implemented **4-bit scalar quantization**, reducing memory footprint by **75%** with negligible loss in Recall@10.
  - Optimized retrieval using **Memory Mapped Indexing (Mmap)**, enabling search across datasets larger than available RAM.
  - Designed an **Async FastAPI gateway** with Redis-backed task queuing to prevent GPU OOM (Out of Memory) errors during concurrent requests.
- **Stack:** Python, PyTorch, FAISS, FastAPI, Docker.

---

### 📊 **HR Intelligence: Decision-Support Attrition Pipeline**
*An end-to-end predictive system for workforce risk management and retention strategy.*
- **The "Why":** Raw attrition models in notebooks provide zero value to HR managers; they need actionable dashboards that interpret "risk" in real-time.
- **Engineering Wins:**
  - **Full-Stack Integration:** Architected a complete pipeline from automated data cleaning to a live **Flask/React** interface, ensuring non-technical stakeholders could interact with model outputs.
  - **Explainable AI (XAI):** Integrated feature-importance visualization into the dashboard, allowing HR to see *why* an employee was flagged as high-risk (e.g., overtime, tenure, or pay).
  - **Business Intelligence Sync:** Built a connector for **Power BI** to merge model predictions with existing corporate KPIs for executive-level reporting.
- **Stack:** Python, Scikit-learn, Flask, Power BI, JavaScript.

---

### 🔥 **Real-Time CV: Disaster Detection Pipeline**
*High-concurrency object detection for real-world environmental monitoring.*
- **Optimization:** Achieved a **40% reduction in inference latency** by migrating models to **TensorRT** and **ONNX** runtimes.
- **Deployment:** Containerized with Docker for seamless scaling on cloud GPU instances.
- **Stack:** YOLOv8, TensorRT, ONNX, FastAPI.

---

## 📊 Technical Arsenal

| Category | Technologies |
| :--- | :--- |
| **Languages** | **Python** (High-Performance ML), **Java** (Enterprise Backend/Spring), JavaScript |
| **ML/Ops** | PyTorch, YOLOv8, LangChain, RAG, TensorRT, Quantization (4-bit/8-bit) |
| **System Design** | **FastAPI** (Async), **Spring Boot**, Redis, PostgreSQL, Docker, Kubernetes |
| **Cloud & Infra** | Google Cloud (Cloud Run), AWS, Docker |

---

## 🌍 Community & Leadership

- **Lead @ DataVerse:** Managing a community of **600+ developers**, coordinating technical workshops on RAG architectures and full-stack development.
- **The "Big Picture" View:** I bring a high-level perspective to system architecture—literally.

---

## 🎯 Contact & Profiles

- **LinkedIn:** [theprofessional-bhaumik-yadav](https://www.linkedin.com/in/theprofessional-bhaumik-yadav/)
- **GitHub:** [bhaumikmango](https://github.com/bhaumikmango)

---

## ⚡ Out of Work

- Hike  
- Exercise  
- Doing math problems for fun

---

>I enjoy building things that live outside a notebook.
