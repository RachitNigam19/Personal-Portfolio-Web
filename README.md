# 🌟 Personal-Portfolio-Web
This repository contains a personal portfolio website showcasing my projects, skills, and achievements. Built with Flask for a dynamic web interface and featuring a rule-based chatbot for user interaction, this project demonstrates expertise in web development, deployment, and conversational AI. The website is optimized for deployment on platforms like Heroku or Vercel.
📖 Overview
The Personal Portfolio Web is a professional website designed to highlight my technical skills, projects, and experience as a developer. Powered by Flask, it includes a responsive UI, a chatbot for interactive engagement, and deployment configurations for Heroku (Procfile) and Vercel (vercel.json). The project serves as a central hub for recruiters and visitors to explore my work.
🎯 Features

Displays a portfolio of projects, skills, and professional achievements.
Includes a rule-based chatbot for interactive user engagement (via chatbot_logic.py).
Responsive web interface built with HTML, CSS, and JavaScript.
Supports deployment on Heroku and Vercel for scalability and accessibility.
Modular codebase for easy updates and customization.
Clean and professional design to attract recruiters and potential collaborators.

🛠️ Tech Stack

Python: Core programming language.
Flask: Lightweight framework for building the web application.
HTML/CSS: For front-end UI (in templates and static folders).
JavaScript: For interactive elements (assumed in static).
Gunicorn: WSGI server for Heroku deployment (via Procfile).
Vercel: For serverless deployment (via vercel.json).
Git: Version control with .gitignore for clean repository management.

🚀 Getting Started
Prerequisites

Python 3.8+
Git
Heroku CLI (optional, for Heroku deployment)
Vercel CLI (optional, for Vercel deployment)

Installation

Clone the repository:git clone https://github.com/RachitNigam19/Personal-Portfolio-Web.git
cd Personal-Portfolio-Web


Install dependencies:pip install -r requirements.txt


(Optional) Run the requirements modification script if needed:python modify_requiremnttxt.py



Usage

Run the Flask application locally:python app.py


Access the portfolio at http://localhost:5000.


Interact with the chatbot via the web interface for a dynamic experience.
Explore the portfolio to view projects, skills, and contact information.

Deployment

Heroku:
Deploy to Heroku:heroku create
git push heroku main
heroku open


Ensure the Procfile is configured (e.g., web: gunicorn app:app).


Vercel:
Deploy to Vercel:vercel


Ensure the vercel.json configuration is set for Flask deployment.



📂 Project Structure
Personal-Portfolio-Web/
├── static/                      # CSS, JavaScript, and static assets
├── templates/                   # HTML templates for the web interface
├── app.py                       # Main Flask application
├── chatbot_logic.py             # Rule-based chatbot logic
├── modify_requiremnttxt.py      # Script to modify requirements (if needed)
├── Procfile                     # Heroku deployment configuration
├── vercel.json                  # Vercel deployment configuration
├── requirements.txt             # Project dependencies
├── .gitignore                   # Files/folders to ignore in Git
├── .venv/                       # Virtual environment (excluded from Git)
├── __pycache__/                 # Python bytecode cache (excluded from Git)
├── .DS_Store/                   # macOS system file (excluded from Git)
├── prepros-6.config             # Prepros configuration for front-end preprocessing

🔍 How It Works

Portfolio Display: The Flask app (app.py) serves a web interface with HTML templates (templates) and styling (static) to showcase projects and skills.
Chatbot: The chatbot_logic.py script implements a rule-based chatbot that responds to user inputs, enhancing interactivity.
Deployment: Configurations like Procfile and vercel.json enable deployment on Heroku or Vercel for public access.
Customization: The modify_requiremnttxt.py script likely automates dependency updates, and prepros-6.config supports front-end preprocessing (e.g., CSS compilation).

🌟 Why This Project?

Demonstrates expertise in web development with Flask and front-end technologies.
Showcases skills in building interactive features like a rule-based chatbot.
Highlights proficiency in deployment on Heroku and Vercel.
Reflects clean coding practices with a modular, well-organized codebase.
Serves as a professional portfolio to attract recruiters and collaborators.

📫 Contact

GitHub: RachitNigam19
LinkedIn: Rachit Nigam
Email: rachitn46@gmail.com

Feel free to explore, contribute, or reach out for collaboration!
