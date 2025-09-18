
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
## 📁 Folder Structure

```text
backend/
├── controllers/       # Business logic
├── routes/            # API endpoints
├── middleware/        # Auth, error handling
├── prisma/            # Prisma schema & migrations
├── config/            # Configuration files
├── .env               # Environment variables
├── server.ts         # App entry point
```

---
## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/Othneil16/GETYOVONOW.git
cd BACKEND
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Configure Environment Variables
Create a `.env` file and add:
```env
PORT=5000
DATABASE_URL="postgresql://user:password@localhost:5432/getyovonow_db"
JWT_SECRET=your_jwt_secret
```

### 4. Set Up the Database
```bash
npx prisma migrate dev --name init
npx prisma generate
```

### 5. Run the Server
```bash
npm run dev
```
### 6. Online Server For Testing in
```text
still-in-development
```
---

## 🧪 API Endpoints

| Feature        | Method | Endpoint                      |
|----------------|--------|-------------------------------|
| Sign Up        | POST   | /api/v1/auth/signup              |
| Login          | POST   | /api/v1/auth/login               |
| Get Profile    | GET    | /api/v1/users/:userId            |
  
---

 🔐 Security Features
- Password hashing (argon2)
- JWT, Session, and Google Auth authentication
- Secure `.env` for sensitive data
- Input validation planned using Zod

---

## 🤝 Contributing
1. Fork the repository
2. Create a new branch(the branch should not be named master📌) : `git checkout -b feature-name`
3. Commit your changes: `git commit -m "Added feature"`
4. Push to the branch: `git push origin feature-name`
5. Open a Pull Request

---
## 📄 License
This project is licensed under the MIT License.

## 👨‍💻 Maintainer
Othneil Victory

## Backend Team Lead

📧 othneilvictory16@gmail.com



knjn;oino;
jbvlhvb.uvblj