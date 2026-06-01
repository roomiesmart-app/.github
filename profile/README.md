# 🏠 Bienvenido a RoomieSmart

**Plataforma inteligente para la gestión de convivencia y gastos compartidos.**

RoomieSmart es una solución web diseñada para simplificar la vida de quienes comparten vivienda. Nuestro sistema facilita la búsqueda de compañeros de piso compatibles y centraliza la administración de presupuestos, pagos y responsabilidades del hogar en un solo lugar.

---

## 🚀 Arquitectura y Tecnología

Nuestra infraestructura está diseñada bajo un enfoque **Cloud-Native**, garantizando alta disponibilidad, aislamiento de entornos y automatización total del ciclo de vida del software mediante integración y despliegue continuo (CI/CD).

### 💻 Stack de Desarrollo
- **Frontend:** React + Vite (TypeScript)
- **Backend:** Node.js (REST API)
- **Base de Datos:** PostgreSQL (Gestionada vía Supabase)

### ⚙️ DevOps & Cloud Infrastructure
- **Orquestación:** Docker & Docker Compose (Multi-stage builds)
- **CI/CD:** GitHub Actions (Zero-touch deployment)
- **Servidor:** AWS EC2 (Ubuntu Linux + Elastic IP estática)
- **Red y Seguridad:** Nginx Reverse Proxy (Aislamiento de entornos Dev/Prod en puertos 8080 y 80)

---

## 👥 Nuestro Equipo de Ingeniería

El desarrollo y despliegue de RoomieSmart es posible gracias al trabajo colaborativo de nuestro equipo:

* **Esteban Larrea** - Software Engineer
* **Kevin Tenorio** - Software Engineer
* **Jonathan Plaza** - Software Engineer
* **Luis Luna** - Software Engineer
* **Ricardo Chapi** - Cloud / DevOps Engineer

---

## 📌 Repositorios Principales

* 🌐 [roomiesmart-frontend](https://github.com/TU_ORGANIZACION/roomiesmart-frontend): Interfaz de usuario web optimizada y responsive.
* ⚙️ [roomiesmart-backend](https://github.com/TU_ORGANIZACION/roomiesmart-backend): Lógica de negocio, autenticación y conexión segura a Supabase.

> **Nota:** Todos los despliegues de la rama `main` y `dev` están automatizados y enlazados directamente con nuestra gestión de tareas en **Jira** para mantener una trazabilidad completa del proyecto.