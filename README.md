# DMU-CSE-VueHomepage

A multi-page university department homepage built with **Vue 3**, featuring user authentication flows, an academic info section, a gallery, and a responsive layout with hamburger menu support.

---

## 📁 Project Structure

```
DMU-CSE-VueHomepage/
├── public/
│   ├── favicon.ico
│   ├── favicon1.ico
│   └── index.html
├── src/
│   ├── assets/                 # Static assets (images, fonts, etc.)
│   ├── components/
│   │   ├── PageHeader.vue          # Top header bar
│   │   ├── PageLogo.vue            # Department logo
│   │   ├── PageNavbar.vue          # Navigation bar
│   │   ├── PageLogbar.vue          # Login status bar
│   │   ├── PageHamburgerMenu.vue   # Mobile hamburger menu
│   │   ├── PageFooter.vue          # Footer
│   │   └── HelloWorld.vue
│   ├── views/
│   │   ├── HomeView.vue            # Landing page
│   │   ├── AboutView.vue           # About the department
│   │   ├── AcademicView.vue        # Academic information
│   │   ├── GalleryView.vue         # Photo gallery
│   │   ├── LoginView.vue           # Login page
│   │   ├── LogoutView.vue          # Logout page
│   │   ├── SignUp.vue              # Sign up page
│   │   └── ForgotPassword.vue      # Password recovery
│   ├── router/
│   │   └── index.js                # Vue Router configuration
│   ├── store/                      # Vuex store
│   ├── App.vue                     # Root component
│   └── main.js                     # App entry point
├── babel.config.js
├── jsconfig.json
├── vue.config.js
└── package.json
```

---

## ✨ Features

- **Multi-page routing** – 8 pages managed with Vue Router 4 (lazy-loaded for performance)
- **User auth flow** – Login, Sign Up, Logout, and Forgot Password pages
- **Responsive layout** – Hamburger menu component for mobile viewports
- **Vuex state management** – Centralized store for app-wide state
- **Gradient UI** – Beige-to-white gradient background with clean centered layout

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Framework | Vue 3 |
| Routing | Vue Router 4 |
| State Management | Vuex 4 |
| Tooling | Vue CLI 5 |
| Linting | ESLint + Standard style |

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher recommended)
- npm or yarn

### Installation

```bash
git clone https://github.com/Aywah01/DMU-CSE-VueHomepage.git
cd DMU-CSE-VueHomepage
npm install
```

### Running the Dev Server

```bash
npm run serve
```

Then open `http://localhost:8080` in your browser.

### Building for Production

```bash
npm run build
```

Output will be in the `dist/` folder.

### Linting

```bash
npm run lint
```

---

## 🔀 Pages & Routes

| Route | View | Description |
|-------|------|-------------|
| `/` | `HomeView` | Landing page |
| `/about` | `AboutView` | Department info |
| `/academic` | `AcademicView` | Academic programs & info |
| `/gallery` | `GalleryView` | Photo gallery |
| `/login` | `LoginView` | User login |
| `/signup` | `SignUp` | New user registration |
| `/logout` | `LogoutView` | Logout confirmation |
| `/forgot-password` | `ForgotPassword` | Password recovery |

---

## 📄 License

This project is private. All rights reserved.
