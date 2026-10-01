# 🪔 Assamese Heritage & Legends — AI Art Gallery

> A curated, interactive gallery featuring **58 AI-generated artworks** celebrating the royal history, cultural luminaries, folklore spirits, sacred Namghars, and traditional architecture of Assam.

🌐 **Live Demo:** [https://angsumi.github.io/assamese-ai-gallery/](https://angsumi.github.io/assamese-ai-gallery/)

---

## 🏛️ Gallery Overview & Categories

| Category | Icon | Count | Description |
| :--- | :---: | :---: | :--- |
| **History & Royalty** | 👑 | 11 | Chaolung Sukapha, Ahom noble commanders, Patra Mantri ministers, and Queen Birangana Sati Sadhani. |
| **Notable Figures & Luminaries** | 📜 | 27 | Srimanta Sankardev, Kalaguru Bishnu Prasad Rabha, Rupkonwar Jyoti Prasad Agarwala, Hemchandra Baruah, and renaissance pioneers. |
| **Folklore & Legends** | 👻 | 4 | Spectral village legends including Japi Pindha Bhoot and Hetuka Xulin. |
| **Sacred & Culture** | 🪔 | 3 | Multi-tiered Guru Asana (Singhasan) and sacred wood carvings (Kurma, Gaja, Singha) from Assamese Namghars. |
| **Traditional Architecture** | 🏡 | 12 | Classic earthquake-resistant Assam-type houses, verandahs (Chora-Ghar), village ponds, and rural homesteads. |

---

## ✨ Features

- **⚡ Instant Search & Filtering**: Search across artwork names, descriptions, historical periods, and tags.
- **🎨 Assamese Cultural Aesthetic**: Warm Muga Silk gold (`#E5B044`), Eri crimson, and Assam tea green palette with glassmorphism effects.
- **🌓 Light & Dark Modes**: Seamless theme switching with automatic system preference detection.
- **🔍 High-Res Lightbox Modal**:
  - Zoom in/out (+ / -) and 100% reset controls.
  - Keyboard navigation (Left / Right arrow keys, Escape to close).
  - Touch swipe support on mobile devices.
  - Direct deep-linking via URL hash (e.g. `#sukapha-portrait`).
  - High-res image download & shareable link copy.
- **📱 Fully Responsive**: Optimized for ultra-wide desktops, laptops, tablets, and smartphones.
- **🚀 Zero-Dependency Static App**: Pure modern HTML5, CSS3, and JavaScript — lightning-fast on GitHub Pages.

---

## 📂 Project Structure

```
├── .github/
│   └── workflows/
│       └── deploy.yml         # GitHub Actions automated Pages deployment
├── css/
│   └── style.css              # Custom styling, dark/light theme, and animations
├── data/
│   └── gallery.json           # Structured metadata, tags, and descriptions
├── images/
│   ├── folklore-and-legends/   # Folklore & ghost lore artworks
│   ├── history-and-royalty/   # Ahom kings, ministers & queens
│   ├── notable-figures/       # Assamese cultural luminaries & scholars
│   ├── sacred-and-culture/    # Namghar sanctums & sacred motifs
│   └── traditional-architecture/ # Assam-type houses & country homesteads
├── js/
│   └── app.js                 # Gallery engine, search, filters & lightbox
├── .nojekyll                  # GitHub Pages static asset flag
├── index.html                 # Main gallery webpage
└── README.md                  # Project documentation
```

---

## 💻 Local Development & Preview

To run the gallery locally:

```bash
# Clone the repository
git clone https://github.com/Angsumi/assamese-ai-gallery.git
cd assamese-ai-gallery

# Start a local web server (using Python 3)
python3 -m http.server 8000
```

Open your browser at `http://localhost:8000` to explore the gallery.

---

## 📜 License & Credits

Artworks generated and curated for the preservation and artistic celebration of Assamese culture, history, and folklore. Open source and free to share.
