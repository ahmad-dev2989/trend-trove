git clone https://github.com/your<div align="center">

# 🌟 TREND TROVE 🌟
**Wear The Trend. Define Your Style.**

[![Alpine.js](https://img.shields.io/badge/Alpine.js-8BC0D0?style=for-the-badge&logo=alpine.js&logoColor=white)](#)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](#)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](#)
[![Cloudflare Pages](https://img.shields.io/badge/Cloudflare_Pages-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)](#)
[![Grok AI](https://img.shields.io/badge/Grok_AI-000000?style=for-the-badge&logo=x&logoColor=white)](#)

*A premium, high-performance e-commerce platform built for the modern fashion landscape in Pakistan.*

</div>

---

## 📖 About The Project

**Trend Trove** is a comprehensive, full-stack e-commerce web application specializing in premium men's hoodies, oversized tracksuits, and custom apparel. Built from the ground up to provide a luxurious shopping experience, the platform merges high-end graphic design aesthetics with cutting-edge web technologies. 

From interactive 3D product viewing to a fully integrated AI customer support assistant, Trend Trove is designed to handle everything from browsing to dynamic custom order generation.

---

## ✨ Standout Features

*   🎨 **Glassmorphic UI & Advanced Animations:** A visually stunning interface featuring frosted glass modals, deeply saturated blur effects, and complex, buttery-smooth CSS animations (including a custom animated truck checkout button and liquid-fill page loaders).
*   👕 **Interactive Custom Apparel Builder:** A powerful drag-and-drop canvas allowing users to upload, scale, and position their own logos or artwork directly onto apparel mockups, complete with dynamic pricing based on print size (A4, A3, pocket, sleeve).
*   🤖 **Grok-Powered AI Assistant:** A 24/7 intelligent chat widget seamlessly integrated via Cloudflare Workers. The AI is context-aware, reading live inventory data to assist customers with exact stock levels and product details.
*   🧊 **3D Interactive Product Models:** Integration of Google's `<model-viewer>` for real-time, rotatable 3D viewing of oversized garments with dynamic lighting and shadow rendering.
*   👑 **Secure Admin Dashboard:** A hidden, authenticated control center where administrators can manage products, track inventory states (low stock/out of stock), apply global sales, and handle categories.
*   📄 **Automated Invoicing & Emailing:** Real-time PDF receipt generation via `jsPDF` and automated order confirmation emails routed securely through `EmailJS`.

---

## 🛠️ Technology Stack

### **Frontend Architecture**
*   **HTML5 & CSS3:** Semantic structure with heavy emphasis on custom keyframe animations.
*   **Tailwind CSS:** Rapid, utility-first styling ensuring a fully responsive mobile-first design.
*   **Alpine.js:** Lightweight reactive framework managing the complex UI states, modal toggling, and real-time cart calculations without the overhead of React/Vue.
*   **Three.js / Model-Viewer:** Rendering high-fidelity `.glb` 3D apparel models.

### **Backend & BaaS (Backend-as-a-Service)**
*   **Firebase Authentication:** Secure email/password and Google OAuth login for users and admins.
*   **Firebase Firestore:** NoSQL database storing user profiles, complex product schemas, dynamic categories, and order history.
*   **Firebase Storage:** Secure cloud storage for user-uploaded custom design assets.

### **Serverless Functions & APIs**
*   **Cloudflare Pages & Workers:** Edge-network hosting with serverless `functions/api/chat.js` acting as a secure proxy to communicate with the **xAI (Grok)** API.
*   **ImgBB API:** Rapid, transient image hosting for custom review uploads.

---

## 🚀 Installation & Local Setup

To run this project locally and explore the architecture:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/trend-trove.git](https://github.com/your-username/trend-trove.git)
   cd trend-trove
