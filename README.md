# 🌊 Ocean Watch - Marine Conservation Platform

> **⚠️ Note:** This repository serves as a portfolio showcase. Due to university academic integrity policies, the full source code is not publicly available. This README documents my individual contributions, technical decisions, and UI implementations.

## 📖 Project Overview
**Ocean Watch** is a React-based Single Page Application (SPA) designed to educate communities about marine pollution and endangered species. The platform bridges the gap between scientific data and local activists by visualizing species locations and allowing users to report sightings.

* **Role:** Front-End Developer & Product Owner (Sprint 1)
* **Focus:** Interactive Mapping, AI prototyping, Core Architecture, and Team Integration.
* **Tech Stack:** React, Vite, Leaflet.js, CSS Modules, Git/GitHub.

---

## 🚀 Key Features Implemented

### 1. Interactive Global Map
I designed and built the core visualization tool for the platform, replacing static text with an interactive experience.
* **Tech Used:** `react-leaflet`, Custom JSON Data.
* **Implementation:**
    * Integrated **OpenStreetMap** tiles via Leaflet for a lightweight, cost-effective solution.
    * Developed a custom data layer (`mock-educational-pins.json`) to render dynamic markers for 20+ endangered species.
    * Implemented interactive popups displaying species status (e.g., "Critically Endangered") upon user interaction.

![Interactive Map Screenshot](./screenshots/map-feature.png)
*(Screenshot of the Map interface showing markers)*

### 2. AI Photo Identifier (Prototype)
I developed a "Citizen Science" tool allowing users to upload sightings of marine life.
* **Tech Used:** React Hooks (`useState`), `URL.createObjectURL`.
* **Implementation:**
    * Built a file upload handler that generates instant client-side previews without needing a backend upload first.
    * Implemented "Mock AI" logic to simulate successful species identification for demonstration purposes ("Blue Whale" result).
    * Designed the UI to provide immediate visual feedback to keep users engaged.

![Photo Identifier Screenshot](./screenshots/photo-feature.png)
*(Screenshot of the Photo Upload tool)*

### 3. Architecture & Navigation
I was responsible for the initial repository setup and the application's core routing structure.
* **Tech Used
