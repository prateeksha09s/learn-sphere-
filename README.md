# learn-sphere-
A full-stack online learning platform that enables instructors to create and manage courses, and learners to enroll, learn, and pay — all in one place.
📖 Project Overview
Learn-Sphere is an end-to-end e-learning web application built with a Java/Spring Boot backend and a React.js frontend. It supports role-based access for students and instructors, secure payment integration via Razorpay, and a clean, responsive UI for an intuitive learning experience.

🛠️ Tech Stack
LayerTechnologyBackend Java, Spring Boot, Spring Security, HibernateFrontendReact.jsDatabaseMySQLAuthenticationJWT + Role-Based Access ControlPaymentRazorpay Payment GatewayVersion ControlGit / GitHub

✨ Features

🔐 Secure Authentication – JWT-based login with role-based access (Student / Instructor / Admin)
📚 Course Management – Instructors can create, update, and manage courses
🎯 Student Enrollment – Students can browse, enroll, and track progress
💳 Payment Integration – Razorpay gateway for seamless course purchases
📱 Responsive UI – Mobile-friendly React.js frontend
🔒 Spring Security – Protected API endpoints with authorization filters
🗄️ Optimized Database – Relational schema with query optimization


🖼️ Screenshots

Screenshots coming soon — stay tuned!

<!-- Add your screenshots here -->
<!-- ![Homepage](screenshots/homepage.png) -->
<!-- ![Dashboard](screenshots/dashboard.png) -->
<!-- ![Course Page](screenshots/course.png) -->

⚙️ Setup & Installation
Prerequisites

Java 17+
Node.js 18+
MySQL 8+
Maven

Backend Setup
bash# Clone the repository
git clone https://github.com/prateeksha09s/learn-sphere.git
cd learn-sphere/backend

# Configure database
# Edit src/main/resources/application.properties
# Set your MySQL username, password, and DB name

# Build and run
mvn clean install
mvn spring-boot:run

Backend runs on http://localhost:8080

Frontend Setup
bashcd ../frontend

# Install dependencies
npm install

# Start the development server
npm start

Frontend runs on http://localhost:3000

Database Setup
sqlCREATE DATABASE learnsphere_db;
-- Tables will be auto-created by Hibernate on first run

🤝 Contributing
Contributions are welcome! Here's how to get started:

Fork the repository
Create a new branch: git checkout -b feature/your-feature-name
Make your changes and commit: git commit -m "Add: your feature description"
Push to your fork: git push origin feature/your-feature-name
Open a Pull Request

Please follow clean code practices and include comments where necessary.

👩‍💻 Author
Prateeksha S
Associate Software Engineer | Full Stack Developer
GitHub • LinkedIn

📄 License
This project is open source and available under the MIT License.
