# Apache_Airflow_Windows_without_Docker
Apache Airflow installation on Windows without Docker

Note: It's assumed you already have Ubuntu installed on your system.

As of Apache **Airflow 2.10.2**, the supported Python versions are:

**- Python 3.7
- Python 3.8
- Python 3.9
- Python 3.10
- Python 3.11**

**⚠️ Important Notes:**

- **Python 3.6** support was officially** dropped in Airflow 2.4.**
- **Python 3.7** support is expected to be dropped in future releases (possibly Airflow 3.0).
- Always refer to the official **Apache Airflow documentation** (https://airflow.apache.org/docs/apache-airflow/stable/installation/prerequisites.html) for the most up-to-date information on Python version compatibility.

**💡 How to Check Compatibility:**
Before installing, make sure your Python version is compatible with the Airflow version you're planning to use. You can check the Python version on your system with:







## Step 1: Install Python 3.9 on Ubuntu

![img_1_git](https://github.com/user-attachments/assets/879502bc-212a-4ae3-ae1a-848402d62e69)


## 🌐 Step 2: Set Up a Virtual Environment for Airflow
![img_2_git](https://github.com/user-attachments/assets/bfc1042c-ab00-4ad5-9a57-548af378acdc)


## 📦 Step 3: Install System-Level Dependencies for Airflow
Airflow may require certain system packages, especially on Ubuntu:
![img_3_git](https://github.com/user-attachments/assets/cd26d8c6-a326-42c1-b2f1-0acfd006fc20)


## ⚙️ Step 4: Install Apache Airflow
![img_4_git](https://github.com/user-attachments/assets/7f6b9a2f-826a-4c3c-b31e-12c8ca5449ee)


## 🗄️ Step 5: Initialize Airflow Database
To set up a SQLite database for development and testing:
![img_5_git](https://github.com/user-attachments/assets/09d293dd-5975-4b72-bd3d-309a7276bdfa)



## 👤 Step 6: Create Airflow User (Optional for Web UI Access)
To access the Airflow Web UI, you can create an admin user:

![img_6_git](https://github.com/user-attachments/assets/a05ed4f9-edb0-4010-9e4b-800387820441)


## 🚀 Step 7: Start Airflow Services
![img_7_git](https://github.com/user-attachments/assets/4d9f5d81-5c69-417a-b7b6-71045c72b669)



## 🌐 Step 8: Access Airflow Web UI
Open your browser and go to:



![img_8_git](https://github.com/user-attachments/assets/4c5ef6ae-34be-4c8b-8948-4af9be346ac9)



You should now see the Apache Airflow dashboard!





