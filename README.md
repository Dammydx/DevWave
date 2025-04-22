# DevWave – Irewole Daramola’s Developer Portfolio Website

A modern, animated personal portfolio to showcase real projects, skills, and links, built with React, TailwindCSS, and Supabase Auth.

---

## 🌎 Live Site
View the portfolio:    
https://dammydx.github.io/DevWave/

---

## 📄 Project Overview
DevWave is a sleek and fully-responsive portfolio site built for Irewole Daramola. It serves as a central hub to:

- Showcase real, live projects with rich descriptions and visuals
- Highlight technical skills and tools
- Allow visitors to contact Daramola directly
- Provide a password-protected admin panel for managing project data stored in Supabase

All project data is fetched dynamically from Supabase, allowing seamless future updates without modifying code.

---

## 🔮 Features

### 🚀 Welcome/Home Page
- Bold hero section with animated heading and bio
- Live background effect (particles / morphing gradient / waves)
- CTA buttons: **View Projects**, **Get in Touch**
- Smooth scroll navigation

### 📂 Projects Page
- Live project cards with:
  - Name
  - Stack (badges)
  - Description
  - Live Link & GitHub Link
  - Project image/mockup
- Filter by tags (React, Supabase, Fullstack, etc.)
- Scroll animations
- Data pulled from Supabase

### 🤵 About Me Page
- Avatar/Profile photo
- Full bio and developer journey
- Skill tags/progress bars
- Tech tool logos
- Downloadable CV/Resume

### 📬 Contact Page
- Form: Name, Email, Message
- Supabase function handles submission
- Toast/modal on success
- Links to GitHub, X, LinkedIn
- Optional: embed Calendly

### 🚪 Admin Panel (Password-Protected)
- Accessible from navbar/footer
- Password: `*****`
- Add/Edit/Delete projects:
  - Name
  - Description
  - Tags
  - Live Link
  - GitHub Repo
  - Image upload
- View submitted messages (admin only)

---

## 📍 Routes
- `/` → Home
- `/projects` → Projects
- `/about` → About Me
- `/contact` → Contact
- `/admin` → Admin Panel

---

## 🎨 Theme & Design
- **Theme Name:** NeoClassic Portfolio
- **Design Style:** Modern, clean, soft shadows, rounded UI
- **Typography:** Inter / Poppins

### 🌈 Color Palette
- Background: `#FFFFFF`
- Primary: `#1D4ED8` (Indigo)
- Accent: `#22D3EE` (Cyan)
- Surface: `#F3F4F6` (Light Gray)
- Text: `#1F2937` (Slate)
- Highlight: Indigo → Cyan Gradient

### ✨ UI Enhancements
- Page load animations
- Button ripple effects
- Scroll-triggered section highlights

---

## 🛠️ Tech Stack
- **Frontend:** React, TailwindCSS, Vite
- **Backend/Auth:** Supabase
- **Animations:** Framer Motion
- **Icons:** Heroicons, Lucide
- **Notifications:** React-Toastify
- **Storage:** Supabase File Storage

---

## 💡 How to Run Locally
1. Clone the repo
2. Install dependencies:
   ```bash
   npm install
   ```
3. Add a `.env` file:
   ```env
   VITE_SUPABASE_URL=your_url
   VITE_SUPABASE_ANON_KEY=your_key
   ```
4. Run the dev server:
   ```bash
   npm run dev
   ```

---

## 📆 How to Add New Projects (via Admin Panel)
1. Navigate to `/admin`
2. Enter the password: `****`
3. Use the form to:
   - Add project title, description, tags, links
   - Upload an image
   - Submit to store in Supabase

---

## 🔷 Folder Structure
```
/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   ├── utils/
│   ├── App.jsx
│   └── main.jsx
├── .env
├── package.json
├── tailwind.config.js
└── vite.config.js
```

---

## 📋 Other Notes
- Favicon and logo must be placed in `/public`
- Add proper SEO meta tags in each page
- Contact form has validation before submit
- Mobile-first responsive design
- Uses GitHub Pages drag-and-drop deployment method

---

## 📎 Footer
- Animated wave background
- “Built by Irewole Daramola”
- “Proudly sponsored by Dammy’s Tech Hub”
- Admin login link hidden but accessible

