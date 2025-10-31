# 🚀 Kafiil Docker Service

This project is a simple **Node.js + Express + MongoDB** web application running inside **Docker containers**, created as a demo service for **Kafiil**.

---

## 🧩 Overview

The app demonstrates how to:
- Build and run a Node.js + MongoDB stack using **Docker Compose**.
- Connect the Node.js backend to a MongoDB container.
- Serve a simple interactive web interface using **Tailwind CSS**.
- Perform CRUD operations (create & fetch users) via REST API.

---

## 🛠️ Technologies Used

- **Node.js** (v18)
- **Express.js**
- **MongoDB** (v4.4)
- **Mongoose**
- **Docker & Docker Compose**
- **Tailwind CSS**

---

## ⚙️ Project Structure

Kafiil-Docker-Service/
│
├── Dockerfile
├── docker-compose.yml
├── app.js
├── package.json
├── public/
│ └── index.html
└── README.md


---

## 🧪 How to Run Locally

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/mariam-ahmeed/Kafiil-Docker-Service.git
cd Kafiil-Docker-Service

2️⃣ Build & Start the Containers
docker-compose up --build

3️⃣ Open the Application

Once the build finishes, visit:

http://localhost:3000



➕ Add a new user:
curl -X POST http://localhost:3000/users \
-H "Content-Type: application/json" \
-d '{"name":"Mariam","email":"mariam@example.com"}'

📜 Get all users:
curl http://localhost:3000/users


💬 Author

👩‍💻 Mariam Ahmed
AWS Certified Cloud Practitioner | DevOps Enthusiast
📍 Egypt
🔗 GitHub Profile


🧱 Notes

MongoDB version 4.4 is used to ensure CPU compatibility.

The containers automatically restart if stopped.

The project can be easily deployed on AWS, Docker Hub, or any VPS.

🏁 Conclusion

This project demonstrates a clean Dockerized Full Stack Application — combining backend (Node.js + Express) and database (MongoDB) inside containers, with a simple interactive frontend.


