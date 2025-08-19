## 🛠 Steps to Set Up Flask Project

1. Create Project Folder
mkdir flask_project
cd flask_project

2. Create Virtual Environment
# For Windows
python -m venv .env
.env\Scripts\activate

3. Install Flask
pip install flask

flask_project/
│── app.py              # main Flask app
│── requirements.txt
│── .env/               # virtual environment folder
│── static/             # CSS, JS, images
│    └── style.css
│── templates/          # HTML templates
     ├── base.html
     ├── nav.html
     ├── index.html
     ├── about.html
     └── login.html
     
5. Create app.py

6. Run Flask App
python app.py
