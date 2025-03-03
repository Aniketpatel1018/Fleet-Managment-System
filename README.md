🚗 Fleet Management System (FLEEMAN) 🛠️
FLEEMAN is a microservices-based application designed for efficient vehicle reservations, handovers, and returns. It features a React.js frontend and robust backends powered by ASP.NET Core and Spring Boot.

🌟 Key Features
🔗 Microservices Architecture: Modular services for booking, user management, and vehicle inventory.

🔐 Secure Authentication: JWT-based authentication and authorization.

🔏 Password Encryption: Strong hashing for user credentials.

📜 Logging & Monitoring: Centralized logging with industry-standard tools.

💻 Cross-Platform Compatibility: React.js frontend communicating via REST APIs.

🏗️ Tech Stack
🎨 Frontend
⚛️ React.js

🎨 Bootstrap

📡 Fetch API for communication

🔙 Backend
⚙️ ASP.NET Core (.NET 8, EF Core with MySQL, ASP.NET Identity, Serilog)

☕ Spring Boot (Spring Boot 6, Spring Security with JWT, Hibernate & JPA, Logback)

🗄️ Database
🐬 MySQL

🚀 DevOps
🐳 Docker for containerization

🤖 GitHub Actions for CI/CD automation

⚙️ Installation & Setup
📌 Prerequisites
🎭 Node.js (for React.js frontend)

🛠️ .NET SDK (for ASP.NET Core services)

☕ Java 17+ (for Spring Boot services)

🐬 MySQL Server

📥 Clone the Repository
bash
Copy
git clone https://github.com/yourusername/fleeman.git
cd fleeman
🔙 Backend Setup
⚙️ ASP.NET Core Services
bash
Copy
cd backend-dotnet
dotnet restore
dotnet run
☕ Spring Boot Services
bash
Copy
cd backend-springboot
./mvnw spring-boot:run
🎨 Frontend Setup
bash
Copy
cd frontend
npm install
npm start
📜 API Documentation
API endpoints and usage details are available in docs/api-spec.md or as a Postman collection.

🚀 Deployment
Use Docker for containerization.

Automate CI/CD with GitHub Actions.
