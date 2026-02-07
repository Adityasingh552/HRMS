# HRMS

## 📌 Project Overview
HRMS Lite is a web-based Human Resource Management System designed to handle basic internal HR operations.  
The application allows an administrator to manage employee records and track daily attendance through a simple and professional interface.

This project demonstrates a decoupled architecture where the frontend and backend are deployed on separate platforms and communicate via RESTful APIs.

### Core Features
- Add, view, and delete employee records
- Mark daily attendance (Present / Absent)
- View attendance records per employee
- Persistent data storage using a cloud database

---

## 🛠️ Tech Stack Used

### Frontend
- HTML
- CSS
- JavaScript (Vanilla JS)
- **Deployment:** Vercel

### Backend
- Python
- FastAPI (RESTful APIs)
- Uvicorn (ASGI server)
- **Deployment:** Render

### Database
- MongoDB Atlas (Cloud NoSQL Database)

## ▶️ Steps to Run the Project Locally

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Adityasingh552/HRMS.git
cd HRMS
```

###2️⃣ Run the Backend (FastAPI)
```
cd Backend
```

### (Optional) Create and activate a virtual environment:
```
python -m venv venv
venv\Scripts\activate   # Windows
```

### Install dependencies:
```
pip install -r requirements.txt
##Set MongoDB Atlas connection string as an environment variable:
```

### Windows (PowerShell):
```
setx MONGO_URL "mongodb+srv://<username>:<password>@<cluster>.mongodb.net/hrms_db"
##Restart the terminal after setting the variable.
```

### Start the backend server:
```
python -m uvicorn main:app --reload

##Backend will run at:
```
http://127.0.0.1:8000
```

## API documentation (Swagger):
```
http://127.0.0.1:8000/docs
```

```

### 3️⃣ Run the Frontend:
```
cd frontend

##Open index.html in a browser
or use VS Code Live Server extension.
```

## 🌐 Live Application URLs:
```
https://hrms-seven-henna.vercel.app/
```




