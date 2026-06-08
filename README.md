SmartAttend-AI
AI-Powered Automated Student Attendance Monitoring and Analytics System for Colleges built using Python, FastAPI, Streamlit, OpenCV, MongoDB, and AI-based face recognition.
Features
Student Face Recognition Attendance System
Real-Time Attendance Marking
Admin & Student Login System
Attendance Analytics Dashboard
Monthly / Daily Reports
History Tracking System
Downloadable Attendance Reports (PDF/Excel)
Interactive Plotly Charts
Secure MongoDB Data Storage
AI-based Accuracy Improvement System
Tech Stack
Frontend
Streamlit
HTML / CSS
Plotly
Backend
FastAPI
Python
Uvicorn
OpenCV (Face Detection & Recognition)
Database
MongoDB
PyMongo
AI / ML
Face Recognition Model (Haar Cascade / FaceNet / Dlib)
Rule-based AI fallback system
Project Structure

smartattend-ai
├── backend
│   ├── main.py
│   ├── auth.py
│   ├── attendance.py
│   └── ai_model.py
├── frontend
│   ├── app.py
│   ├── dashboard.py
│   └── utils.py
├── dataset
├── venv
├── requirements.txt
├── README.md
└── .gitignore
How to Run
Activate Virtual Environment

.\venv\Scripts\activate
Run Backend

uvicorn backend.main:app --reload
Run Frontend

streamlit run frontend/app.py
Modules
Authentication System
Face Recognition Attendance System
AI Attendance Analyzer
Dashboard Analytics
Student Management System
Report Generation Module
Developed By
Yourvarsha jaysiha V
