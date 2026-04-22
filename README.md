# 📱 Sok Bunleab - Portfolio

> **Mobile Developer & Web Developer& Software Engineering Student**
> *Exploring the intersection of mobile development and modern web experiences.*

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)

A highly interactive portfolio website built to showcase mobile development achievements, front-end software development projects, and professional experience.

---

## 📸 Screenshots

<p align="center">
  <img src="public/images/image.png" alt="Hero Section" width="100%"/>
</p>

<p align="center">
  <img src="public/images/image copy.png" alt="About Section" width="48%"/>
  <img src="public/images/image copy 2.png" alt="Experience Section" width="48%"/>
</p>

<p align="center">
  <img src="public/images/image copy 3.png" alt="Skills Section" width="48%"/>
  <img src="public/images/image copy 4.png" alt="Projects Section" width="48%"/>
</p>

<p align="center">
  <img src="public/images/image copy 5.png" alt="Contact Section" width="100%"/>
</p>

---

## ✨ Key Features

- **🎨 Modern Aesthetic**: Custom neon design system with glassmorphism and dynamic effects.
- **📱 Responsive Design**: Fully optimized for Desktop, Laptop, Tablet, and Mobile devices.
- **✉️ Secure Contact Form**:
  - Integrated with **EmailJS** for serverless, secure email delivery.
  - Custom **Toast Notification System** for real-time user feedback.
- **🏗️ Dynamic Architecture**:
  - **Experience Timeline**: Vertical interactive timeline connecting academic and industry projects.
  - **Achievement Carousel**: Auto-playing image gallery for certifications and event participations.
  - **Project Hub**: GitHub API integration to fetch and display live repository statistics.

## 🛠️ Tech Stack

- **Frontend**: React 18
- **Build Tool**: Vite
- **Animations**: Framer Motion
- **Styling**: CSS Modules with CSS Variables (Theming)
- **Email Service**: EmailJS
- **Icons**: Lucide React / Custom SVG

## 🚀 Quick Start

1. **Clone the repository**

   ```bash
   git clone https://github.com/leap170505/portfolio.git
   ```
2. **Install dependencies**

   ```bash
   cd portfolio
   npm install
   ```
3. **Environment Setup**
   Create a `.env` file based on `.env.example` to set up EmailJS and GitHub configuration.
4. **Start local server**

   ```bash
   npm run dev
   ```
5. **Build for production**

   ```bash
   npm run build
   ```

## 📁 Project Structure

```bash
src/
├── components/
│   ├── Navbar/       # Responsive navigation
│   ├── Hero/         # 3D interactive landing section
│   ├── About/        # Profile & Bio
│   ├── Experience/   # Vertical Professional Timeline
│   ├── Projects/     # GitHub API integrated project cards
│   ├── Contact/      # EmailJS form with validation
│   └── Toast/        # Custom notification system
├── styles/
│   └── global.css    # Theme variables & animations
└── main.jsx          # Entry point
```

## 📧 Contact Configuration

To make the contact form work:

1. Create an account on [EmailJS](https://www.emailjs.com/).
2. Create a standardized email template.
3. Update the `.env` file with your specific `VITE_EMAILJS_SERVICE_ID`, `VITE_EMAILJS_TEMPLATE_ID`, and `VITE_EMAILJS_PUBLIC_KEY`.

*Built with 💚 and 💻 by [Sok Bunleab](https://github.com/leap170505)*
