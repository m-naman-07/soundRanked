# 🎧 Sound Ranked – Frontend

This is the **frontend** repository for **Sound Ranked: Music Rating & Review Platform**, a web application where users can browse music albums, rate them, and contribute reviews. Built using **React**, **Tailwind CSS**, and **Framer Motion**, it offers an animated, responsive, and user-focused interface.

---
- 🚀 **Live Site (GitHub Pages)**: https://m-naman-07.github.io/soundRanked/
---

## 📌Tech Stack

| Technology        | Purpose                            |
|-------------------|-------------------------------------|
| React             | Component-based frontend framework |
| Tailwind CSS      | Utility-first responsive styling   |
| Framer Motion     | Smooth and performant animations   |
| React Router DOM  | Page navigation and routing        |
| Axios (optional)  | API requests to backend            |
| Vite or CRA       | Frontend build tool (assumed Vite) |

---

## ✨ Features Implemented (Frontend)

### ✅ Landing Page
- Beautiful **hero section** with motion-based gradient background using `Framer Motion`.
- Responsive layout using Tailwind’s utility classes.
- Search bar and CTA buttons.

### ✅ Navigation Bar
- Implemented using React.
- Dynamic highlighting of current route using `NavLink`.
- Links to Home, Rankings, Favorites, Login, and Signup.

### ✅ Routing
- Built using `react-router-dom`.
- Client-side navigation between:
  - `/` – Home
  - `/rankings` – Album Rankings
  - `/favorites` – Favorite Albums
  - `/login` – Login Page
  - `/signup` – Signup Page

### ✅ Cards & Components
- `Card01` and `Card02`: Reusable components showing albums or features.
- Fully responsive grid layout.
- Animated entry transitions using `motion.div`.

### ✅ Rankings Page
- Lists albums sorted by backend-calculated average ratings.
- Styled tables using Tailwind.

### ✅ Authentication Pages (UI Only)
- Login and Signup forms designed with validation.
- Placeholder submission logic (integration pending or handled via API).

### ✅ Favorites Page
- Displays albums added to favorites by logged-in users.
- Interaction logic can be extended using JWT-protected API calls.

---

## 🧠 Customizations & Enhancements

| Area        | Description                                                                 |
|-------------|-----------------------------------------------------------------------------|
| 🖼 UI Design | Switched from default React styles to **Tailwind CSS** for full responsiveness |
| 🎨 UX Motion| Added `Framer Motion` animations for hero section and cards                |
| 🌈 Theme     | Dynamic radial background gradient using motion values and color animation |
| 🔄 Routing   | Configured `react-router-dom` for seamless SPA navigation                 |
| 📦 Structure | Organized all UI into reusable, isolated React components                 |
| 🔐 Auth UI   | Designed functional login/signup pages with future API integration planned |

---

## 🛠️ Installation & Running Locally

### Prerequisites
- Node.js (v16+ recommended)
- npm or yarn

### Steps

```bash
# Clone the repository
git clone https://github.com/your-username/sound-ranked-frontend.git
cd sound-ranked-frontend

# Install dependencies
npm install

# Start the development server
npm run dev   # or `npm start` if using CRA

# Open in browser
http://localhost:5173   # or http://localhost:3000 (CRA)
```

---

## 📁 Folder Structure 
```
src/
├── components/
│   ├── Navbar.jsx
│   ├── Search.jsx
│   ├── Card01.jsx
│   ├── Card02.jsx
│   ├── Rankings.jsx
│   ├── Login.jsx
│   ├── Signup.jsx
│   ├── Favorites.jsx
├── App.jsx
├── main.jsx
├── index.css
```

---
## 👨‍🎓 Author

- **AKANKSHA SNEHAL & NAMAN MISHRA**
- Roll No: 12411074 & 12411094
- B tech CSE 1st year ,IIIT SONEPAT

---

