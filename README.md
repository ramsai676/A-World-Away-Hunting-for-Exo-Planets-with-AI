<<<<<<< HEAD
# ExoPlanetHunt — Exoplanet Hunter

ExoPlanetHunt is an AI-first, interactive web application that demonstrates how automated models can assist in exoplanet discovery by scoring and prioritizing candidates from Kepler mission data.

✨ Key Features
This project is built as a single-page application with a rich, dynamic user interface.

- Fully Interactive Particle Background: A mesmerizing canvas background filled with thousands of stars and celestial objects (planets, astronauts, asteroids, nebulas) that drift independently and react to the user's cursor movements.

- Scrollable Single-Page Experience: A modern, multi-section layout that users can scroll through, with content panels that elegantly fade into view.

- Professional UI/UX: Features a "glassmorphism" design with semi-transparent, blurred panels, a fixed header for easy navigation, and a custom animated cursor.

- Fully Responsive: The layout seamlessly adapts to all screen sizes, from mobile phones to widescreen desktops.

- AI Classifier Tool: The core of the project. A dedicated page (classifier.html) that simulates an AI model, allowing users to "analyze" a random object from a built-in Kepler dataset and see the classification results.

- Data Visualization: The classifier displays results using animated progress bars and provides a clear, data-driven reason for its classification.

- Comprehensive Information: The main page includes detailed sections explaining the project's mission, potential applications, and a Q&A about the underlying technology.

- Team Showcase: A dedicated footer section to credit the project's creators.

🚀 How to Run This Project Locally
This project is designed to be incredibly simple to run, as it does not require a Python backend or any complex setup.

1. Download the Files: Make sure you have both project files:
   - index.html (the main landing page)
   - classifier.html (the AI tool page)

2. Place in the Same Folder: Put both index.html and classifier.html into the exact same folder on your computer.

3. Open in Browser: Simply double-click the index.html file. This will open the main website in your default web browser.

That's it! The website is fully functional. Clicking the "Open Planet Classifier" button on the main page will correctly navigate to the tool.

🛠️ Technology Stack
This project leverages a modern, frontend-focused technology stack to deliver a rich user experience without requiring a complex backend.

Frontend:

- HTML5: For the core structure and content.
- CSS3: For custom styling, animations, and the theme system.
- Tailwind CSS: A utility-first CSS framework used for rapid and responsive layout design.
- JavaScript (ES6): Powers all the interactivity, including the canvas animation, UI logic, and data handling.

Key Libraries:

- Chart.js: Used to create the doughnut chart for the "Model Performance" section.
- Tone.js: For generating immersive sound effects on user interaction.

## The Team — THE PATHFINDERS
This project was developed by:
- Ram Sai Kandagatla
- Pavan Tej Mareedu
- Raga Sri Kulakarni
- Akshaya Sirigani
- B. Snehana

How to add a logo
- Place your logo file named `logo.png` into the Exoplanet_Project folder (same folder as `index.html`).
- The header uses: `<img id="site-logo" class="h-12 w-12" src="logo.png" alt="ExoPlanetHunt logo">`
- For a different filename, update the `src` attribute to match your file.
- Recommended: 200×200 PNG or a lightweight SVG for crisp rendering.

About the Chatbot
- A lightweight, client-side retrieval chatbot is included. It loads a seeded FAQ and persists any new FAQ pairs you submit (format: `question|answer`) to your browser's `localStorage` under the key `exop_kb_v1`.
- To add a persistent FAQ: open the chat widget on the main site and send: `question|answer`.
- To edit or export the KB manually: open Developer Tools → Application → Local Storage → key: `exop_kb_v1`.
- All chatbot logic runs locally in the browser — no external servers.
About the Chatbot
- A lightweight client-side AI Chatbot is included in the site. It is trained on a local knowledge base (project mission, dataset, model details, usage FAQ).
- The bot is retrieval-based: it preprocesses the knowledge entries, computes a simple similarity score at runtime, and returns the best answer. This keeps everything local and fast (no server required).
- To extend training: edit the knowledge entries in the index.html/classifier.html JS array or add new FAQs, then reload the page.
=======
# A-World-Away-Hunting-for-Exo-Planets-with-AI
An AI/ML model to identify exoplanets from NASA's Kepler mission data. Created for the NASA Space Apps Challenge 2025.
>>>>>>> 5e10f644ede72ad0044eb9c045763a0785fd3fa1
