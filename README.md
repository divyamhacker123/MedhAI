# 🩺 MedhAI

**MedhAI** is a full-stack AI-powered healthcare SaaS application designed to provide an intelligent and user-friendly platform for healthcare-related services and assistance.

The project follows a **client-server architecture**, with a React-based frontend and a Node.js/Express backend connected to MongoDB.

---

## 🚀 Features

* 🤖 AI-powered healthcare assistance
* 👤 User-friendly interface
* 🔐 Secure backend architecture
* 🌐 RESTful APIs
* 📊 Scalable SaaS architecture
* 💾 MongoDB-based data management
* ⚡ Responsive React.js frontend
* 🧩 Modular backend architecture
* 🔄 Client-server communication through REST APIs

---

## 🏗️ Project Architecture

```text
MedhAI
│
├── client-medhai/          # React.js frontend
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
│
├── server/                 # Node.js + Express backend
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── config/
│   ├── package.json
│   └── ...
│
└── .gitignore
```

### Architecture Overview

```text
        ┌─────────────────────┐
        │      User           │
        └──────────┬──────────┘
                   │
                   ▼
        ┌─────────────────────┐
        │   React Frontend    │
        │     client-medhai   │
        └──────────┬──────────┘
                   │
                REST API
                   │
                   ▼
        ┌─────────────────────┐
        │   Node.js + Express │
        │       Server        │
        └──────────┬──────────┘
                   │
          ┌────────┴─────────┐
          ▼                  ▼
 ┌─────────────────┐  ┌───────────────┐
 │    MongoDB      │  │   AI Services │
 │    Database     │  │   / Logic     │
 └─────────────────┘  └───────────────┘
```

---

## 🛠️ Tech Stack

### Frontend

* **React.js**
* JavaScript
* HTML5
* CSS3
* npm

### Backend

* **Node.js**
* **Express.js**
* REST APIs
* JavaScript

### Database

* **MongoDB**

### Development Tools

* Git
* GitHub
* npm
* Postman
* VS Code

---

## 📂 Folder Structure

### Frontend

The `client-medhai` directory contains the React.js application responsible for the user interface and communication with the backend APIs.

```text
client-medhai/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── ...
├── package.json
└── ...
```

### Backend

The `server` directory contains the backend application built using Node.js and Express.js.

```text
server/
├── controllers/
├── models/
├── routes/
├── middleware/
├── config/
├── package.json
└── ...
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/divyamhacker123/MedhAI.git
```

```bash
cd MedhAI
```

---

### 2. Setup the Backend

```bash
cd server
npm install
```

Create a `.env` file inside the `server` directory:

```env
PORT=5000
MONGO_URL=your_mongodb_connection_string
```

Start the backend:

```bash
npm start
```

For development:

```bash
npm run dev
```

---

### 3. Setup the Frontend

Open another terminal:

```bash
cd client-medhai
npm install
```

Start the React application:

```bash
npm start
```

The frontend will run on the development server configured by the project.

---

## 🔑 Environment Variables

The backend requires environment variables for configuration.

Example:

```env
PORT=5000
MONGO_URL=your_mongodb_connection_string
```

> ⚠️ Never commit your `.env` file or database credentials to GitHub.

Make sure `.env` is included in `.gitignore`.

---

## 🔄 How It Works

1. The user interacts with the **React.js frontend**.
2. The frontend sends requests to the **Express.js REST APIs**.
3. The backend processes the request.
4. Required information is retrieved from or stored in **MongoDB**.
5. AI-related processing can be handled through the application's AI service/logic.
6. The backend sends the response back to the frontend.
7. React updates the user interface with the result.

---

## 🧪 API Testing

Backend APIs can be tested using **Postman**.

Example:

```text
Client
   │
   │ HTTP Request
   ▼
Express API
   │
   ▼
Controller
   │
   ▼
MongoDB / AI Logic
   │
   ▼
HTTP Response
   │
   ▼
React UI
```

---

## 📈 Future Improvements

* [ ] Advanced AI-powered medical assistance
* [ ] User authentication and authorization
* [ ] Personalized user dashboard
* [ ] AI-based health recommendations
* [ ] Doctor/patient management
* [ ] Appointment management
* [ ] Health record management
* [ ] Improved security
* [ ] Cloud deployment
* [ ] Automated testing
* [ ] Monitoring and analytics

---

## 🎯 Learning Outcomes

Through this project, I worked with:

* Full-stack application development
* React.js frontend development
* Node.js and Express.js backend development
* REST API design
* MongoDB database integration
* Client-server architecture
* Modular backend architecture
* Git and GitHub
* SaaS application development

---

## 👨‍💻 Author

**Divyam Gupta**

* GitHub: [divyamhacker123](https://github.com/divyamhacker123)

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

---

## 📄 License

This project is intended for educational and development purposes.
