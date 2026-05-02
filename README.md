# ⚖️ LegalEase – Full Stack Legal Management System

A full-stack web application designed to streamline legal services by connecting **clients, lawyers, and admins** on a single platform. Users can manage cases, book appointments, and track legal progress efficiently.

---

## 🚀 Features

### 👤 Authentication
- User registration and login
- Role-based access:
  - Client
  - Lawyer
  - Admin

### 👩‍⚖️ Lawyer Features
- Manage assigned cases
- View and update case details
- Handle appointments
- Update profile and settings

### 👨‍💼 Client Features
- Browse lawyers
- Book appointments
- Track case progress
- View case timelines

### 🛡️ Admin Features
- Manage users (clients and lawyers)
- Verify lawyer profiles
- Monitor cases
- Access admin dashboard

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Vite

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Other Tools
- JWT Authentication
- Multer (for file uploads)

---

## 📁 Project Structure

```

legal-system/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── uploads/
│   ├── seed.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   │   ├── admin/
│   │   │   ├── client/
│   │   │   └── lawyer/
│   │   ├── context/
│   │   └── utils/
│   └── package.json
│
└── README.md

````

---

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/legal-system.git
cd legal-system
````

---

### 2. Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file in the backend folder:

```
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
```

Run backend:

```bash
npm start
```

---

### 3. Setup Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 🔗 API Modules

* Authentication (Login / Register)
* Case Management
* Appointment Booking
* Client Management
* Lawyer Profiles
* Admin Controls

---

## 📸 Screenshots

*Add screenshots of your application here (homepage, dashboards, etc.)*

---

## 💡 Future Enhancements

* Real-time notifications
* Chat system between lawyer and client
* Mobile application
* AI-based legal suggestions

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## 👩‍💻 Author

**Devi Priya**
B.Tech CSE Student

---

## 📜 License

This project is licensed under the MIT License.

---

## ⭐ Acknowledgements

* Open-source community
* Online tutorials and documentation

```

---

If you want to make it **stand out for placements**, next step I recommend:
- Add **live demo link**
- Add **screenshots**
- Add **“How it works” section (2–3 lines)**

Tell me — I’ll upgrade this to a **top-tier GitHub README 🔥**
```
