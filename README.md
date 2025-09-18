# -Inventory-Workflow-Automation-System
A full-stack web application for managing retail inventory and order fulfillment. Built with React, Flask, and PostgreSQL, this project automates common workflow tasks that are often handled manually in retail environments.

🚀 Features

* **Inventory Management**

 * Add, update, and delete products

 * Track stock quantities in real time

Order Fulfillment

Place new customer orders

Update order status (pending → fulfilled)

Dashboard (optional stretch)

Low-stock alerts

Sales and inventory trends

Authentication (optional stretch)

Admin vs. staff roles

🛠️ Tech Stack

Frontend: React, Tailwind CSS (or Bootstrap)

Backend: Flask (Python) + SQLAlchemy ORM

Database: PostgreSQL

Deployment: Render/Heroku (backend), Vercel/Netlify (frontend)

Testing & CI/CD: Pytest + GitHub Actions

⚙️ Installation & Setup
1. Clone the repo
git clone https://github.com/YOUR_USERNAME/inventory-automation.git
cd inventory-automation

2. Backend Setup
cd backend
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
pip install -r requirements.txt
flask run

3. Frontend Setup
cd frontend
npm install
npm start

4. Database Setup
CREATE DATABASE inventory_db;


Update connection string in config.py.

🌐 Live Demo

🔗 Live Site

🔗 Backend API

📸 Screenshots

(Add a couple of clean screenshots or GIFs here — inventory dashboard, order page, etc.)

🧪 Tests

Run backend tests:

pytest

📖 Project Roadmap

 Backend API for products

 Order management system

 React frontend

 Deployment (Render + Vercel)

 Analytics dashboard

 Authentication

✨ Resume-Ready Highlights

Designed and deployed a full-stack web app for inventory and order management.

Implemented RESTful APIs with Flask and PostgreSQL.

Built a React dashboard for real-time stock and order updates.

Deployed with CI/CD pipelines on GitHub Actions + cloud platforms.

👨‍💻 Author

Theron Hamlin

LinkedIn

GitHub
