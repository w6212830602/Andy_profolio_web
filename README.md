<div align="center">

# ⚡ Andy Li | Creative Developer Portfolio

> **A reactive, futuristic portfolio featuring neon aesthetics, glassmorphism, and immersive animations.**

[![Live Demo](https://img.shields.io/badge/🚀_View_Live_Demo-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://w6212830602.github.io/Andy_portfolio_web/)

[![React](https://img.shields.io/badge/React-18.2-61DAFB?logo=react&logoColor=black)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Framer Motion](https://img.shields.io/badge/Framer_Motion-Animation-0055FF?logo=framer&logoColor=white)](https://www.framer.com/motion/)

</div>


---

## 📖 Overview

This project is a personal portfolio website designed to showcase my software development skills through immersive UI/UX. Moving away from static, traditional designs, it opts for a **cyberpunk-inspired** aesthetic that emphasizes motion, interactivity, and modern web technologies.

The site is built with **React** and **TypeScript**, ensuring type safety and component modularity, while **Tailwind CSS** handles the complex styling requirements of the neon/glassmorphism theme.

---

## ✨ Key Features

* **⚡ Interactive Hero Section:** Features a typewriter effect and dynamic background elements that grab attention immediately.
* **💎 Glassmorphic UI:** Heavily utilizes backdrop filters, translucent layers, and border glows to create depth.
* **🎬 Advanced Animations:** Powered by **Framer Motion** for complex transitions, scroll-triggered reveals, and layout animations.
* **📇 3D Holographic Card:** A custom-built 3D tilt effect on the contact card that reacts to mouse movement.
* **⏳ Expandable Timeline:** An interactive experience timeline where milestones expand to reveal details upon interaction.
* **🔦 Project Spotlight:** A "spotlight" hover effect on project cards that tracks cursor position for a dynamic lighting feel.
* **📱 Fully Responsive:** Optimized for seamless experiences across mobile, tablet, and desktop devices.

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| **Core** | [React 18](https://react.dev/), [TypeScript](https://www.typescriptlang.org/), [Vite](https://vitejs.dev/) |
| **Styling** | [Tailwind CSS](https://tailwindcss.com/) |
| **Animation** | [Framer Motion](https://www.framer.com/motion/), [Lottie React](https://lottiereact.com/) |
| **Icons** | [Lucide React](https://lucide.dev/) |
| **Fonts** | DM Sans, Space Grotesk, JetBrains Mono |

---

## 🚀 Getting Started

To run this project locally, follow these steps:

### Prerequisites
* Node.js (v16 or higher)
* npm or yarn

### Installation

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/w6212830602/Andy_portfolio_web.git](https://github.com/w6212830602/Andy_portfolio_web.git)
    cd Andy_portfolio_web
    ```

2.  **Install dependencies**
    ```bash
    npm install
    # or
    yarn install
    ```

3.  **Run the development server**
    ```bash
    npm run dev
    # or
    yarn dev
    ```

4.  Open [http://localhost:5173](http://localhost:5173) (or the port shown in your terminal) to view it in the browser.

---

## 📂 Project Structure

```text
/src
  ├── components/       # Reusable UI components (Hero, Navbar, Projects, etc.)
  ├── constants.tsx     # Centralized content (Projects data, Experience logs)
  ├── types.ts          # TypeScript interfaces and type definitions
  ├── App.tsx           # Main application entry point
  └── index.tsx         # Root rendering logic
