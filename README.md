<div align="center">
  <img src="https://img.icons8.com/color/150/000000/tractor.png" alt="Tractor Logo" />
  <h1>🌾 AI Farm Management System</h1>
  <p><strong>A comprehensive, intelligent platform for modern agriculture.</strong></p>
  
  <p>
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
    <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django" />
    <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap" />
    <img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
  </p>
</div>

<hr />

## 📖 Overview

The **AI Farm Management System** is a robust, full-stack web application designed to empower farmers with data-driven insights and modern management tools. From inventory and soil tracking to intelligent crop recommendations, this platform bridges the gap between traditional farming and modern technology.

## ✨ Key Features

- **🧠 AI Recommendations Engine**: Get intelligent suggestions for crops and fertilizers based on soil data.
- **🌱 Soil & Crop Management**: Keep detailed records of soil tests, land parcels, and crop yields.
- **📦 Inventory & Orders**: Full e-commerce capability to manage agricultural supplies, tools, and seeds.
- **🧑‍🌾 Farmer Profiles**: Dedicated profiles for farmers to track their specific lands and resources.
- **🏛️ Government Resources**: Integrated portal to access local government schemes and help.
- **📊 Custom Admin Dashboard**: A powerful, centralized dashboard for administrators to oversee operations, inventory, and user activity.
- **📄 PDF Reports**: Automatically generate and download detailed soil reports and receipts (powered by `xhtml2pdf` and `reportlab`).
- **dashboard-<img width="1203" height="651" alt="DASHBOARD IMAGE" src="https://github.com/user-attachments/assets/93c2908d-9aec-4179-b2b2-a0b41f686ca0" />


---

## 🛠️ Tech Stack

### Backend
- **Framework**: Django 4.2+
- **Language**: Python 3
- **Database**: SQLite (Default) / PostgreSQL ready

### Frontend
- **Framework**: Bootstrap 5
- **Forms**: Django Crispy Forms
- **Styling**: Custom CSS / HTML5

---

## 🚀 Getting Started

Follow these steps to set up the project locally on your machine.

### 1. Clone the repository
```bash
git clone https://github.com/omjadhav9641/AI_Farm_Management_System.git
cd AI_Farm_Management_System
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
```

*Activate the environment:*
- **Windows:** `venv\Scripts\activate`
- **Mac/Linux:** `source venv/bin/activate`

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Create a Superuser (Admin)
```bash
python manage.py createsuperuser
```

### 6. Run the Development Server
```bash
python manage.py runserver
```

Open your browser and navigate to `http://127.0.0.1:8000/` to see the application running. Access the admin panel at `http://127.0.0.1:8000/admin/`.

---

## 📂 Project Structure

```text
AI_Farm_Management_System/
│
├── accounts/          # User authentication and roles
├── crops/             # Crop catalog and tracking
├── custom_admin/      # Custom administrative dashboard
├── dashboard/         # User and farmer dashboards
├── farmers/           # Farmer profiles and government schemes
├── inventory/         # E-commerce products and supplies
├── orders/            # Checkout and order tracking
├── recommendations/   # AI-powered crop & fertilizer suggestions
├── soil/              # Soil health tracking and reports
├── templates/         # Global HTML templates
└── farm_management/   # Main project configuration
```

---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📝 License
This project is open-source and available under the [MIT License](LICENSE).

<br/>
<div align="center">
  <sub>Built with ❤️ for better agriculture.</sub>
</div>
