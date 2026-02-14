# 🚀 TalentTrail – Smart Job Platform

**TalentTrail** is a comprehensive web-based job portal built using the **MERN Stack**.
It simplifies and digitizes the recruitment process by connecting students (job seekers) with recruiters (job providers) on a single smart platform.

---

## 📌 Problem Statement

The current job application ecosystem is fragmented and inefficient:

* **Manual Inefficiency** – Students must visit multiple websites to search for jobs.
* **General-Purpose Portals** – Most platforms are not tailored for freshers and entry-level candidates.
* **Tedious Application Process** – Re-uploading resumes repeatedly for each job.
* **Limited Recruiter Insights** – Recruiters lack structured tools to filter candidates based on academic skills and projects.

---

## 💡 Solution

TalentTrail provides a centralized digital ecosystem where:

* Students create professional digital profiles
* Recruiters post and manage job listings
* Applications are streamlined with one-click apply
* Real-time tracking ensures transparency

It ensures the **right talent meets the right opportunity**.

---

## ✨ Key Features

### 🎓 Student Module

* 🔐 Registration & Secure Login (JWT Authentication)
* 🧑‍💼 Profile Management (Digital Resume)
* 🔍 Advanced Job Search (Filter by keyword, company, location)
* ⚡ One-Click Job Application
* 📊 Application Status Tracking (Applied / Accepted / Rejected)

---

### 💼 Recruiter Module

* 🏢 Company Profile Creation
* 📝 Job Posting & Management (Create, Edit, Delete)
* 👀 View Applicant Profiles & Resumes
* 🔄 Update Application Status

---

## 🛠 Tech Stack

| Component          | Technology Used                          |
| ------------------ | ---------------------------------------- |
| **Frontend**       | React.js (Vite), Tailwind CSS, ShadCN/UI |
| **Backend**        | Node.js, Express.js                      |
| **Database**       | MongoDB Atlas                            |
| **Authentication** | JSON Web Token (JWT)                     |
| **API Testing**    | Postman                                  |

---

## 📊 System Architecture

* Backend follows **MVC Architecture**
* Frontend follows **Component-Based Architecture**
* RESTful APIs for communication
* JWT-based authentication & protected routes

---

## ⚙️ Installation & Setup

### 🔹 Prerequisites

* Node.js (v18+ recommended)
* MongoDB Atlas Account
* Git Installed

---

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/talent-trail.git
cd talent-trail
```

---

### 2️⃣ Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file inside the backend folder:

```
PORT=8000
MONGO_URI=your_mongodb_atlas_connection_string
JWT_SECRET=your_secret_key
```

Start the backend server:

```bash
npm run dev
```

---

### 3️⃣ Frontend Setup

```bash
cd ../frontend
npm install
npm run dev
```

Open in browser:

```
http://localhost:5173
```

---

## 🔮 Future Enhancements

* 🤖 AI-Based Job Recommendations
* 📊 Admin Dashboard
* 💬 Real-Time Chat (Socket.io)
* 📧 Email Notifications
* 📱 Mobile App (React Native)

---

## 👨‍💻 Author

**Atharva Shridhar Mhetre**
🎓 Master of Computer Applications (MCA)
🏫 Chhatrapati Shahu Institute of Business Education and Research
👨‍🏫 Guided by: Prof. R. T. Thorat

---

## ⭐ Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is for educational purposes.

