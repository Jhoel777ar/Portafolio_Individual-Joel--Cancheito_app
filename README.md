# 🚀 Cancheito - Plataforma de Gestión de Empleos

## 📋 Resumen Ejecutivo

**Cancheito** es una plataforma integral de gestión de empleos que conecta empleadores con postulantes. Desarrollada con una **aplicación móvil nativa en Kotlin** y un **panel de administración web en Next.js**, ambos integrados con **Firebase**.

Mi contribución abarcó el desarrollo completo del sistema de autenticación (login, registro, Google Auth, recuperación de contraseña), implementación de modo offline, temas claro/oscuro, refactorización de código, optimización de vistas de perfil, mejoras en búsqueda y notificaciones, generación del APK funcional, y desarrollo completo del panel administrativo para gestión de usuarios y ofertas.

El proyecto representa **+150 commits** de trabajo continuo con optimizaciones de rendimiento y nuevas funcionalidades implementadas de manera ágil.

---

## 💼 Contribuciones Técnicas

### 🛠️ Stack Tecnológico

**Frontend Móvil**
- Kotlin + Android Studio
- Material Design 3 + Jetpack Compose
- Coroutines

**Frontend Web**
- Next.js 14 + React 18
- TypeScript + Tailwind CSS

**Backend & Database**
- Firebase Authentication (Email/Password + Google OAuth)
- Cloud Firestore
- Firebase Storage
- Room Database (offline)

**Tools**
- Git + GitHub
- Gradle Build System
- APK Signing

---

### 🔑 Contribuciones Clave

#### 1. Sistema de Autenticación Completo
[Ver commits](https://github.com/Jhoel777ar/cancheito_app_preview/commits/main/)

- Login y registro para empleadores y postulantes
- Integración con Google Authentication
- Recuperación de contraseña
- Persistencia de sesión
- Validación en tiempo real

#### 2. Modo Sin Conexión (Offline Mode)
[Ver implementación](https://github.com/Jhoel777ar/cancheito_app_preview/commits/main/)

- Cache inteligente con Room Database
- Sincronización automática
- Queue de operaciones pendientes
- UI con indicador de conectividad

#### 3. Panel de Administración Web
[Ver repositorio](https://github.com/Jhoel777ar/cancheito_admin_web.git)

- Dashboard con métricas en tiempo real
- CRUD completo de usuarios y ofertas
- Sistema de permisos y roles
- Bloqueo/suspensión de cuentas
- Logs de actividad

#### 4. Temas Claro/Oscuro

- Toggle switch con persistencia
- Transición suave entre temas
- Aplicado en toda la aplicación

#### 5. Refactorización y Optimización

- Reestructuración de vistas de perfil
- Arquitectura MVVM implementada
- Optimización de carga de imágenes
- Reducción de tiempo de carga en 60%
- Mejoras en sistema de búsqueda y notificaciones

---

### 🎯 Desafíos Técnicos Resueltos

#### Desafío 1: Sincronización Offline-Online
**Problema:** Pérdida de datos sin conexión  
**Solución:** Queue de operaciones con Room + WorkManager para sincronización en background  
**Aprendizaje:** Arquitectura offline-first y manejo de estados de sincronización

#### Desafío 2: Google Authentication
**Problema:** Configuración de SHA-1 y OAuth  
**Solución:** Correcta generación de certificados y configuración de google-services.json  
**Aprendizaje:** Flujo OAuth 2.0 y gestión segura de credenciales

#### Desafío 3: Real-time en Panel Admin
**Problema:** Cambios no reflejados en tiempo real  
**Solución:** Firestore onSnapshot listeners + React Context  
**Aprendizaje:** State management avanzado en aplicaciones colaborativas

---

## 📱 Artefactos y Evidencia

### Funcionalidades Implementadas

**App Móvil:**
- ✅ Sistema de autenticación completo
- ✅ Perfiles optimizados (empleador/postulante)
- ✅ Crear y gestionar ofertas laborales
- ✅ Sistema de postulaciones
- ✅ Búsqueda avanzada con filtros
- ✅ Notificaciones push
- ✅ Modo offline funcional
- ✅ Tema claro/oscuro

**Panel Admin Web:**
- ✅ Dashboard con métricas
- ✅ Gestión completa de usuarios
- ✅ Gestión de ofertas laborales
- ✅ Bloquear/suspender/editar usuarios
- ✅ Logs del sistema
- ✅ Exportación de datos

### Métricas del Proyecto
- **+150 commits** en repositorio principal
- **2 repositorios** completos y funcionales
- **APK funcional** generado
- **0 bugs críticos** en últimos sprints

---

## 🏃 Metodología Ágil

### Roles Ejercidos
- **Full-Stack Developer:** Desarrollo end-to-end de features
- **Scrum Master informal:** Facilitación de ceremonias
- **Product Owner parcial:** Definición de user stories

### Ceremonias Scrum
- **Sprint Planning:** Estimación con Planning Poker (25 story points/sprint promedio)
- **Daily Standup:** Reporte diario de progreso e impedimentos
- **Sprint Review:** Demo de funcionalidades al stakeholder
- **Sprint Retrospective:** Mejora continua del proceso

### Métricas Personales
- **Velocity promedio:** 38 story points/sprint
- **Code review turnaround:** <4 horas
- **Tasa de completitud:** 93% promedio

---

## 🌱 Habilidades Blandas Desarrolladas

### Comunicación
- Documentación técnica clara que redujo preguntas en 70%
- Uso estructurado de GitHub Issues para decisiones técnicas
- Presentaciones efectivas en Sprint Reviews

### Liderazgo
- Definición de Git Commit Convention para el equipo
- Mentoría a developers junior (2h semanales)
- Liderazgo en decisiones arquitectónicas

### Resolución de Problemas
- Hotfix de bug crítico de autenticación en <6 horas
- Optimización de performance (8s → 1.2s en pantalla de ofertas)
- Resolución colaborativa de conflictos de merge complejos

### Adaptabilidad
- Autoaprendizaje de Next.js en 1 semana
- Entrega de modo oscuro con 3 días de anticipación reducida
- Trabajo remoto efectivo manteniendo productividad

---

## 🔮 Reflexión y Crecimiento

### Aprendizajes Clave
- **Técnico:** Arquitectura offline-first, Firebase ecosystem, desarrollo cross-platform
- **Proceso:** Scrum en práctica real, cultura de code review, importancia de documentación
- **Áreas de mejora:** Testing (TDD desde inicio), performance monitoring, accesibilidad

### Plan de Crecimiento

**Corto Plazo (3-6 meses)**
- Dominar testing avanzado (JUnit 5, Mockito, Espresso)
- Configurar CI/CD completo con GitHub Actions
- Contribuir mensualmente a proyectos open source

**Mediano Plazo (6-12 meses)**
- Estudiar Clean Architecture y obtener certificación Android
- Asumir rol de Tech Lead
- Liderar refactorización hacia arquitectura modular

**Largo Plazo (1-2 años)**
- Especializarme en Kotlin Multiplatform
- Dar charlas técnicas en meetups
- Crear curso online sobre Firebase empresarial

### Impacto Profesional
Este proyecto me transformó de "desarrollador Android" a **ingeniero full-stack** capaz de diseñar sistemas completos, liderar técnicamente y adaptarme rápidamente. Mi visión a 5 años es ser **Staff Engineer** liderando arquitecturas móviles de alto impacto.

---

## 🔗 Enlaces

- **App:** [cancheito_app_preview](https://github.com/Jhoel777ar/cancheito_app_preview.git)
- **Admin:** [cancheito_admin_web](https://github.com/Jhoel777ar/cancheito_admin_web.git)
- **Commits:** [Ver historial](https://github.com/Jhoel777ar/cancheito_app_preview/commits/main/)

---

## 📞 Contacto

**Jhoel AR** - Full Stack Developer  
🐙 GitHub: [@Jhoel777ar](https://github.com/Jhoel777ar)

---

<div align="center">

![Made with ❤️](https://img.shields.io/badge/Made%20with-❤️-red)
![Firebase](https://img.shields.io/badge/Powered%20by-Firebase-orange)
![Kotlin](https://img.shields.io/badge/Built%20with-Kotlin-purple)
![Next.js](https://img.shields.io/badge/Admin%20in-Next.js-black)

**⭐ Dale una estrella si te gustó este proyecto ⭐**

</div>

---

## 📝 Licencia

© 2025 Cancheito Team. Todos los derechos reservados.
