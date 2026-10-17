# Furniture & Arts - Interactive Design Portfolio 
<img width="1855" height="872" alt="Screenshot 2026-10-17 200928" src="https://github.com/user-attachments/assets/fb515b2c-4ad3-45fa-935c-820730a94c72" />


A hybrid web project that bridges the gap between interior design theory and interactive 3D web technology. This project serves as a comprehensive portfolio piece, featuring curated mood boards, color theory explanations, and a fully functional, custom-coded 3D furniture configurator.

 **Live Experience (Main Site):** https://furniture-and-arts.webflow.io/
 **3D Configurator Engine:** https://configurator-briana.netlify.app/

## Project Structure

### 1. UI/UX & Design Showcase (Webflow)
The landing experience is visually driven, focusing on aesthetics and design principles:
* **Color Theory & Mood Boards:** Curated sections explaining the foundational dialogue between textures, colors, and light in interior spaces.
* **Responsive UI:** A clean, modern layout built visually to guide the user naturally toward the interactive 3D catalog.

### 2. 3D Interactive Configurator (Vanilla JS & HTML/CSS)
Accessible directly from the main site, the configurator is a custom-coded web application hosted separately, allowing users to customize products in real-time:
* **Real-Time 3D Rendering:** Uses Google's `<model-viewer>` component for highly performant `.glb` rendering and Augmented Reality (AR) support.
* **Dynamic Texture Swapping:** Users can apply dozens of different textures (wood, metal, fabrics) to specific material nodes using asynchronous JavaScript (`createTexture()`).
* **Interactive UI Controls:** Custom-built nested menus and a dynamic "zoom bubble" for inspecting high-resolution material details.
* **Environment Lighting:** Toggle between Neutral, Warm, and Cool lighting setups by adjusting exposure and shadow intensity on the fly.

## 🛠️ Technologies Used
* **Web Design & Hosting:** Webflow (UI/UX)
* **Configurator Logic:** HTML5, CSS3, Vanilla JavaScript (ES6)
* **3D Library:** `<model-viewer>` (Web Components)
* **3D Asset Creation:** Blender (Custom 3D modeling, precision UV unwrapping/mapping, and optimized `.glb` export).
* **Configurator Hosting:** Netlify
