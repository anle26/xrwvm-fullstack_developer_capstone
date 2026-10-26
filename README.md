# fullstack_developer_capstone

This is the comprehensive capstone application index and management panel for Cars Dealership, a national car retailer in the U.S. It acts as an interactive client portal and administrative dashboard written in React, Django, Node.js, and MongoDB with CI/CD GitHub Actions and Cloud Deployment.

### 📋 Project & Repository Details
- **Repository Name**: xrwvm-fullstack_developer_capstone
- **Project Name**: fullstack_developer_capstone
- **Website Primary Title**: Best Cars Dealership Portal
- **Website Secondary Title**: Full Stack Application Development Capstone Project

---

## 🛠️ Technology Stack Breakdown

### Frontend
- **React & Vite** - Next-generation compiler, state-management hooks, dynamic view routing, and responsive UI components.
- **Bootstrap & CSS** - Responsive grid alignments, card layouts, and custom light/dark styling tokens.

### Backend & Microservices
- **Django Framework (Python)** - Core administrative framework managing authentication, user session security, and state proxy pipelines.
- **Express / Node.js Microservices** - High-concurrency backend services handling dealership queries and review management.
- **Sentiment Analyzer Microservice** - Microservice handling natural language processing and sentiment classification for dealer reviews.

### Databases
- **MongoDB (Cloud / Containerized)** - Document database facilitating fast customer reviews query lookups.
- **SQLite (Django Local DB)** - Relational database managing car makes, car models, and administrative records.

### DevOps & Deployment Pipeline
- **Docker** - Self-contained containerization defining repeatable client/server environments.
- **Kubernetes / IBM Cloud Code Engine** - Container orchestration and production serverless deployment.
- **GitHub Actions (CI/CD)** - Automated linting (flake8) and test execution on push/pull requests.

---

## 📂 Core Project Files
- `/server/frontend/static/About.html` - Static "About Us" page with executive board details and responsive cards.
- `/server/frontend/static/Contact.html` - Static "Contact Us" page with company contact details and inquiry form.
- `/server/frontend/src/components/Register/Register.jsx` - React registration component with five user fields.
- `/server/djangoapp/` - Django backend application containing models, views, and routing logic.
- `/Project-Deliverables/` - Folder containing cURL logs, terminal outputs, and rubrics verification artifacts.

---

## 🚀 How to Run Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/anle26/xrwvm-fullstack_developer_capstone.git
   cd xrwvm-fullstack_developer_capstone
   ```

2. **Start the Django Backend**:
   ```bash
   cd server
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   python3 manage.py migrate
   python3 manage.py runserver 0.0.0.0:8000
   ```

3. **Start the Frontend**:
   ```bash
   cd server/frontend
   npm install
   npm run build
   ```
