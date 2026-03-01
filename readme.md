# 🍽️ CampusBite — Pre-Ordering Canteen Management System

> A modern, web-based pre-ordering platform for college canteens that eliminates queues, reduces wait times, and streamlines food service operations.

![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-Express-339933?logo=node.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/Database-MongoDB_Atlas-47A248?logo=mongodb&logoColor=white)
![Firebase](https://img.shields.io/badge/Auth-Firebase-FFCA28?logo=firebase&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Styling-Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)

---

## 📌 About the Project

CampusBite is a full-stack campus canteen ordering system developed as a Project-Based Learning (PBL) submission for the Bachelor of Technology in Computer Science and Engineering at **Hyderabad Institute of Technology and Management (HITAM)**, affiliated to JNTUH, Hyderabad — Academic Year 2025–2026.

The system addresses real problems faced in institutional canteens: long queues, manual billing errors, poor inventory tracking, and delayed service during peak hours. CampusBite solves these by offering an online pre-ordering platform for students and staff, along with a powerful admin dashboard for canteen management.

---

## 👨‍💻 Team Members

| Name | Roll Number |
|------|-------------|
| K. Saisri | 24E55A0511 |
| P. Lakshmi Prasanna | 23E51A05A5 |
| M. Rajesh | 23E51A05B9 |
| P. Shourya Prabhas | 23E51A05D0 |

---

## ✨ Features

### 👩‍🎓 Student Features
- **Menu Browsing** — Browse food items with images, descriptions, prices, and categories
- **Shopping Cart** — Add/remove items with quantity controls
- **Pre-Ordering** — Place orders in advance and set a preferred pickup time
- **Online Payment** — Secure payment processing integration
- **Order Tracking** — Real-time order status updates
- **Order History** — View all past orders and their statuses
- **Notifications** — Live order status notifications
- **Multi-language Support** — English, Telugu (తెలుగు), and Hindi (हिन्दी)

### 🛠️ Admin Features
- **Dashboard** — Overview of all orders with urgency indicators
- **Order Management** — Update order statuses as they progress
- **Menu Management** — Add, edit, and delete menu items with images
- **Analytics** — View popular items, peak hours, and revenue trends
- **Real-time Notifications** — Instant alerts for incoming orders

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React.js 18, HTML5, CSS3, JavaScript |
| Styling | Tailwind CSS |
| Routing | React Router DOM |
| Icons | Lucide React |
| State Management | React Context API |
| Backend | Node.js with Express.js |
| Database | MongoDB Atlas |
| Authentication & Hosting | Firebase |
| Build Tool | Create React App |
| Dev Tools | Visual Studio Code, GitHub |

---

## 📁 Project Structure

```
src/
├── components/           # Shared UI components
│   ├── Navbar.jsx
│   ├── Footer.jsx
│   ├── Button.jsx
│   ├── Modal.jsx
│   ├── LoadingSpinner.jsx
│   └── LanguageSelector.jsx
├── contexts/             # React Context providers
│   ├── AuthContext.jsx
│   ├── CartContext.jsx
│   └── LanguageContext.jsx
├── student/              # Student-facing pages
│   ├── MenuPage.jsx
│   ├── CartPage.jsx
│   ├── OrdersPage.jsx
│   └── NotificationsPage.jsx
├── admin/                # Admin-facing pages
│   ├── DashboardPage.jsx
│   ├── MenuManagementPage.jsx
│   └── AnalyticsPage.jsx
├── pages/                # General pages
│   └── Login.jsx
├── utils/                # Utility functions
│   ├── api.js            # API layer
│   ├── helpers.js        # Helper functions
│   └── languages.js      # Multi-language support
├── data/
│   └── dummyData.js      # Sample menu data
└── App.js                # Root component
```

---

## ⚙️ Getting Started

### Prerequisites
- Node.js v14 or higher
- npm or yarn
- A Firebase project (for auth and hosting)
- MongoDB Atlas account (for database)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/campusbite.git
   cd campusbite
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure environment variables**

   Create a `.env` file in the root directory:
   ```env
   REACT_APP_FIREBASE_API_KEY=your_api_key
   REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
   REACT_APP_FIREBASE_PROJECT_ID=your_project_id
   REACT_APP_MONGODB_URI=your_mongodb_connection_string
   ```

4. **Start the development server**
   ```bash
   npm start
   ```

5. **Open in browser**
   ```
   http://localhost:3000
   ```

---

## 🔑 Demo Credentials

| Role | Email | Password |
|------|-------|----------|
| Student | student@hitam.org | password123 |
| Admin | admin@hitam.org | password123 |

> ⚠️ These are for demo/testing purposes only. Change credentials before deploying to production.

---

## 🚀 Deployment

### Build for Production
```bash
npm run build
```
This generates an optimized `build/` folder ready for deployment.

### Deploy to Firebase Hosting
```bash
firebase login
firebase init hosting
firebase deploy
```

---

## 📸 Screenshots

| Welcome Page | Login / Registration |
|---|---|
| ![Welcome](screenshots/welcome.png) | ![Login](screenshots/login.png) |

| Admin Dashboard | Menu Management |
|---|---|
| ![Dashboard](screenshots/admin-dashboard.png) | ![Menu](screenshots/menu-management.png) |

| User Menu Page | Order Confirmation |
|---|---|
| ![Menu](screenshots/user-menu.png) | ![Order](screenshots/order-confirm.png) |

> Add your screenshots to a `/screenshots` folder in the repository.

---

## 🌐 Multi-language Support

The application supports three languages switchable from the navbar:

| Language | Code |
|----------|------|
| English | `en` (Default) |
| Telugu | `te` |
| Hindi | `hi` |

---

## 🧪 Testing

```bash
npm test
```

Testing includes unit tests, integration tests, and user acceptance testing to verify each module and the complete system flow.

---

## 🔮 Future Enhancements

- [ ] QR-based order pickup system
- [ ] AI-based food recommendations
- [ ] Mobile application (Android/iOS)
- [ ] SMS/Email order confirmation
- [ ] Advanced analytics and reporting dashboard
- [ ] Loyalty/reward points system

---

## 📚 References

- Silberschatz, Korth & Sudarshan — *Database System Concepts*, 7th Ed.
- Roger S. Pressman — *Software Engineering: A Practitioner's Approach*, 8th Ed.
- Ian Sommerville — *Software Engineering*, 10th Ed.
- [Firebase Documentation](https://firebase.google.com/docs)
- [W3Schools](https://www.w3schools.com)
- [GeeksforGeeks](https://www.geeksforgeeks.org)
- [IEEE Xplore](https://ieeexplore.ieee.org)

---

## 🏫 Institution

**Hyderabad Institute of Technology and Management (HITAM)**  
Department of Computer Science and Engineering  
Affiliated to JNTUH, Autonomous — Hyderabad, Telangana  
Academic Year: 2025–2026

---

## 📄 License

This project was developed for academic purposes under HITAM's PBL program. All rights reserved by the authors.

---

<p align="center">Made with ❤️ by Team CampusBite — HITAM CSE 2025–26</p>
