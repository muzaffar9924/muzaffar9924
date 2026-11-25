<div align="center">

# Hi, I'm Muzaffar Hussain 👋

### Senior PHP/Laravel Developer · Next.js & TypeScript · MS in Project Management

📍 Islamabad, Pakistan 🇵🇰

</div>

---

## 👨‍💻 About Me

I'm a **Senior PHP/Laravel Developer with ~5 years of experience** building web platforms, portals, payment integrations, and APIs. I work across the full stack with **Laravel, Vue 3 + Inertia.js, Next.js, and TypeScript**, and I have a particular niche in **payment gateway integrations** (CyberSource, WooCommerce, Magento).

I also hold an **MS in Project Management** from Bahria University, Islamabad, so I don't just write code. I plan, scope, and deliver it, and I understand how projects succeed or fail.

- 🔭 Building multi-role portals, registration systems, and payment plugins
- 🎓 Researched how AI adoption affects project success (MS thesis)
- ☁️ Working toward AWS certification
- 🌍 Open to senior developer and technical project roles, locally and internationally

---

## 🧰 Tech Stack

**Backend**

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![REST API](https://img.shields.io/badge/REST_APIs-009688?style=for-the-badge&logo=fastapi&logoColor=white)

**Frontend**

![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![Inertia.js](https://img.shields.io/badge/Inertia.js-9553E9?style=for-the-badge&logo=inertia&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

**CMS & E-commerce**

![WordPress](https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white)
![WooCommerce](https://img.shields.io/badge/WooCommerce-96588A?style=for-the-badge&logo=woocommerce&logoColor=white)
![Magento](https://img.shields.io/badge/Magento_2-EE672F?style=for-the-badge&logo=magento&logoColor=white)

**Payments & Integrations**

CyberSource (Recurring Billing, Microform v2, Secure Acceptance, TMS) · Meta WhatsApp Cloud API · Groq AI · Pusher

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)

---

## 🚀 Featured Projects

### 💳 CyberSource Recurring Billing Plugin (WordPress / WooCommerce)
A WordPress plugin that integrates the **CyberSource Recurring Billing REST API** as a subscriptions payment gateway.
- Built on the official `cybersource/rest-client-php` SDK with HTTP Signature authentication
- Card capture through **CyberSource Microform** on both classic and block-based WooCommerce checkout (no raw card data touches the server)
- Customer tokenization, plan and subscription creation, and scheduled renewal reconciliation that creates a linked order for every billing cycle
- Removed the dependency on the paid WooCommerce Subscriptions plugin by tracking subscription state through order meta
- Admin tools to cancel, suspend, and reactivate subscriptions, plus a customer-facing **My Account → Subscriptions** page
- Compatible with WooCommerce HPOS and the Checkout Block
- **Stack:** PHP, WordPress, WooCommerce, CyberSource REST API

### 🏦 AlliedBank Installment Billing (WooCommerce plugin)
A modular WooCommerce plugin for **CyberSource-based installment plans** (for example "Pay in 3 installments").
- Admin-managed installment plans (create, edit, deactivate) synced to CyberSource's Plans API
- Product-level installment options with installment amount shown on the product page
- Subscriptions admin page with CyberSource-backed cancellation and full API logging
- Test/Live environment toggle with automatic API URL selection
- Built in phases: admin and plan management first, checkout payment second
- **Stack:** PHP, WooCommerce, CyberSource APIs

### 🛒 Allied Bank Payment Gateway for Magento 2.4.8
A complete payment extension for **Magento 2.4.8**, integrating **CyberSource Secure Acceptance and Microform v2**.
- Fixed guest-checkout cart errors, security validation gaps, and Microform v2 capture-context issues
- Prepared for **Adobe Commerce Marketplace (EQP)** submission
- **Stack:** PHP, Magento 2, CyberSource

### 🕌 UMABC Community Portal
A multi-role community portal for a Muslim community organization in British Columbia.
- Two-level role system (portal-level and association-level) using a pivot table, with custom middleware and routing
- News & Events management and a Prayer Hours module
- Association listings with server-side pagination and filtering
- Inline-editable home page and footer, user profiles with cascading country/state/city dropdowns, and a Super Admin dashboard
- Reusable Vue modal patterns for Add / Edit / View / Delete
- **Stack:** Laravel 12, Vue 3, Inertia.js, Vite, Bootstrap 5

### 🎟️ SHIQR Visitor Registration System
A visitor registration platform built for the **Reenergia Impact** event.
- QR code generation for each visitor, with email delivery
- REST API for an iOS app
- Admin dashboard for managing registrations
- **Stack:** Laravel 12, Vue 3, Inertia.js

### 🔍 AI-Powered Product Search for a Multi-Vendor Store
Natural-language product search for a store with ~15,000 products.
- Customers can search naturally, for example *"earbuds with a range 1k to 5k"* or *"leather shoes size 7"*, with price and size filters understood from the query
- Designed around a free, open-source AI model
- **Stack:** Laravel, Blade, jQuery, AI/NLP

### ⬆️ Laravel 8 → Laravel 12 Upgrade
Modernized a production Laravel 8 application to **Laravel 12** using a fresh skeleton.
- Migrated custom middleware (timezone, XSS protection, seller checks, maintenance and demo modes) from the old Kernel into `bootstrap/app.php`
- Ported admin routes, authentication, and package dependencies

### 📲 WooCommerce WhatsApp & Email Location Collector
A WooCommerce plugin that automatically collects customer delivery locations.
- Uses the **Meta WhatsApp Cloud API** plus email
- **Groq AI** parses free-text customer replies into structured location data

### 🎨 Chaudhry Flour Mills Website
Converted a static HTML site into a full **WordPress theme** with Customizer integration, so the client can edit content without touching code.

---

## 🎓 Research

**MS Thesis (Bahria University Islamabad, 2026):**
*The Impact of AI Capability, AI Integration, and Organizational Readiness on Project Success: The Mediating Role of Scope Creep Control*

- Built and tested a seven-hypothesis **PLS-SEM** model targeting Agile IT practitioners in Pakistan's telecom and fintech sectors
- Collected **303 usable survey responses** and analyzed them in **SmartPLS 4**
- All seven hypotheses were supported, and the model explained about 59% of the variance in scope creep control and about 50% of the variance in project success

---

## 💼 Experience

| Company | Role |
|---|---|
| **AXABIZTECH** | Software Developer |
| **AKSA-SDS** | Software Developer |
| **SixSole Technology** | Software Developer |
| **Freelance (Upwork)** | Laravel / Vue / WordPress / payment integrations |

*Total: ~5 years in PHP/Laravel development.*

---

## 🎓 Education

- **MS in Project Management**, Bahria University, Islamabad
- Currently pursuing **AWS certification**

---

## 🤝 What I Can Help With

- Custom Laravel + Vue 3 / Inertia web applications
- Payment gateway integrations (CyberSource, WooCommerce, Magento)
- WordPress and WooCommerce plugin development
- Laravel version upgrades and refactoring
- REST APIs for mobile apps
- Technical project planning and delivery

---

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muzaffar-hussain-work)
[![Upwork](https://img.shields.io/badge/Upwork-6FDA44?style=for-the-badge&logo=upwork&logoColor=white)](https://www.upwork.com/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your-email@example.com)

---

<div align="center">

⭐ Open to senior developer and technical project roles. Let's build something great together.

</div>
