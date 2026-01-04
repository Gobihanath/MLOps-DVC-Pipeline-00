# MLOps DVC Pipeline

This repository demonstrates a **basic MLOps pipeline using DVC (Data Version Control)**.  
It shows how to create a **reproducible machine learning workflow** where data, models, and pipeline stages are tracked properly.

The goal of this project is to help beginners understand:
- How DVC pipelines work
- How reproducibility is achieved in ML projects
- Basic MLOps workflow structure

---

## 📌 Project Features
- Reproducible ML pipeline using **DVC**
- Pipeline stages defined in `dvc.yaml`
- Data and model versioning
- Simple and easy-to-follow setup

---



## 🚀 Getting Started

Follow the steps below to run the project locally.

---

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Gobihanath/MLOps-DVC-Pipeline-00.git
cd MLOps-DVC-Pipeline-00



python -m venv venv


venv\Scripts\activate


source venv/bin/activate


pip install -r requirements.txt



dvc init


dvc repro

