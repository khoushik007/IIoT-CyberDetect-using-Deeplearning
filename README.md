# IIoT-CyberDetect-using-DeepLearning  

A **trustworthy and reliable deep-learning-based Intrusion Detection System (IDS)** for the **Industrial Internet of Things (IIoT)**.  
A deep-learning-based Intrusion Detection System (IDS) for the Industrial Internet of Things (IIoT) that uses Pyramidal Recurrent Units (PRUs) and Decision Trees to find cyberattacks in real time and with high accuracy. It gets 97% or more of the answers right, has few false positives, and can be deployed at the edge. 

---

## 🚀 Features  
- 🔐 **Cyberattack Detection** – Identifies DoS, reconnaissance, command injection, spoofing, and more.  
- ⚡ **Hybrid Deep Learning Model** – Combines PRUs (temporal learning) with DTs (interpretability & stability).  
- 📊 **High Accuracy** – Achieved **97%+ accuracy** on benchmark SCADA-IIoT datasets.  
- ⏱ **Real-time & Lightweight** – Optimized for edge/fog deployment.  
- 🌐 **Protocol-Agnostic** – Works across Modbus, DNP3, MQTT, and more.  
- 📈 **Visualization** – Displays detection ratios and accuracy with clear graphs.  

---

## 🏗 System Architecture  
![Architecture](trustworthy_and_reliable_deep_learning/Template/images/bg.jpg)  

---

## 🖼 Screenshots  

### 🔑 Login Page  
![Login](trustworthy_and_reliable_deep_learning/Template/images/Login.jpg)  

### 📝 Register Page  
![Register](trustworthy_and_reliable_deep_learning/Template/images/Register.jpg)  

---

## ⚙️ Tech Stack  
- **Programming Language:** Python  
- **Frameworks:** Django, Scikit-learn  
- **Database:** MySQL  
- **Machine Learning:** PRU (Pyramidal Recurrent Units), Decision Trees, SVM, Logistic Regression, DNN  
- **Visualization:** Matplotlib, Django Templates  

---

## 📂 Project Structure  
├── trustworthy_and_reliable_deep_learning/

│ ├── Template/

│ │ ├── images/ # Screenshots and background images

│ │ ├── *.html # Frontend templates

│ ├── models/ # ML/DL models

│ ├── views.py # Django views

│ ├── urls.py # URL routes

│ ├── settings.py # Django project settings

│ └── ...

├── requirements.txt

├── README.md

---

## 🛠 Installation & Setup  

### 1️⃣ Clone the Repository  

git clone https://github.com/<khoushik007>/IIoT-CyberDetect-using-DeepLearning.git
cd IIoT-CyberDetect-using-DeepLearning

## Install Dependencies
pip install -r requirements.txt

## Setup Database (MySQL)
Create a database:
CREATE DATABASE trustworthy_and_reliable_deep_learning;
Update settings.py with your MySQL credentials.

## Run the Server
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

## Access the Application
Open your browser and go to:
👉 http://127.0.0.1:8000/

📊 Results
Accuracy: 97.85%
Low False Positive Rate compared to traditional IDS
Tested on 15+ benchmark SCADA-IIoT datasets

Sample Result Visualization:
Attack Types Detected: 
- DoS: 25%
- Reconnaissance: 20%
- Command Injection: 30%
- Spoofing: 25%

## 🔮 Future Enhancements
Integration with Federated Learning for privacy-preserving training.
Deployment in Docker/Kubernetes for scalability.
Incorporation of Explainable AI (XAI) for better interpretability.
