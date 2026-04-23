# 🛹 PERFORMANCE SB — URBAN TALENT
### *Redefining Skateboarding culture through technology.*

---

![Performance SB Status](https://img.shields.io/badge/Status-Live-brightgreen)
![Tech Stack](https://img.shields.io/badge/Stack-React%2019%20%7C%20Vite%20%7C%20Tailwind%204-blue)
![Deployment](https://img.shields.io/badge/Deployment-Docker%20%2B%20Nginx-blueviolet)
![License](https://img.shields.io/badge/License-Proprietary-red)

## 📖 Overview

**Performance SB** is not just an app; it is the ultimate digital ecosystem for **Skateboarding** in Colombia. Born from the need to professionalize urban talent, our platform connects enthusiasts, learners, and experts under a high-performance technical infrastructure.

From managing personalized training sessions to a premium equipment store, Performance SB centralizes all the necessary tools for the "skate life" to scale to the next level.

---

## 🚀 Main Modules

### 🛒 SB Store (E-Commerce)
An immersive shopping experience designed for skaters.
*   **Dynamic Catalog:** Advanced product and equipment filtering.
*   **Premium Details:** Technical visualization of decks, trucks, wheels, and accessories.
*   **Seamless Checkout:** Optimized shopping cart and real-time order management.

### 📅 Training & Academy
The heart of learning at Performance SB.
*   **Specialized Classes:** Booking and tracking of training sessions.
*   **Community Events:** Interactive calendar with competitions, jams, and group sessions.
*   **Pre-registration:** Simplified system for joining the academy.

---

## 👥 Profile Architecture

The platform offers segmented experiences to ensure that every user finds what they need:

| Profile | Responsibilities and Tools |
| :--- | :--- |
| **🎓 Student** | Personal progress dashboard, scheduled class viewing, purchase history, and "Skaters Profile" management. |
| **🧘‍♂️ Instructor** | Assigned student management, class attendance control, monitoring of service sales, and professional configuration panel. |
| **👤 Client / Guest** | Landing Page exploration, store access, event registration, and simplified registration process. |

---

## 🛠️ Tech Stack (High-End)

The project uses the most cutting-edge technologies to ensure a world-class UI/UX:

### **Frontend Core**
*   **React 19:** The latest standard for reactive interfaces.
*   **Vite:** Ultra-fast build tool for a smooth development experience.
*   **Tailwind CSS 4:** Utility-first design with a "Street & Urban" aesthetic.

### **Interactivity and Visuals**
*   **Framer Motion:** Fluid animations that bring life to every scroll and click.
*   **Lucide React:** Clean and modern vector iconography.
*   **Recharts:** Visualization of performance and sales metrics.
*   **Canvas Confetti:** Positive visual feedback for achievements and purchases.

### **Infrastructure and Deployment**
*   **Docker:** Full containerization for absolute portability.
*   **Nginx:** High-performance server configuration for traffic handling and security.
*   **Axios:** API service consumption with advanced error handling.

---

## 📂 Project Structure

```text
src/
├── features/            # Main modules (Landing, Dashboards, Auth)
│   ├── landing/         # Public experience and store
│   ├── dashboards/      # Role-specific private panels (Student, Instructor)
│   └── Auth/            # Access management and security
├── context/             # Global states (Authentication, Cart)
├── services/            # Backend communication logic
├── hooks/               # Custom hooks for reusable logic
└── utils/               # Validation, date, and formatting helpers
```

---

## ⚙️ Quick Start Guide

### Manual Installation
1.  **Clone the repository:** `git clone https://github.com/...`
2.  **Install dependencies:**
    ```bash
    npm install
    ```
3.  **Configure Environment Variables:** Create a `.env` file based on `.env.example`.
4.  **Run in Development:**
    ```bash
    npm run dev
    ```

### Deployment with Docker
```bash
docker-compose up --build
```

---

## 🛡️ License and Ownership

This software is the exclusive intellectual property of **Performance SB**. Any total or partial reproduction without authorization is strictly prohibited.

**Development Team:**
*   **Sebastián Vásquez Echavarria**
*   **Emanuel González Jaramillo**
*   **Mariana Granda**
*   **Manuela Granda**

---
*© 2026 Performance SB — Urban Talent & Tech Division.*
