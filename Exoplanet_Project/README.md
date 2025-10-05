# ExoPlanetHunt — Exoplanet Hunter

ExoPlanetHunt is a professional, fully interactive web application demonstrating AI-assisted exoplanet discovery. It helps researchers and citizen scientists analyze Kepler-derived candidates using a simulated classifier and an integrated local chatbot.

Key features
- Interactive particle/space background and modern UI.
- Planet Classifier page: shows per-criterion likelihoods (orbits star, round shape, cleared orbit) and an explanation.
- Local Retrieval Chatbot: a client-side assistant trained from an editable KB in the HTML files.
- Dataset visualization (Chart.js) and a demo CSV of Kepler-like candidates.

Team — THE PATHFINDERS
- Ram Sai Kandagatla
- Pavan Tej Mareedu
- Raga Sri Kulakarni
- Akshaya Sirigani
- B. Snehana

How to add a logo
1. Place your logo image as `logo.png` in the same folder as `index.html` and `classifier.html` (Exoplanet_Project/logo.png).
2. The header image src is already set to `logo.png`. If not found, a small SVG badge will be used as fallback.
3. Optionally replace the `src` with a path to any other image (for example `/assets/logo.svg`) and set an appropriate `alt`.

Chatbot — local training and extension
- The chatbot is purely client-side and uses a small knowledge base (KB) embedded in `index.html` and `classifier.html`.
- To extend or "re-train" the bot:
  1. Open `index.html` or `classifier.html`.
  2. Find the `const KB = [ ... ]` array near the bottom of each file.
  3. Add or edit entries in the form: { q: "question phrase", a: "answer string" }.
  4. Save and reload the page — the bot recomputes token vectors at load time and will immediately answer new queries.
- For production-grade assistants, consider exporting the KB to a backend, using embeddings, and a vector DB + LLM for RAG.

Running locally
- Place `index.html`, `classifier.html`, and `nasa_data.csv` in the same folder.
- Open `index.html` in a browser. Click "Open Planet Classifier" to navigate to the classifier.

Notes
- The classifier page included here is a demo that uses embedded CSV features. For a full model, export your trained model and host an inference endpoint.
