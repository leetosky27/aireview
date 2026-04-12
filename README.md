# aireview

## Proyecto de Ciencia de Datos - Universidad Uniminuto

**AIReview** es un gestor inteligente de reseñas de aerolíneas, vuelos y viajes enfocado en el contexto colombiano. Este proyecto ha sido desarrollado como parte del programa de Ciencia de Datos de la **Universidad Uniminuto**, con el objetivo de recolectar, procesar y analizar la experiencia del usuario en el sector aeronáutico mediante herramientas interactivas y análisis asistido por Inteligencia Artificial.

## 🚀 Propósito del Proyecto

El sistema permite capturar datos cualitativos y cuantitativos de viajeros para generar una base de conocimientos sobre la calidad del servicio en aerolíneas nacionales (como Avianca, Wingo, LATAM Colombia, entre otras). La aplicación busca optimizar la obtención de información y ofrecer respuestas precisas a través de un motor de análisis de datos.

## 🛠️ Funcionalidades Principales

### 1. Registro y Gestión de Datos de Usuario
*   **Autenticación Completa:** Módulos de Inicio de Sesión (`login.html`), Registro de nuevos usuarios (`register.html`) y Recuperación de cuenta (`reset.html`).
*   **Perfil Personalizado:** Espacio dedicado (`profile.html`) donde el cliente puede gestionar su información personal, incluyendo:
    *   Foto de perfil.
    *   Identificación (Cédula/ID).
    *   Nacionalidad y país de residencia.
    *   Teléfono de contacto.

### 2. Sistema de Reseñas Interactivo
*   **Captura de Datos:** Formulario estructurado para registrar el nombre de la aerolínea, título de la experiencia, fecha del vuelo y comentarios detallados.
*   **Medición Cuantitativa:** Sistema de calificación mediante estrellas (1-5) para medir la satisfacción del cliente de forma visual.
*   **Modo Anónimo:** Opción para proteger la identidad del usuario durante la publicación.
*   **Gestión de Datos:** Capacidad para filtrar por aerolínea, ordenar por relevancia/fecha y persistencia de datos mediante `localStorage`.

### 3. AirAssistant IA (Módulo de Inteligencia Artificial)
El núcleo del proyecto integra una interfaz de **Inteligencia Artificial** diseñada para interactuar con la información almacenada:
*   **Análisis Predictivo y Descriptivo:** El usuario puede realizar consultas en lenguaje natural sobre las reseñas (ej. "¿Cuál es la aerolínea con mejor servicio?").
*   **Procesamiento de Información:** La IA analiza el volumen de datos registrados, promedia calificaciones y extrae sentimientos de los comentarios para ofrecer respuestas concretas, claras y basadas en evidencia real.

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
