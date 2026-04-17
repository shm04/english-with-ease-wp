# EWE Academy — High-Conversion Landing Page & Diagnostic Engine

> **Category:** Frontend Development / Lead Generation  
> **Client:** EWE Academy  
> **Developer:** Sebastian Hernandez ([Elevate Agency](https://your-elevate-link.com))  

---

## 🌎 Languages
Read this in [Spanish](./README-es.md)

---

# 📗 Table of Contents
- [📖 About the Project](#about-project)
- [🎯 Business Goal & Conversions](#business-goal)
- [✨ UI/UX & Design Features](#ui-ux-design)
- [💻 Tech Stack](#tech-stack)
- [📈 SEO & Performance Metrics](#seo-performance)
- [🔗 The Lead Capture Flow](#lead-capture)
- [👥 Authors](#authors)
- [📝 License](#license)

---

## 📖 About the Project <a name="about-project"></a>
The EWE Academy Landing Page is not a traditional static website; it is a **performance-first conversion funnel**. Designed to capture highly qualified leads for a premium English academy, the site guides users through a modern, engaging interface that highlights the academy's unique methodology.

**Key Links:**
* [Live Demo / Website](https://eweacademy.com/) 

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🎯 Business Goal & Conversions <a name="business-goal"></a>
The primary objective of this project is **High-Fidelity Lead Qualification**. 

Instead of a generic "Contact Us" form, the site employs a strategic funnel:
1. **Primary Conversion:** Directing users to complete the **"Diagnóstico Express"**, an interactive 10-minute placement test.
2. **Secondary Conversion:** Upon completion, qualified prospects are routed to a "Strategic Feedback" session via the **WhatsApp API**, arming the sales team with the prospect's exact English level before the conversation even begins.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ✨ UI/UX & Design Features <a name="ui-ux-design"></a>
The design language reflects a "Premium Academy" aesthetic, balancing professionalism with approachability.

* **Mobile-First Fluidity:** Ensures a seamless experience across all devices, crucial for B2C lead generation.
* **Progressive Disclosure:** Complex concepts like the "F-U-F Model" (Function-Use-Form) are explained using interactive card ecosystems to prevent cognitive overload.
* **Micro-Interactions:** Smooth hover states, glassmorphism effects, and engaging entry transitions keep users focused, especially during the diagnostic test.
* **Brand Identity:** Custom implementation of *EWE Blue (#004aad)* and *EWE Pink (#ff3131)* using Tailwind's JIT engine.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 💻 Tech Stack <a name="tech-stack"></a>
Built for speed and scalability using a modern React architecture.

* **Framework:** React 19 + Vite 7 (for lightning-fast HMR and optimized builds).
* **Styling:** Tailwind CSS v4.
* **Routing & Code Splitting:** React Router DOM v7.
* **SEO Management:** React Helmet Async.
* **UI Components:** Sonner (Toast notifications) & Lucide React (Iconography).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📈 SEO & Performance Metrics <a name="seo-performance"></a>
Engineered to dominate Core Web Vitals and search rankings to reduce Customer Acquisition Cost (CAC).

**Lighthouse Benchmarks:**
* 🟢 **Performance:** 94+ (Minimized unused JS via `React.lazy` and strict code-splitting).
* 🟢 **Accessibility:** 100 (High-contrast palettes, ARIA labels, semantic HTML5).
* 🟢 **Best Practices:** 100.
* 🟢 **SEO:** 100.

**Key Optimizations:**
* Next-Gen image formats (WebP) with `fetchpriority="high"` for Hero sections to minimize Largest Contentful Paint (LCP).
* Dynamic Open Graph tags and meta descriptions for distinct routes (Home, Methodology, Blog).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🔗 The Lead Capture Flow (Integration) <a name="lead-capture"></a>
* **Custom Assessment Engine:** A proprietary multi-step test that accurately calculates user levels based on the CEFR framework.
* **Full-Stack Persistence:** Connects to a Node.js/Express backend to securely store lead data and granular test results in PostgreSQL.
* **CRM WhatsApp Bridge:** Automatically generates a personalized WhatsApp message payload containing the user's name and diagnostic result, drastically reducing friction for the sales team.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 👥 Authors <a name="authors"></a>

👤 **Sebastian Hernandez**
* **Role:** Frontend Engineer / UI Developer
* **Agency:** [Elevate Agency](https://your-elevate-link.com)
* **LinkedIn:** [Sebastian Hernandez](https://www.linkedin.com/in/sebastian-hernandez-munoz/)
* **GitHub:** [@your-github](https://github.com/shm04)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📝 License <a name="license"></a>
This project's design and custom logic are **Proprietary**—all rights reserved by Elevate Agency and EWE Academy.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
