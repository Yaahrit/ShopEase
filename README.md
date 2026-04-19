# 🛒 ShopEase — E-Commerce Web Application

<p align="center">
  <img src="https://img.shields.io/badge/React-18.2.0-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Bootstrap-5.2.3-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white"/>
  <img src="https://img.shields.io/badge/Recoil-State_Management-3578E5?style=for-the-badge&logo=react&logoColor=white"/>
  <img src="https://img.shields.io/badge/React_Router-v6-CA4245?style=for-the-badge&logo=reactrouter&logoColor=white"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge"/>
</p>

<p align="center">
  A fully responsive <strong>E-Commerce web application</strong> built with React 18, featuring product browsing,
  user authentication, cart management, and a complete multi-page experience.
</p>

<p align="center">
  <a href="#">🌐 Live Demo</a> &nbsp;|&nbsp;
  <a href="#-getting-started">⚙️ Setup</a> &nbsp;|&nbsp;
  <a href="#-features">✨ Features</a>
</p>

---

## ✨ Features

- 🏠 **Home Page** — Hero section with product carousels and sliders
- 🛍️ **Product Page** — Dynamic product detail view with routing (`/product/:prodid`)
- 🔐 **Authentication** — Login, Signup, and Forgot Password flows
- 🛒 **Cart Management** — Add/remove products with real-time state updates
- 👤 **User Profile** — Dynamic profile page with active page routing
- 📄 **Static Pages** — About, Contact, FAQ, Terms & Conditions, Privacy Policy
- 🔔 **Toast Notifications** — Real-time feedback using React Toastify
- 📱 **Fully Responsive** — Mobile-first design using React Bootstrap
- 🚫 **404 Page** — Custom Not Found page for invalid routes

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|-----------|
| Frontend Framework | React 18 |
| Routing | React Router DOM v6 |
| State Management | Recoil |
| UI Library | React Bootstrap 5 |
| Carousels | React Slick, React Multi Carousel |
| Notifications | React Toastify |
| Styling | CSS3, Bootstrap 5 |

---

## 📁 Project Structure

```
ShopEase/
│
├── public/                   # Static public assets
└── src/
    ├── ASSETS/               # Images, icons, static files
    ├── COMPONENTS/           # Reusable UI components (Navbar, Footer, etc.)
    ├── PAGES/
    │   ├── HomePage/         # Landing page with carousels
    │   ├── Product/          # Product detail page
    │   ├── Cart/             # Shopping cart
    │   ├── Auth/             # Login, Signup, ForgotPassword
    │   ├── User/             # User profile page
    │   └── Extra/            # About, Contact, FAQ, T&C, Privacy Policy
    ├── Providers/            # Recoil state providers
    ├── App.js                # Main app with route definitions
    └── index.js              # Entry point
```

---

## 🗺️ App Routes

| Route | Page |
|-------|------|
| `/` | Home |
| `/product/:prodid` | Product Detail |
| `/login` | Login |
| `/signup` | Signup |
| `/forgotpassword` | Forgot Password |
| `/cart` | Shopping Cart |
| `/user/:activepage` | User Profile |
| `/about` | About Us |
| `/contact` | Contact |
| `/FAQ` | FAQ |
| `/termsandconditions` | Terms & Conditions |
| `/privacypolicy` | Privacy Policy |
| `*` | 404 Not Found |

---

## ⚙️ Getting Started

### Prerequisites
- Node.js v16+
- npm v8+

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/yaahrit/ShopEase.git
cd ShopEase

# 2. Install dependencies
npm install

# 3. Start development server
npm start
```

Open your browser at:
```
http://localhost:3000
```

### Build for Production

```bash
npm run build
```

---

## 🚀 Planned Enhancements

- [ ] Backend integration with Spring Boot REST API
- [ ] Payment gateway integration (Razorpay/Stripe)
- [ ] Product search and filter functionality
- [ ] Order history and tracking
- [ ] Admin dashboard for product management
- [ ] JWT-based secure authentication

---

## 🤝 Contributing

```bash
git checkout -b feature/your-feature-name
git commit -m "Add: your feature description"
git push origin feature/your-feature-name
# Open a Pull Request
```

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Yash Raj**

<p>
  <a href="https://yashrajhub.netlify.app">
    <img src="https://img.shields.io/badge/Portfolio-FF6B00?style=flat&logo=vercel&logoColor=white"/>
  </a>
  <a href="https://linkedin.com/in/yashrajhub">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://github.com/yaahrit">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white"/>
  </a>
</p>

---

<p align="center">⭐ Star this repo if you found it useful!</p>
