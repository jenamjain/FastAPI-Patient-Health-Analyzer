🩺 FastAPI Patient Health Analyzer

A FastAPI-based project that analyzes patient health data and provides BMI (Body Mass Index) insights to assess overall patient wellness efficiently.

🚀 Features

🧠 Calculates BMI (Body Mass Index) from height and weight

📊 Provides personalized health insights — Underweight, Normal, Overweight, or Obese

💾 Stores and manages patient data in a JSON file (patients.json)

⚡ Built using FastAPI for high performance and modern API structure

🧩 Uses Pydantic models for validation and structured data management

🗂️ Project Structure
FastAPI-Patient-Health-Analyzer/
├── main.py             # Main FastAPI application
├── patients.json        # JSON data file for patients
├── requirements.txt     # List of dependencies
├── .gitignore           # Files ignored by Git
├── Pydantic/            # Pydantic models for validation
└── __pycache__/         # Compiled Python cache files

🧰 Tech Stack
Component	Technology
Language	Python 🐍
Framework	FastAPI
Data Model	Pydantic
Storage	JSON
Environment	Virtual Environment (venv / myenv)
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/jenamjain/FastAPI-Patient-Health-Analyzer.git
cd FastAPI-Patient-Health-Analyzer

2️⃣ Create and Activate a Virtual Environment
# Create a virtual environment
python -m venv myenv

# Activate the environment
# macOS / Linux
source myenv/bin/activate

# Windows
myenv\Scripts\activate

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run the FastAPI Server
uvicorn main:app --reload


Now open your browser and visit:
👉 http://127.0.0.1:8000

🧭 Explore the API Documentation

FastAPI provides two built-in interactive docs:

Swagger UI → http://127.0.0.1:8000/docs

ReDoc → http://127.0.0.1:8000/redoc

🧪 Example API Endpoints
Method	Endpoint	Description
GET	/patients	Retrieve all patient records
POST	/patients	Add a new patient record
GET	/patients/{id}	Retrieve a specific patient by ID
DELETE	/patients/{id}	Delete a patient record
🧮 Example BMI Insights
BMI Range	Category
< 18.5	Underweight
18.5 – 24.9	Normal weight
25 – 29.9	Overweight
≥ 30	Obese
🌟 Future Enhancements

🗄️ Add database integration (SQLite / PostgreSQL)

🩸 Include additional health metrics (Blood Pressure, Sugar Levels, etc.)

🖥️ Build a frontend dashboard using Streamlit or React

🐳 Dockerize the application for easier deployment

🧑‍💻 Author

Jenam Jain
📍 Data Science & Analytics | AIML Engineer
🔗 GitHub Profile

✅ FastAPI Patient Health Analyzer – Smart health insights made simple.
