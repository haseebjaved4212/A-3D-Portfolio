# 3D Developer Portfolio

A modern, immersive, and fully responsive 3D developer portfolio website built with React, Three.js, and Tailwind CSS. This project showcases advanced 3D graphics, smooth animations, and a clean, futuristic UI to present professional work and skills.

## 🚀 Features

-   **Immersive 3D Hero Section**: Features a high-quality 3D computer scene with interactive elements.
-   **Interactive 3D Models**: Uses React Three Fiber and Drei to render and manipulate 3D assets.
-   **Smooth Animations**: Powered by GSAP (GreenSock Animation Platform) for fluid transitions and effects.
-   **Responsive Design**: Fully optimized for all devices, from desktops to mobile phones, using Tailwind CSS.
-   **Dynamic Content**: Easy to update content via a centralized constants file.
-   **Contact Form**: Functional contact form with email integration (EmailJS).
-   **Tech Stack Display**: Visual representation of skills and technologies.

## 🛠 Tech Stack

-   **Frontend Framework**: [React](https://react.dev/)
-   **Styling**: [Tailwind CSS](https://tailwindcss.com/)
-   **3D Graphics**: [Three.js](https://threejs.org/), [React Three Fiber](https://docs.pmnd.rs/react-three-fiber), [React Three Drei](https://github.com/pmndrs/drei)
-   **Animations**: [GSAP](https://gsap.com/)
-   **Build Tool**: [Vite](https://vitejs.dev/)
-   **Linting**: ESLint

## 📦 Prerequisites

Before you begin, ensure you have the following installed:

-   [Node.js](https://nodejs.org/) (Version 16 or higher recommended)
-   [npm](https://www.npmjs.com/) (usually comes with Node.js)

## 🔧 Installation

1.  **Clone the repository**

    ```bash
    git clone https://github.com/haseebjaved4212/3d-portfolio.git
    cd 3d-portfolio
    ```

2.  **Install dependencies**

    ```bash
    npm install
    ```

## 💻 Usage

1.  **Start the development server**

    ```bash
    npm run dev
    ```

    Open [http://localhost:5173](http://localhost:5173) to view it in the browser.

2.  **Build for production**

    ```bash
    npm run build
    ```

3.  **Preview production build**

    ```bash
    npm run preview
    ```

## 📂 Project Structure

A brief overview of the important directories:

```
src/
├── assets/         # Static assets like images and potential local sounds
├── components/     # Reusable UI components (NavBar, CanvasLoader, etc.)
├── constants/      # Configuration file for text, links, and data (index.js)
├── sections/       # Main sections of the landing page (Hero, About, features, etc.)
├── App.jsx         # Main application entry point
└── main.jsx        # React root rendering
```

## ⚙️ Customization

You can easily update the portfolio content without touching the core logic. Open `src/constants/index.js` to modify:

-   Navigation Links
-   Hero Text ("Words")
-   Skills & Abilities
-   Experience Data
-   Testimonials
-   Social Media Links
-   Tech Stack Icons

## 🤝 Contributing

Contributions are welcome! If you have suggestions for layout changes or new 3D models to integrate, feel free to open an issue or submit a pull request.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📄 License

Copyright © 2025 Haseeb Javed. All rights reserved.

---

<h3 align="center">
    <p>Happy Coding 💖</p>
</h3>