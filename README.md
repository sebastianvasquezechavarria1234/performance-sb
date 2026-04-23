# 🛹 PERFORMANCE SB — TALENTO URBANO
### *Redefiniendo la cultura del Skateboarding a través de la tecnología.*

---

![Performance SB Status](https://img.shields.io/badge/Status-Live-brightgreen)
![Tech Stack](https://img.shields.io/badge/Stack-React%2019%20%7C%20Vite%20%7C%20Tailwind%204-blue)
![Deployment](https://img.shields.io/badge/Deployment-Docker%20%2B%20Nginx-blueviolet)
![License](https://img.shields.io/badge/License-Proprietary-red)

## 📖 Visión General

**Performance SB** no es solo un aplicativo; es el ecosistema digital definitivo para el **Skateboarding** en Colombia. Nacido de la necesidad de profesionalizar el talento urbano, nuestra plataforma conecta a entusiastas, aprendices y expertos bajo una infraestructura técnica de alto rendimiento.

Desde la gestión de entrenamientos personalizados hasta una tienda de equipos premium, Performance SB centraliza todas las herramientas necesarias para que el "skate life" escale al siguiente nivel.

---

## 🚀 Módulos Principales

### 🛒 SB Store (E-Commerce)
Una experiencia de compra inmersiva diseñada para skaters.
*   **Catálogo Dinámico:** Filtrado avanzado de productos y equipos.
*   **Detalles Premium:** Visualización técnica de tablas, ejes, ruedas y accesorios.
*   **Checkout Fluido:** Carrito de compras optimizado y gestión de pedidos en tiempo real.

### 📅 Training & Academy
El corazón del aprendizaje en Performance SB.
*   **Clases Especializadas:** Reserva y seguimiento de sesiones de entrenamiento.
*   **Eventos de Comunidad:** Calendario interactivo con competencias, jams y sesiones grupales.
*   **Pre-inscripciones:** Sistema simplificado para unirse a la academia.

---

## 👥 Arquitectura de Perfiles

La plataforma ofrece experiencias segmentadas para garantizar que cada usuario encuentre lo que necesita:

| Perfil | Responsabilidades y Herramientas |
| :--- | :--- |
| **🎓 Estudiante** | Dashboard de progreso personal, visualización de clases programadas, historial de compras y gestión de su "Skaters Profile". |
| **🧘‍♂️ Instructor** | Gestión de alumnos asignados, control de asistencia a clases, monitoreo de ventas de sus servicios y panel de configuración profesional. |
| **👤 Cliente / Invitado** | Exploración de la Landing Page, acceso a la tienda, inscripción a eventos y proceso de registro simplificado. |

---

## 🛠️ Stack Tecnológico (High-End)

El proyecto utiliza las tecnologías más vanguardistas para asegurar una UI/UX de nivel mundial:

### **Frontend Core**
*   **React 19:** El estándar más reciente para interfaces reactivas.
*   **Vite:** Herramienta de construcción ultra-rápida para una experiencia de desarrollo fluida.
*   **Tailwind CSS 4:** Diseño basado en utilidades con una estética "Street & Urban".

### **Interactividad y Visuals**
*   **Framer Motion:** Animaciones fluidas que dan vida a cada scroll y click.
*   **Lucide React:** Iconografía vectorial limpia y moderna.
*   **Recharts:** Visualización de métricas de rendimiento y ventas.
*   **Canvas Confetti:** Feedback visual positivo ante logros y compras.

### **Infraestructura y Despliegue**
*   **Docker:** Containerización completa para portabilidad absoluta.
*   **Nginx:** Configuración de servidor de alto rendimiento para el manejo de tráfico y seguridad.
*   **Axios:** Consumo de servicios API con manejo avanzado de errores.

---

## 📂 Estructura del Proyecto

```text
src/
├── feactures/           # Módulos principales (Landing, Dashboards, Auth)
│   ├── landing/         # Experiencia pública y tienda
│   ├── dashboards/      # Paneles privados por rol (Student, Instructor)
│   └── Auth/            # Gestión de acceso y seguridad
├── context/             # Estados globales (Autenticación, Carrito)
├── services/            # Lógica de comunicación con el Backend
├── hooks/               # Hooks personalizados para lógica reutilizable
└── utils/               # Helpers de validación, fechas y formateo
```

---

## ⚙️ Guía de Inicio Rápido

### Instalación Manual
1.  **Clonar el repositorio:** `git clone https://github.com/...`
2.  **Instalar dependencias:**
    ```bash
    npm install
    ```
3.  **Configurar Variables de Entorno:** Crear un archivo `.env` basado en `.env.example`.
4.  **Ejecutar en Desarrollo:**
    ```bash
    npm run dev
    ```

### Despliegue con Docker
```bash
docker-compose up --build
```

---

## 🛡️ Licencia y Propiedad

Este software es propiedad intelectual exclusiva de **Performance SB**. Queda estrictamente prohibida su reproducción total o parcial sin autorización.

**Equipo de Desarrollo:**
*   **Sebastián Vásquez Echavarria**
*   **Emanuel González Jaramillo**
*   **Mariana Granda**
*   **Manuela Granda**

---
*© 2026 Performance SB — Urban Talent & Tech Division.*
