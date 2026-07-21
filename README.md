# QMDJ & Da Liu Ren Professional Calculator 🧭

A high-precision, mobile-ready, client-side calculator for Qi Men Dun Jia (奇门遁甲) and Da Liu Ren (大六壬). 

Built specifically for professional divination and AI-assisted analysis, this engine strictly adheres to traditional algorithmic standards while stripping away non-essential "fluff" (like crystal/remedy overlays) to provide a minimalist, highly actionable interface.

## ✨ Core Features

* **100% Algorithmic Precision:** Rigorously cross-referenced against professional third-party software for exact chart permutations.
* **Dual-Mode Engine:** Seamlessly integrates both QMDJ (9 Palaces) and Da Liu Ren (4 Lessons / 3 Transmissions) into a unified view.
* **True Solar Time (真太阳时) Correction:** Automatically adjusts civil time based on longitudinal coordinates and the Equation of Time.
* **Traditional Standards:** 
  * Defaults to the strict **Chai Bu (拆补)** method.
  * **Zhuan Pan (转盘)** rotation standard with accurate Luo Shu 8-perimeter routing.
  * Precise **Palace 5 (Center)** borrowing and rendering rules.
* **AI-Optimized Markdown Export:** Generates chart data formatted specifically for Large Language Model (LLM) ingestion, forcing a standardized "Executive Summary" output focused on environment, facing directions, and actionable steps.
* **Progressive Web App (PWA) Ready:** Lightweight, single-file architecture designed to run flawlessly as a full-screen mobile app.

## 🚀 Quick Start (No Build Required)

This application runs entirely in the browser (client-side). There are no databases to configure, no servers to spin up, and no complex dependencies.

### Local Use
1. Clone or download this repository to your local machine.
2. Unzip the folder.
3. Double-click `index.html` to open the app directly in your web browser.

### Mobile Installation (PWA)
To use this as a native-feeling app on your smartphone without an app store:
1. Host the repository on a free static hosting service (e.g., GitHub Pages, Netlify, Vercel).
2. Open the live URL in your mobile browser (Chrome/Safari).
3. Tap the browser menu and select **"Add to Home Screen"**.

## 🛠 Tech Stack

* **Frontend:** Vanilla HTML5, CSS3, JavaScript (ES6)
* **Architecture:** Single-Page Application (SPA)
* **Dependencies:** None (Zero-dependency architecture for maximum performance and longevity)

## 📋 AI Prompting Template

The calculator outputs a specific Markdown template designed to prime AI models for clear, practical divination readings. The generated prompt asks the AI to evaluate:
1. The Querent's Destiny Palace.
2. The Environment/Situation.
3. The Path Forward (Liu Ren flow).
4. Optimal Facing Directions (Life Gate, Open Gate, Rest Gate).

## 📄 License

This project is licensed under the [MIT / GNU GPLv3] License - see the LICENSE file for details.