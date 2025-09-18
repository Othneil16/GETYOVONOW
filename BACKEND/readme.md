
# GETYOVONOW Backend  

Welcome to the backend codebase for the **GETYOVO multi-vendor e-Commerce Platform**.  
This project provides secure and scalable APIs for user and vendor authentication, product management, cart handling, messaging, notifications, and payments.  

---

## 🚀 Tech Stack  
- **Server:** Express.ts  
- **ORM:** Prisma  
- **Database:** PostgreSQL  
- **Authentication:** JWT, Session, Google Auth & Argon2  
- **File Uploads:** Cloudinary  
- **Payments:** Stripe / Paystack  

---
# 📁 Folder Structure  

backend/
├── controllers/ # Business logic
├── routes/ # API endpoints
├── middleware/ # Auth, error handling
├── prisma/ # Prisma schema & migrations
├── config/ # Configuration files
├── .env # Environment variables
└── server.ts # App entry point

---

# ⚙️ Setup Instructions  

- **Clone the Repository**  
  ```bash
  git clone https://github.com/Othneil16/GETYOVONOW.git
  cd Backend
Install Dependencies

npm install
Configure Environment Variables
Create a .env file and add:
env
PORT=5000
DATABASE_URL="postgresql://user:password@localhost:5432/momentom_db"
JWT_SECRET=your_jwt_secret

Set Up the Database
npx prisma migrate dev --name init
npx prisma generate
Run the Server
npm run dev

🧪 API Endpoints
Sign Up → POST /api/v1/auth/signup

Login → POST /api/v1/auth/login

Get Profile → GET /api/v1/users/:userId

Product CRUD → GET/POST/PUT/DELETE /api/v1/products

Cart → GET/POST /api/v1/cart

Messages → GET/POST /api/v1/messages

Orders → GET/POST /api/v1/orders

Notifications → GET/PUT /api/v1/notifications

🔐 Security Features
Password hashing (argon2)

JWT, Session, and Google Auth authentication

Secure .env for sensitive data

Input validation planned using Zod

🤝 Contributing
Fork the repository

Create a new branch:
git checkout -b feature-name
Commit your changes:
git commit -m "Added feature"
Push to the branch:
git push origin feature-name
Open a Pull Request

📄 License
This project is licensed under the MIT License.

👨‍💻 Maintainer
Othneil Victory

Backend Team Lead

📧 othneilvictory16@gmail.com
