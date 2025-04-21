
# 🔐 JWTAuthSystem

A secure user authentication system using **JWT (JSON Web Tokens)** stored in **HTTP-only cookies**. This project provides a clean and secure way to handle user login, authentication, and protected routes in a Node.js + Express environment.

---

## 📦 Features

- 🧾 User Signup & Login
- 🛡️ JWT Token-based Authentication
- 🍪 JWT stored in HTTP-only cookies
- 🔐 Protected Routes with Middleware
- 🚪 Secure Logout (clears cookie)
- ⚙️ Clean and modular folder structure

---

## 📁 Project Structure

```
JWTAuthSystem/
│
├── controllers/       # Request logic
├── middleware/        # Auth middleware
├── routes/            # API routes
├── utils/             # Helper functions
├── .env               # Environment variables
├── server.js          # App entry point
└── package.json       # Dependencies
```

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/ANKITKUMARBARIK/JWTAuthSystem.git
cd JWTAuthSystem
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Setup Environment Variables

Create a `.env` file in the root directory:

```
PORT=8000
JWT_SECRET=your_jwt_secret
```

### 4. Run the Server
```bash
npm start
```

---

## 🔐 How It Works

- On **login**, the server generates a JWT and sends it in a secure cookie.
- All **protected routes** check for the cookie and validate the token.
- **Logout** clears the cookie on client side.
- Tokens are **HttpOnly**, improving security against XSS.

---

## 🛠️ Tech Stack

- **Node.js**
- **Express.js**
- **JWT (jsonwebtoken)**
- **Cookie-parser**
- **dotenv**

---

## 🤝 Contribution

Pull requests are welcome! Feel free to fork and improve this project. For major changes, please open an issue first.

---

## 📄 License

This project is licensed under the [GNU License](LICENSE).

---

## 🧑‍💻 Author

Made with ❤️ by [Ankit Kumar Barik](https://github.com/ANKITKUMARBARIK)
