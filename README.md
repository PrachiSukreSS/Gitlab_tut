# Flask Web App Deployment | GitLab CI/CD + Render 🚀

This project is a simple **Flask web application** that demonstrates deployment using **GitLab CI/CD pipelines** and **Render** for live hosting.

## 🌐 Live Demo
Check out the live deployed version here:  https://gitlab-tut-2.onrender.com
---

## 📁 Project Structure:
project/
│
├── app.py               # Main Flask application
├── templates/
│ └── index.html         # HTML page rendered by Flask
├── .gitlab-ci.yml       # GitLab CI/CD pipeline config
└── requirements.txt     # Python dependencies

## Tech Stack:
Python 3.13
Flask 3.1
GitLab CI/CD
Render (Cloud Hosting)

Deployment:
CI/CD handled by .gitlab-ci.yml
App is auto-deployed on Render using the detected port

Local:
git clone https://github.com/YourUsername/YourRepo.git
cd YourRepo
pip install -r requirements.txt
python app.py
