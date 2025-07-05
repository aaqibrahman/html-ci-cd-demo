# html-ci-cd-demo
# 🚀 Flask CI/CD Web App

A simple Python Flask web application deployed to the cloud using **Render**, with **automated testing and deployment via GitHub Actions**.

## 🌐 Live Demo

👉 [View Deployed App on Render](https://flask-ci-cd-demo-phim.onrender.com)  

---

## 📦 Features

- 🐍 Built using **Flask** (lightweight Python web framework)
- ✅ Tested using **Pytest**
- 🔁 CI/CD pipeline with **GitHub Actions**
- ☁️ Cloud deployment via **Render**
- 🚀 Automatic deployment on every `push` to `main`

---

## 🧑‍💻 Technologies Used

- Python 3.10
- Flask
- Pytest
- Gunicorn
- GitHub Actions
- Render (Cloud Hosting)

---

## 📁 Project Structure
flask-ci-cd-demo/
│
├── app.py # Main Flask app
├── test_app.py # Pytest unit tests
├── requirements.txt # Python dependencies
├── .github/
│ └── workflows/
│ └── main.yml # GitHub Actions CI/CD workflow

---

## 🚀 Getting Started

### ✅ Run Locally

bash
# Clone the repo
git clone https://github.com/your-username/flask-ci-cd-demo.git
cd flask-ci-cd-demo

# Set up a virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
Open your browser and visit: http://localhost:5000

# 🧪 Run Tests
pytest

# ⚙️ GitHub Actions CI/CD
Every push to the main branch triggers the following workflow:

✅ Checks out the code
📦 Installs dependencies
🧪 Runs tests with Pytest
☁️ Deploys to Render (if set up)

📄 Workflow file: .github/workflows/main.yml

# ☁️ Deployment (Render)

Sign up at https://render.com
Connect your GitHub repository
Create a new Web Service
Environment: Python
Build command: pip install -r requirements.txt
Start command: gunicorn app:app
Deploy and get your public URL 🎉

