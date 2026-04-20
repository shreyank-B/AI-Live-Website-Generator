# AI-Live-Website-Generator
ARCA is a state-of-the-art AI website generator that instantly creates responsive web interfaces from natural language. Featuring an immersive Liquid Obsidian UI, multi-device previews, 1-click code export, and multi-model AI support (Gemini, GPT-4o, Llama), ARCA seamlessly transforms your ideas into functional code.
<div align="center">
  <h1>✨ ARCA AI Website Generator ✨</h1>
  <p><strong>A Next-Generation, AI-Powered Web Interface Builder</strong></p>
</div>

<br />

## 📖 Overview

**ARCA** is a state-of-the-art, AI-driven development environment that seamlessly transforms natural language descriptions into beautiful, responsive, and fully functional web interfaces. Built for rapid prototyping and deployment, ARCA removes the friction from frontend engineering by instantly generating complete HTML, CSS, and JavaScript. 

Wrapped in an ultra-premium **Liquid Obsidian UI**, the platform offers a deeply immersive, glassmorphism-inspired workspace. Whether you are a solo developer testing ideas or a designer iterating on concepts, ARCA delivers high-fidelity, production-ready code with responsive multi-device previews and instant 1-click exporting.

---

## ✨ Key Features

- 🧠 **Tri-Model AI Support**: Leverage the power of industry-leading Large Language Models. ARCA seamlessly integrates with **Google Gemini 2.0 Flash**, **OpenAI GPT-4o**, and **Groq Llama 3.3** for unparalleled code generation accuracy.
- 🎨 **Liquid Obsidian Interface**: A high-fidelity, hyper-modern UI featuring advanced 4K-ready glassmorphism, fluid micro-animations, curated typography, and an optimal dark-themed aesthetic.
- 📱 **Dynamic Responsive Previews**: Instantly test how generated interfaces look across different viewports with built-in Desktop, Tablet, and Mobile toggle modes.
- ⚡ **Real-Time Generation & Execution**: Describe your vision, watch the AI stream the code, and instantly see the live result rendered securely in the built-in preview sandbox.
- 📦 **1-Click Exporting**: Instantly download your generated projects either as a standalone Single-File HTML or beautifully structured ZIP packages containing separate HTML, CSS, and JS files.
- 🛡️ **Secure Architecture**: Employs a lightweight Node.js proxy server layer limiting the exposure of sensitive API keys on the client side.

---

## 🛠️ Tech Stack

- **Frontend Environment**: HTML5, CSS3, Vanilla JavaScript.
- **Backend / Proxy**: Node.js, Express.js, CORS, Axios (for secure API routing).
- **AI Integrations**: Gemini API, OpenAI API, Groq Cloud API.

---

## 🚀 Getting Started (Local Development)

ARCA's architecture leverages a lightweight Node.js Server (`proxy.js`) to process external AI API calls securely, keeping your API keys hidden from the client-side browser.

### Option 1: Quick Launch (Windows)
We've included a batch script for zero-friction startup.
1. Simply double-click the `start_arca.bat` file in the root directory.
2. The script will automatically start the Node proxy server and open the ARCA workspace in your default web browser.

### Option 2: Manual Launch (macOS / Linux / Windows)
1. Ensure you have [Node.js](https://nodejs.org/) installed.
2. Open a terminal in the root directory and install dependencies if necessary:
   ```bash
   npm install express cors axios dotenv

Run the backend proxy server:
bash
node proxy.js
Open the index.html file in your preferred web browser, or serve it using a local server using npx serve .
🌍 Deployment
To launch ARCA online and share it publicly:

Deploy the Backend: Host the proxy.js file on a Node.js-compatible service (e.g., Render, Railway, Vercel Functions).
Configure Endpoints: Inside index.html, locate the localhost fetch endpoints and update them to point to your new live proxy URL.
Deploy the Frontend: Host the index.html natively on any static host (e.g., Vercel, Netlify, GitHub Pages) and link your custom domain!
