# aireview

## Proyecto de Ciencia de Datos - Universidad Uniminuto

**AIReview** es un gestor inteligente de reseñas de aerolíneas, vuelos y viajes enfocado en el contexto colombiano. Este proyecto ha sido desarrollado como parte del programa de Ciencia de Datos de la **Universidad Uniminuto**, con el objetivo de recolectar, procesar y analizar la experiencia del usuario en el sector aeronáutico mediante herramientas interactivas y análisis asistido por Inteligencia Artificial.

## 🚀 Propósito del Proyecto

El sistema permite capturar datos cualitativos y cuantitativos de viajeros para generar una base de conocimientos sobre la calidad del servicio en aerolíneas nacionales (como Avianca, Wingo, LATAM Colombia, entre otras). La aplicación busca optimizar la obtención de información y ofrecer respuestas precisas a través de un motor de análisis de datos.

## 🛠️ Módulos del Sistema

El sistema se compone de cinco módulos integrados que permiten el flujo completo de la información:

### 1. Módulo de Seguridad y Acceso
*   **Gestión de Sesiones:** Control de entrada mediante `login.html`.
*   **Registro de Analistas:** Captura de nuevos usuarios a través de `register.html`.
*   **Soporte de Cuenta:** Recuperación de credenciales mediante el flujo de `reset.html`.

### 2. Módulo de Gestión de Usuario (Perfil)
*   **Identidad Digital:** Administración de información personal en `profile.html`, incluyendo carga de fotografía de perfil, datos demográficos (nacionalidad/residencia) e identificación oficial.

### 3. Módulo de Recolección de Datos (Feedback Loop)
*   **Captura de Experiencia:** Formulario robusto en `index.html` para datos cualitativos (comentarios) y cuantitativos (estrellas).
*   **Atributos de Viaje:** Registro detallado de aerolínea, fecha de vuelo y títulos descriptivos.
*   **Privacidad del Usuario:** Opción de "Modo Anónimo" para publicaciones protegidas.

### 4. Módulo de Análisis Inteligente (AirAssistant IA)
*   **Motor de Consultas:** Interfaz de IA que procesa lenguaje natural para interrogar la base de datos de reseñas.
*   **Análisis de Sentimientos y Tendencias:** Capacidad para identificar la aerolínea con mejor desempeño, resumir críticas negativas y promediar niveles de satisfacción en tiempo real.

### 5. Módulo de Administración (Panel de Control)
*   **Monitoreo Global:** Panel centralizado en `admin.html` para visualizar métricas clave como el total de reseñas y el promedio de calificación de la plataforma.
*   **Moderación de Contenido:** Capacidad del administrador para supervisar y eliminar reseñas para mantener la integridad de la información.
*   **Gestión de Usuarios:** Control y supervisión de las cuentas de analistas registradas en el sistema.

### 6. Módulo de Persistencia y Visualización Dinámica
*   **Motor de Búsqueda:** Sistema de filtrado en tiempo real por palabras clave y aerolíneas.
*   **Gestión de Base de Datos:** Persistencia mediante la API de `localStorage` y lógica de ordenamiento (por fecha o calificación).
*   **Interfaz de Usuario (UI):** Visualización basada en componentes dinámicos con estados de carga y retroalimentación visual (Toasts).

## 🎨 Diseño y Experiencia de Usuario (UX/UI)

La interfaz ha sido diseñada bajo un concepto **Aeronáutico/Minimalista** que incluye:
*   **Dark Mode Nativo:** Una paleta de colores azul profundo y cian que mejora la legibilidad y reduce la fatiga visual.
*   **Glassmorphism:** Efectos de desenfoque y transparencia en las tarjetas de datos para una estética moderna.
*   **Elementos Temáticos:** Uso de nubes minimalistas animadas por CSS y una iconografía centrada en viajes y aviación para reforzar la identidad del sitio.

## 📂 Estructura del Proyecto

*   `index.html`: Panel principal de gestión de reseñas y asistente de IA.
*   `login.html`: Interfaz de acceso al ecosistema.
*   `register.html`: Formulario de captura de nuevos analistas/usuarios.
*   `reset.html`: Sistema de recuperación de credenciales.
*   `admin.html`: Panel de control para la gestión de métricas y moderación.
*   `profile.html`: Centro de gestión de perfil y datos demográficos del cliente.

## 🧪 Tecnologías Utilizadas

*   **Frontend:** HTML5, CSS3 (Custom Variables, Flexbox, Grid, Animations).
*   **Lógica de Datos:** JavaScript Vanilla (ES6+).
*   **Almacenamiento:** LocalStorage API para la persistencia de la base de datos de reseñas.
*   **Simulación de IA:** Algoritmos de filtrado y procesamiento de lenguaje para la interacción del asistente.

---
*Este proyecto representa un esfuerzo por unir la recolección de datos masivos con la interpretación inteligente en el sector del transporte aéreo colombiano.*

## 👥 Créditos e Información Académica

**Elaborado por:**
1. **Martin Lee**
2. **Nicolas Zarate**

**Institución:** Corporación Universitaria Minuto de Dios  
**Docente:** Hector Ladino  
**Año:** 2026  
**Curso:** Introducción a la Ciencia de Datos e Inteligencia Artificial
