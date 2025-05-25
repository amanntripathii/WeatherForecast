
# Weather Forecast Web App 🌦️

A Django-based web application that predicts upcoming weather conditions like temperature, humidity, and other key parameters using machine learning models trained on historical weather data.

---

## 🚀 Features

- Predicts temperature and humidity for the next 5 hours
- Uses a Random Forest model for forecasting
- Displays wind speed, pressure, and visibility
- Simple UI built with Django templates
- Easily extendable and customizable

---

## 🛠️ Tech Stack

- **Backend**: Python, Django
- **Machine Learning**: scikit-learn (RandomForestRegressor)
- **Frontend**: HTML, CSS (Django templates)
- **Data**: CSV file of weather records
- **Version Control**: Git

---

## ⚙️ Setup Instructions (Step-by-Step)

> These steps are specifically for running the project in **Visual Studio Code** (VS Code) on Windows. Follow them carefully:

### 1. 🛡️ Allow Script Execution

```powershell
Set-ExecutionPolicy RemoteSigned -Scope Process
```

- This command temporarily allows PowerShell to run scripts like virtual environment activation.
- It ensures that scripts in the current session are trusted without affecting the whole system.

---

### 2. 🐍 Activate the Virtual Environment

```powershell
.\myenv\Scripts\activate
```

- This activates the Python virtual environment named `myenv`.
- It ensures all dependencies installed will stay isolated from your global Python setup.

---

### 3. 📁 Navigate to the Django Project Folder

```powershell
cd .\weatherProject\
```

- This command enters the Django project directory where `manage.py` is located.

---

### 4. 🚀 Run the Development Server

```powershell
python manage.py runserver
```

- Starts the Django development server at `http://127.0.0.1:8000/`
- You can now open your browser and view the web app.

---

## 💻 How to Run in VS Code

1. Open **VS Code**
2. Go to **File > Open Folder** and choose the root project directory
3. Open a new terminal in VS Code
4. Run the setup steps above one-by-one in the terminal
5. Press `Ctrl + Click` on the `127.0.0.1:8000` link to view the app

---

## 📂 Project Structure

```
MLproj/
│
├── weatherProject/        # Main Django project
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── myenv/                 # Virtual environment (not usually in repo)
├── weather.csv            # Dataset used for ML model
├── weatherApp/            # Django app for predictions
│   ├── views.py
│   ├── models.py
│   └── templates/
│       └── index.html
└── manage.py              # Django management script
```

---

## 📌 Notes

- Make sure Python (>= 3.8) is installed
- Install dependencies with `pip install -r requirements.txt` if a `requirements.txt` file is available
- The ML model is trained offline and predictions are served through Django views

---

## 📄 License

This project is for educational and demonstration purposes only. 

---

## 👤 Author

Created by **Aman Tripathi**  
