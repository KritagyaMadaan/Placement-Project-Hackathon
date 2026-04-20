# 🎓 NFSU Placement Portal

### An End-to-End Web-Based College Placement Management System


------------------------------------------------------------------------

## 📌 Abstract

The **NFSU Placement Portal** is a comprehensive web-based application
designed to digitalize and streamline the college placement process. It
provides a unified platform for **students**, **recruiters**, and
**placement administrators** to interact efficiently. The system
minimizes manual effort, improves transparency, and ensures timely
communication through automated workflows and email notifications.

This project is suitable for **academic submission, final-year projects,
hackathons, and real-world institutional deployment**.

------------------------------------------------------------------------

## 🎯 Problem Statement

Traditional placement processes rely heavily on manual coordination,
emails, and spreadsheets, leading to: - Inefficient communication\
- Data inconsistency\
- Delayed notifications\
- Lack of centralized monitoring

The NFSU Placement Portal addresses these issues by providing a
**secure, scalable, and automated placement ecosystem**.

------------------------------------------------------------------------

## 🎯 Objectives

-   Centralize placement-related activities on a single platform\
-   Automate job postings, applications, and notifications\
-   Enable transparent interaction between students and recruiters\
-   Reduce administrative workload for placement cells\
-   Ensure scalability and maintainability using modern web technologies

------------------------------------------------------------------------

## 👥 Stakeholders & User Roles

### 👨‍🎓 Students

-   Secure registration and authentication\
-   Profile creation with academic and personal details\
-   Browse and apply for job/internship opportunities\
-   Track application status\
-   Receive automated email notifications

### 🏢 Recruiters

-   Company registration and login\
-   Post job and internship opportunities\
-   View student applications\
-   Shortlist candidates\
-   Send interview and selection notifications

### 🛠️ Placement Administrators

-   Manage student and recruiter accounts\
-   Approve or reject job postings\
-   Monitor placement statistics\
-   Ensure platform integrity and policy enforcement

------------------------------------------------------------------------

## ⭐ Key Features

### 🔐 Authentication & Authorization

-   Role-based access control (Student / Recruiter / Admin)
-   Secure login and session handling

### 📋 Job & Application Management

-   Recruiter-driven job posting
-   Student job applications
-   Admin approval workflow

### 📧 Automated Email Communication

-   Application confirmation
-   Shortlisting notifications
-   Interview scheduling alerts
-   Final selection or rejection emails\
    *(Implemented using EmailJS)*

### 📊 Monitoring & Transparency

-   Application tracking
-   Recruiter activity logs
-   Student application history

### 💻 User Experience

-   Responsive and intuitive UI
-   Cross-browser compatibility
-   Mobile-friendly design

------------------------------------------------------------------------

## 🧰 Technology Stack

### Frontend

-   **React.js** -- Component-based UI architecture\
-   **Vite** -- Fast development and optimized builds\
-   **JavaScript (ES6+)**\
-   **HTML5, CSS3**

### Backend / Services

-   **EmailJS** -- Client-side email automation\
-   **Firebase / REST API (Optional)** -- Authentication and database
    support

### Tools & Utilities

-   Node.js\
-   npm\
-   Git & GitHub

------------------------------------------------------------------------

## 🏗️ System Architecture

    User (Browser)
         ↓
    React + Vite Frontend
         ↓
    EmailJS / API Services
         ↓
    Email Server / Database

------------------------------------------------------------------------

## 📁 Project Directory Structure

    nfsu-placement-portal/
    │
    ├── public/
    │   └── index.html
    │
    ├── src/
    │   ├── assets/          # Images, icons, logos
    │   ├── components/      # Reusable UI components
    │   ├── pages/           # Application pages
    │   ├── services/        # EmailJS & API handlers
    │   ├── styles/          # CSS files
    │   ├── App.jsx          # Root component
    │   └── main.jsx         # Entry point
    │
    ├── node_modules/
    ├── package.json
    ├── vite.config.js
    └── README.md

------------------------------------------------------------------------

## ⚙️ Installation & Setup

### 🔧 Prerequisites

-   Node.js (v16 or higher)
-   npm (v8 or higher)

Verify installation:

``` bash
node -v
npm -v
```

------------------------------------------------------------------------

### 📥 Clone Repository

``` bash
git clone https://github.com/your-username/nfsu-placement-portal.git
cd nfsu-placement-portal
```

------------------------------------------------------------------------

### 📦 Install Dependencies

``` bash
npm install
```

------------------------------------------------------------------------

### 📧 EmailJS Configuration

1.  Create an account at https://www.emailjs.com\
2.  Create an Email Service and Template\
3.  Obtain:
    -   Service ID
    -   Template ID
    -   Public Key

Create a `.env` file:

    VITE_EMAILJS_SERVICE_ID=your_service_id
    VITE_EMAILJS_TEMPLATE_ID=your_template_id
    VITE_EMAILJS_PUBLIC_KEY=your_public_key

Use in code:

``` javascript
import.meta.env.VITE_EMAILJS_SERVICE_ID
```

------------------------------------------------------------------------

### ▶️ Run the Application

``` bash
npm run dev
```

Application runs at:

    http://localhost:5173

------------------------------------------------------------------------

## 🧪 Testing Strategy

-   UI and form validation testing\
-   Role-based access testing\
-   Email delivery verification\
-   Cross-browser testing

------------------------------------------------------------------------

## 🚀 Deployment

Build the project:

``` bash
npm run build
```

Deploy using: - Vercel - Netlify - Firebase Hosting

------------------------------------------------------------------------

## 🔮 Future Enhancements

-   Resume upload and parsing
-   Interview scheduling module
-   Analytics dashboard for admins
-   Backend integration with MongoDB
-   OTP-based authentication
-   AI-based candidate-job matching

------------------------------------------------------------------------

## 📚 Use Cases

-   College placement cells
-   University career services
-   Internship coordination portals
-   Academic and research projects

------------------------------------------------------------------------

## 📜 License

This project is intended strictly for **academic, research, and
educational purposes**.\
Commercial use requires prior authorization.

------------------------------------------------------------------------

## 👨‍💻 Author

**Shivam**\
Cybersecurity \| Web Development \| Research\
National Forensic Sciences University (NFSU)

------------------------------------------------------------------------

## 🙌 Acknowledgements

-   Faculty mentors and placement coordinators\
-   Open-source community\
-   EmailJS documentation and developer support
