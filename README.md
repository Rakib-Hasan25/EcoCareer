# EcoCareer Platform

**EcoCareer** is a **full-stack, modular job discovery and career intelligence platform**.
It integrates **real-time job retrieval**, **skill matching & gap analysis**, and **admin analytics dashboards** using **Next.js** on the frontend and **Python (Flask)** on the backend.

The repository is structured as **independent services**, each responsible for a specific concern, enabling scalability, maintainability, and clean separation of responsibilities.

---

## 🌍 Problem Statement

Most existing job platforms:

* Show **outdated or duplicated job listings**
* Provide **little to no skill-gap guidance**
* Focus on **either global or local markets**, not both

**EcoCareer addresses these gaps by:**

* Fetching **real-time job data** from multiple sources (no static database)
* Matching jobs to user skills with **percentage-based relevance**
* Identifying **missing skills** and learning directions
* Supporting **Bangladesh, global, and remote job platforms**
* Providing **admin-level analytics** for monitoring platform impact

---

## 🧠 Key Features

* 🔎 Real-time job retrieval from multiple APIs
* 🎯 Skill-based job matching with relevance score
* 📉 Skill gap analysis & learning recommendations
* 🌐 Direct redirection links to 13+ job platforms
* 📊 Admin dashboard for analytics & management
* 🧩 Modular, service-based architecture

---

## 🖼️ System Architecture

### System Architecture Diagram

<img width="512" height="426" alt="eco-Diagram" src="https://github.com/user-attachments/assets/ff1fdc66-08db-4ba0-8806-2dc5f499e554" />

*The complete system architecture showing the interaction between frontend services, backend API gateway.*

---

## 🖥️ Frontend Screenshots

### Landing Page

<img width="949" height="496" alt="Slide-Homepage" src="https://github.com/user-attachments/assets/ea05d4cc-7ca3-4f06-9c5a-10bed702a699" />

*EcoCareer homepage showcasing the platform's value proposition and call-to-action.*

---

### User Registration

<img width="960" height="494" alt="Slide-SignUpPage" src="https://github.com/user-attachments/assets/53e9c9f8-655b-49b0-abf9-11adee898bbf" />

*User sign-up page with authentication options.*

---

### Role Selection

<img width="1914" height="989" alt="Slide-JoinAs" src="https://github.com/user-attachments/assets/3cb7a886-c7e3-423f-9613-ad52e05ff76f" />

*Role selection interface allowing users to join as job seekers or employers.*

---

### User Dashboard

<img width="953" height="494" alt="Slide-UserDashboard" src="https://github.com/user-attachments/assets/fcd1b5fd-0b71-4231-b5ee-f6fc8eee7d0c" />

*Main dashboard displaying personalized job recommendations and quick actions.*

---

### User Profile Overview

<img width="953" height="496" alt="Slide-UserProfile" src="https://github.com/user-attachments/assets/5eb477d0-3d40-4c9d-bdda-a1d0b624468e" />

*User profile page showing skills, experience, and career information.*

---

### Extended Profile View

<img width="952" height="495" alt="Slide-UserProfile2" src="https://github.com/user-attachments/assets/471f1498-250e-42a2-bd6e-393df642b57b" />

*Detailed user profile section with additional career details.*

---

### Profile Editor

<img width="952" height="496" alt="Slide-EditProfile" src="https://github.com/user-attachments/assets/7533c536-935d-49f5-ab13-3d054d5b1151" />

*Profile editing interface for updating user information and skills.*

---

### Job Profile Analyzer

<img width="952" height="495" alt="Slide-ProfileAnalyzerForJob" src="https://github.com/user-attachments/assets/1f0d0019-3e83-4feb-86f2-02ddfdf7951e" />

*AI-powered profile analyzer showing skill match percentage and compatibility with job requirements.*

---

### Career Roadmap - Overview

<img width="1897" height="991" alt="Slide-CareerRoadmap" src="https://github.com/user-attachments/assets/11fdcf44-f3ce-47ce-b5f4-c128bd54b921" />

*Visual career roadmap displaying progression paths and milestones.*

---

### Career Roadmap - Skill Progression

<img width="1902" height="990" alt="Slide-CareerRoadmap2" src="https://github.com/user-attachments/assets/47f33f5d-3f12-45a8-ad08-b9806899e775" />

*Detailed skill progression timeline with learning checkpoints.*

---

### Career Roadmap - Learning Path

<img width="1900" height="988" alt="Slide-CareerRoadmap3" src="https://github.com/user-attachments/assets/0aa6983a-1508-40ff-88fe-fd5e1a60fb41" />

*Customized learning path recommendations based on career goals.*

---

### Learning Resources Hub

<img width="1904" height="988" alt="Slide-Learning" src="https://github.com/user-attachments/assets/6e8f16e1-eda7-468b-befa-a4069f8ab126" />

*Curated learning resources and courses for skill development.*

---

### CV Assistant - Input

<img width="1896" height="985" alt="Slide-CvAssitant" src="https://github.com/user-attachments/assets/6da1231f-5701-455d-bc0c-598c9eaf0ce5" />

*AI-powered CV assistant interface for resume creation and optimization.*

---

### CV Assistant - Output

<img width="1900" height="989" alt="Slide-CvAssitant2" src="https://github.com/user-attachments/assets/3d65b9b4-4183-4712-a4d8-df5d002b3dae" />

*Generated CV preview with professional formatting and suggestions.*

---

### Admin Dashboard - Job Management

<img width="1906" height="990" alt="Slide-AdminJobs" src="https://github.com/user-attachments/assets/f01bd683-cced-45c8-ab25-15a32b6f8d3d" />

*Admin interface for viewing and managing job listings.*

---

### Admin Dashboard - Job Editor

<img width="1919" height="987" alt="Slide-AdminJobsEdit" src="https://github.com/user-attachments/assets/120122fd-51a4-4178-9315-7644929e24ca" />

*Job editing interface for administrators to update job details.*

---

### Admin Dashboard - Resources Management

<img width="1908" height="989" alt="Slide-AdminResources" src="https://github.com/user-attachments/assets/7417ef49-0796-4c16-8ed5-b804c2293a28" />

*Resource management panel for curating learning materials and content.*

---

## 📁 Repository Structure

```
ECOCAREER/
│
├── Online_Jobretrieve_service/        # Real-time job retrieval engine
│   └── README.md                      # Service-level documentation
│
├── main_backend_service/              # Flask backend (API gateway)
│   ├── app.py                         # Main application entry point
│   ├── requirements.txt               # Python dependencies
│
├── main_frontend_service/             # User-facing Next.js frontend
│   └── README.md                      # Frontend documentation
│
├── admin_dashboard_frontend_service/  # Admin analytics dashboard
│   └── README.md                      # Admin dashboard documentation
│
└── README.md                          # Root documentation (this file)
```

---

## 🧩 Services Overview

### 1️⃣ Online Job Retrieval Service (Python)

**Purpose**
Fetches and normalizes job listings in **real time** from multiple APIs and generates platform-specific job search links.

**Highlights**

* No database dependency
* 5+ job data APIs
* 13+ job platform link generators
* Skill extraction from job descriptions
* 30-minute in-memory caching for performance

📄 Detailed documentation: `Online_Jobretrieve_service/README.md`

---

### 2️⃣ Main Backend Service (Flask)

**Purpose**
Acts as the **central API layer** connecting frontend applications with job intelligence services.

**Responsibilities**

* REST API exposure
* Job-to-skill matching logic
* Skill gap analysis
* Integration with real-time job retrieval engine
* Dockerized deployment support


---

### 3️⃣ Main Frontend Service (Next.js)

**Purpose**
Provides the **user-facing interface** for job discovery and career guidance.

**Responsibilities**

* Job search UI
* Skill input & matching results
* Platform redirection links
* Responsive and scalable frontend architecture

📄 Documentation: `main_frontend_service/README.md`

---

### 4️⃣ Admin Dashboard Frontend (Next.js)

**Purpose**
Admin-only interface to monitor platform performance and manage content.

**Responsibilities**

* Analytics visualization
* Job management (CRUD)
* Learning resource management
* Impact tracking for SDG 8 goals

📄 Documentation: `admin_dashboard_frontend_service/README.md`

---

## 🚀 Local Development (Quick Start)

### Backend

```bash
cd main_backend_service
pip install -r requirements.txt
python app.py
```

Runs at: `http://localhost:5001`

---

### User Frontend

```bash
cd main_frontend_service
npm install
npm run dev
```

Runs at: `http://localhost:3000`

---

### Admin Dashboard

```bash
cd admin_dashboard_frontend_service
npm install
npm run dev
```

Runs at: `http://localhost:3001`

---

## 🔑 Environment Configuration

Each service uses its **own environment configuration**.

### Backend Service (.env)

```env
# API Keys
RAPIDAPI_KEY=your_key
ADZUNA_APP_ID=your_id
ADZUNA_APP_KEY=your_key

# Database (if used)
DATABASE_URL=your_database_url

# Server Configuration
FLASK_ENV=development
PORT=5001
```

### Frontend Service (.env.local)

```env
NEXT_PUBLIC_API_URL=http://localhost:5001
NEXT_PUBLIC_APP_NAME=EcoCareer
```

Refer to individual service READMEs for full environment variable lists.

---

## 🎯 Why This Project Stands Out

| Traditional Platforms | EcoCareer               |
| --------------------- | ----------------------- |
| Static job databases  | Real-time job fetching  |
| Generic listings      | Skill-aware matching    |
| No learning guidance  | Skill gap insights      |
| Single-market focus   | Local + global coverage |
| Heavy DB maintenance  | No database dependency  |

---

## 🏆 Use Cases

* 🎓 **Students** exploring career-ready skills
* 💼 **Job seekers** targeting better-fit roles
* 🌍 **SDG-focused organizations** driving employment initiatives
* 📊 **Admin teams** tracking employment impact and platform analytics

---

## 📌 Project Status

* ✅ Core features implemented
* ✅ Production-ready services
* 🔄 UI/UX refinement ongoing
* 🔄 Backend service documentation needed
* 🔄 Optional persistence layer (future enhancement)

---

## 🛠️ Technology Stack

### Frontend
- **Framework:** Next.js (React)
- **Styling:** Tailwind CSS / CSS Modules
- **State Management:** React Context / Redux
- **API Communication:** Axios / Fetch API

### Backend
- **Framework:** Flask (Python)
- **API Integration:** Multiple job board APIs
- **Caching:** In-memory (30-minute TTL)
- **Deployment:** Docker support

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---
