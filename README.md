# 🩺 FastAPI Patient Health Analyzer

A **FastAPI-based project** that analyzes patient health data and provides **BMI (Body Mass Index) insights** to help assess patient wellness efficiently.

---

## 🚀 Features

- 🧠 Calculates **BMI (Body Mass Index)** from height and weight  
- 📊 Provides **health insights** such as "Underweight", "Normal", "Overweight", or "Obese"  
- 💾 Stores and manages patient data in a JSON file (`patients.json`)  
- ⚡ Built using **FastAPI** for high performance and clean API structure  
- 🧩 Utilizes **Pydantic** models for validation and structured data handling  

---

## 🗂️ Project Structure
FastAPI-Patient-Health-Analyzer/
├── main.py # Main FastAPI application file
├── patients.json # JSON data file for patients
├── requirements.txt # List of dependencies
├── .gitignore # Ignored files for Git
├── Pydantic/ # Folder containing Pydantic models
└── pycache/ # Compiled Python cache files


---

## 🧰 Tech Stack

- **Language:** Python 🐍  
- **Framework:** FastAPI  
- **Data Model:** Pydantic  
- **Storage:** JSON  
- **Environment:** Virtual Environment (`venv` / `myenv`)

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/jenamjain/FastAPI-Patient-Health-Analyzer.git
cd FastAPI-Patient-Health-Analyzer

2️⃣ Create and activate a virtual environment
# Create a virtual environment
python -m venv myenv

# Activate the environment
# On macOS/Linux:
source myenv/bin/activate

# On Windows:
myenv\Scripts\activate

3️⃣ Install dependencies
pip install -r requirements.txt


4️⃣ Run the FastAPI server
uvicorn main:app --reload

Now open your browser and visit:
👉 http://127.0.0.1:8000

5️⃣ Explore the API documentation
FastAPI automatically generates interactive docs:


Swagger UI → http://127.0.0.1:8000/docs


ReDoc → http://127.0.0.1:8000/redoc



🧪 Example API Endpoints
MethodEndpointDescriptionGET/patientsGet all patient recordsPOST/patientsAdd a new patient recordGET/patients/{id}Retrieve a specific patient by IDDELETE/patients/{id}Delete a patient record

🧮 Example BMI Insights
BMI RangeCategory< 18.5Underweight18.5 – 24.9Normal weight25 – 29.9Overweight≥ 30Obese

🌟 Future Enhancements


Add database integration (SQLite / PostgreSQL)


Include additional health metrics (BP, Sugar Level, etc.)


Implement frontend dashboard with Streamlit or React


Dockerize the application for deployment



🧑‍💻 Author
Jenam Jain
📍 Data Science & Analytics | AIML Engineer
🔗 GitHub Profile

✅ FastAPI Patient Health Analyzer – Smart health insights made simple.


