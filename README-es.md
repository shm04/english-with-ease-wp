# EWE Academy — Landing Page de Alta Conversión y Motor de Diagnóstico

> **Categoría:** Desarrollo Frontend / Generación de Leads  
> **Cliente:** EWE Academy  
> **Desarrollador:** Sebastian Hernandez ([Elevate Agency](https://your-elevate-link.com))  

---

## 🌎 Idiomas
Leer en [Inglés](./README.md)

---

# 📗 Tabla de Contenidos
- [📖 Acerca del Proyecto](#acerca-del-proyecto)
- [🎯 Objetivo de Negocio y Conversiones](#objetivo-negocio)
- [✨ UI/UX y Diseño](#ui-ux-diseno)
- [💻 Stack Tecnológico](#stack-tecnologico)
- [📈 Métricas de SEO y Rendimiento](#seo-rendimiento)
- [🔗 Flujo de Captura de Leads](#captura-leads)
- [👥 Autores](#autores)
- [📝 Licencia](#licencia)

---

## 📖 Acerca del Proyecto <a name="acerca-del-proyecto"></a>
La Landing Page de EWE Academy no es un sitio web estático tradicional; es un **embudo de conversión (funnel) enfocado en el rendimiento**. Diseñado para capturar prospectos altamente calificados para una academia de inglés premium, el sitio guía a los usuarios a través de una interfaz moderna y atractiva que destaca la metodología única de la institución.

**Enlaces Clave:**
* [Live Demo / Sitio Web](#) 
* [Mockups de Diseño / Figma](#)

<p align="right">(<a href="#readme-top">volver arriba</a>)</p>

## 🎯 Objetivo de Negocio y Conversiones <a name="objetivo-negocio"></a>
El objetivo principal de este proyecto es la **Calificación de Leads de Alta Fidelidad**. 

En lugar de un formulario genérico de "Contáctanos", el sitio emplea un embudo estratégico:
1. **Conversión Principal:** Dirigir a los usuarios a completar el **"Diagnóstico Express"**, una prueba de nivel interactiva de 10 minutos.
2. **Conversión Secundaria:** Una vez finalizada, los prospectos calificados son redirigidos a una sesión de "Feedback Estratégico" a través de la **API de WhatsApp**, armando al equipo de ventas con el nivel exacto de inglés del prospecto antes de que comience la conversación.

<p align="right">(<a href="#readme-top">volver arriba</a>)</p>

## ✨ UI/UX y Características de Diseño <a name="ui-ux-diseno"></a>
El lenguaje de diseño refleja una estética de "Academia Premium", equilibrando el profesionalismo con la accesibilidad.

* **Fluidez Mobile-First:** Garantiza una experiencia perfecta en todos los dispositivos, crucial para la generación de leads B2C.
* **Divulgación Progresiva:** Conceptos complejos como el "Modelo F-U-F" (Función-Uso-Forma) se explican utilizando ecosistemas de tarjetas interactivas para evitar la sobrecarga cognitiva.
* **Micro-Interacciones:** Estados hover suaves, efectos de glassmorphism y transiciones de entrada atractivas mantienen a los usuarios enfocados, especialmente durante la prueba de diagnóstico.
* **Identidad de Marca:** Implementación personalizada del *Azul EWE (#004aad)* y el *Rosa EWE (#ff3131)* utilizando el motor JIT de Tailwind.

<p align="right">(<a href="#readme-top">volver arriba</a>)</p>

## 💻 Stack Tecnológico <a name="stack-tecnologico"></a>
Construido para velocidad y escalabilidad utilizando una arquitectura React moderna.

* **Framework:** React 19 + Vite 7 (para tiempos de compilación y HMR ultra rápidos).
* **Estilos:** Tailwind CSS v4.
* **Enrutamiento y Code Splitting:** React Router DOM v7.
* **Gestión de SEO:** React Helmet Async.
* **Componentes UI:** Sonner (Notificaciones Toast) y Lucide React (Iconografía).

<p align="right">(<a href="#readme-top">volver arriba</a>)</p>

## 📈 Métricas de SEO y Rendimiento <a name="seo-rendimiento"></a>
Diseñado para dominar las métricas de Core Web Vitals y el posicionamiento en buscadores para reducir el Costo de Adquisición de Clientes (CAC).

**Métricas de Lighthouse:**
* 🟢 **Rendimiento:** 94+ (Minimización de JS no utilizado vía `React.lazy` y code-splitting estricto).
* 🟢 **Accesibilidad:** 100 (Paletas de alto contraste, etiquetas ARIA, HTML5 semántico).
* 🟢 **Mejores Prácticas:** 100.
* 🟢 **SEO:** 100.

**Optimizaciones Clave:**
* Formatos de imagen de próxima generación (WebP) con `fetchpriority="high"` para las secciones Hero para minimizar el LCP (Largest Contentful Paint).
* Etiquetas Open Graph dinámicas y meta descripciones para rutas distintas (Inicio, Metodología, Blog).

<p align="right">(<a href="#readme-top">volver arriba</a>)</p>

## 🔗 El Flujo de Captura de Leads (Integración) <a name="captura-leads"></a>
* **Motor de Evaluación Personalizado:** Una prueba multipaso patentada que calcula con precisión los niveles de los usuarios según el marco del MCER.
* **Persistencia Full-Stack:** Se conecta a un backend Node.js/Express para almacenar de forma segura los datos de los leads y los resultados granulares de las pruebas en PostgreSQL.
* **Puente CRM con WhatsApp:** Genera automáticamente un payload de mensaje de WhatsApp personalizado que contiene el nombre del usuario y el resultado del diagnóstico, reduciendo drásticamente la fricción para el equipo de ventas.

<p align="right">(<a href="#readme-top">volver arriba</a>)</p>

## 👥 Autores <a name="autores"></a>

👤 **Sebastian Hernandez**
* **Rol:** Frontend Engineer / UI Developer
* **Agencia:** [Elevate Agency](https://your-elevate-link.com)
* **LinkedIn:** [Sebastian Hernandez](https://www.linkedin.com/in/your-profile)
* **GitHub:** [@your-github](https://github.com/your-github)

<p align="right">(<a href="#readme-top">volver arriba</a>)</p>

## 📝 Licencia <a name="licencia"></a>
El diseño y la lógica personalizada de este proyecto son de **Propiedad Privada**. Todos los derechos reservados por Elevate Agency y EWE Academy.

<p align="right">(<a href="#readme-top">volver arriba</a>)</p>
