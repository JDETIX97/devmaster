# DevMaster – Proyecto de Formación en Angular + Ionic

Este repositorio contiene el proyecto base para el plan de estudio diario orientado al dominio avanzado de tecnologías modernas como **Angular**, **Ionic**, **Firebase** y **GitHub**. El objetivo es construir una aplicación robusta, modular y escalable aplicando buenas prácticas de desarrollo profesional.

---

## 📌 Objetivos del Proyecto

- Consolidar y perfeccionar habilidades en Angular e Ionic.
- Aplicar una arquitectura escalable y mantenible.
- Integrar servicios de Firebase: autenticación, Firestore, hosting, entre otros.
- Dominar Git y GitHub en un flujo de trabajo colaborativo.
- Publicar avances y entregables diarios como parte del plan de estudio.

---

## 🛠️ Tecnologías Iniciales

- [Angular CLI](https://angular.io/cli) – v20.0.6
- [Ionic Framework](https://ionicframework.com/) – v7.2.1
- [Firebase CLI](https://firebase.google.com/docs/cli)
- [Node.js](https://nodejs.org/) – v22.17.0
- [Git](https://git-scm.com/)
- Editor sugerido: [Visual Studio Code](https://code.visualstudio.com/)

---

## 🔧 Configuración del Entorno

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/JDETIX97/devmaster.git
   cd devmaster
   
2. Instalar dependecias:
   ```bash
   npm install -g @angular/cli
   npm install -g @ionic/cli
   npm install -g firebase-tools
   
3. Iniciar la aplicación:
   ```bash
   ionic serve
   
---

<img width="1908" height="986" alt="image" src="https://github.com/user-attachments/assets/ee0c0ece-48e8-44a4-828f-e9d691b7b38b" />

---

### ✅ Día 1 – Preparación del Entorno
- Instalación de herramientas: Angular CLI, Ionic CLI, Firebase CLI, Git.
- Creación del proyecto base con `ionic start`.
- Revisión de fundamentos Angular (componentes, servicios, enrutamiento).

### ✅ Día 2 – Arquitectura Escalable y Lazy Loading
- Reorganización del proyecto:
  - Estructura modular (`core`, `shared`, `features`).
  - Creación de módulos `auth` y `dashboard`.
- Implementación de lazy loading en `app-routing.module.ts`.
- Navegación funcional entre rutas.
- Aplicación lista para escalar módulos de forma organizada.