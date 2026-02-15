
# 🏥 QuickTriage‑AI  
### AI-Based Smart Patient Triage & Appointment System

QuickTriage‑AI is an AI-powered healthcare management system that analyzes patient symptoms and vital parameters to classify risk levels, recommend appropriate medical departments, and assist hospitals in efficient patient prioritization and appointment management.

---

## 🚀 Problem Statement

Hospitals often rely on manual triage systems that do not prioritize patients based on medical urgency. This leads to:

- Delayed treatment for high-risk patients  
- Long waiting times  
- Inefficient resource utilization  
- Lack of real-time monitoring  
- Poor patient prioritization  

There is a need for an intelligent AI-based system that can analyze patient symptoms, classify risk levels, recommend departments, and improve hospital workflow efficiency.

---

## 💡 Proposed Solution

QuickTriage‑AI provides:

- 🟢 Risk Classification (Low / Medium / High)  
- 🏥 Automatic Department Recommendation  
- 🔍 Explainable AI Predictions with Confidence Score  
- 📅 Smart Appointment Booking  
- 📊 Real-time Hospital Dashboard  
- 📈 Priority-based Patient Sorting  

The system connects patient input, AI prediction, and hospital monitoring in real time.

---

## 🏗️ System Architecture

The architecture follows a layered approach connecting the user interface, AI logic, database, and visualization components.

---

## 🔄 Workflow

1. Patient enters medical details (Age, BP, Oxygen, Temperature, Symptoms).
2. System validates and processes the input.
3. AI model predicts the risk level.
4. Appropriate department is assigned.
5. Explanation and confidence score are generated.
6. Patient books appointment (optional).
7. Data is stored in the database.
8. Hospital dashboard updates in real time.
9. Patients are sorted in priority queue (High → Medium → Low).

---

## 🛠️ Technologies Used

- **Python** – Core programming logic  
- **Streamlit** – Frontend web interface  
- **SQLite** – Database management  
- **Pandas** – Data processing  
- **Plotly** – Data visualization  
- **Machine Learning Logic** – Risk classification  

---

## 📊 Key Features

### 👤 Patient Portal
- Enter health parameters  
- Predict risk level  
- View recommended specialist  
- See explanation & confidence score  
- Book appointment  

### 🏥 Hospital Staff Dashboard
- Live risk statistics  
- Risk distribution pie chart  
- Department workload bar chart  
- Priority queue sorting  
- Booked appointments list  

---

## 📁 Database Structure

### Patients Table
- Risk Level  
- Department  
- Oxygen Level  
- Confidence Score  

### Appointments Table
- Department  
- Appointment Date  
- Appointment Time  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/QuickTriage-AI.git
cd QuickTriage-AI
pip install -r requirements.txt
streamlit run app.py
live : https://quicktriage-ai-v4nqb8b7amui5awnfvvbex.streamlit.app/

