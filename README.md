# Onam 2026 — Celebrating Harmony, Prosperity & Culture (കേരളോത്സവം)

A tribute web experience dedicated to **Onam**, the harvest festival of Kerala. Celebrating King Mahabali, Athapookkalam floral art, the grand 26-dish Onasadya served on a plantain leaf, Vallam Kali snake boat races, Pulikali, and the rich cultural heritage of God's Own Country.

---

## 🌟 Key Features & Interactive Modules

1. **🍃 Authentic Onasadya Plantain Leaf & Feast Explorer**:
   - High-definition flat-lay visual of the traditional 26-dish Onasadya banquet arranged in ceremonial order on a fresh banana leaf (*Thalavazha Ila*).
   - Dual-view switcher: **Authentic Banana Leaf Feast** photo mode and **Interactive Dish Guide** with rich cultural notes on Matta Rice with Ghee & Parippu, Ada Pradhaman, Avial, Olan, Sambar, Injipuli, Thoran, Upperi Chips, Sharkara Varatti, Pappadam, and Pachadi.
2. **🌸 Interactive Athapookkalam Flower Mandala**:
   - Dynamic 10-ring floral carpet with interactive color-palette cycling (Golden Kasavu, Marigold Sunset, Royal Crimson, Emerald Bloom).
3. **🚣 Kerala Cultural Tapestry Gallery**:
   - Rich SVG art and photography showcase featuring *Chundan Vallam* (Snake Boat Race), *Kathakali Paccha*, *Pulikali Tiger Dance*, *Nilavilakku Grace*, and the *Grand Onasadya Leaf*.
4. **📅 The 10 Sacred Days Timeline (Atham to Thiruvonam)**:
   - Interactive day-by-day journey outlining rituals from *Atham*, *Chithira*, *Chodhi*, *Vishakam*, *Anizham*, *Thriketa*, *Moolam*, *Pooradam*, *Uthradam* (First Onam) to *Thiruvonam* (Main Feast Day).
5. **💌 Personalized Onam Wish Card Generator**:
   - Custom greeting builder with Malayalam blessings, customizable themes (Kasavu Gold, Sunset Maroon, Banana Leaf Green), confetti flower showers, and 1-click clipboard / WhatsApp sharing.
6. **🎵 Procedural Audio & Confetti Flower Showers**:
   - Synthesized temple chimes & bell harmonics via Web Audio API, accompanied by petal-particle showers using Canvas Confetti.

---

## 🚀 Running Locally

No build step or external backend required. Run directly with any static file server:

```bash
# Using Python
python -m http.server 8000

# Using Node / npx
npx serve .
```

Then open `http://localhost:8000` in your web browser.

---

## 🛠️ Technology Stack

- **Markup**: Semantic HTML5 with accessibility attributes and SEO Open Graph / Twitter Card meta tags.
- **Styling**: Vanilla CSS3 with Kasavu gold / leaf green / royal maroon design tokens, responsive CSS Grid and Flexbox layouts.
- **Interactivity**: Vanilla JavaScript (ES6+), Web Audio API for synthetic bell chimes, IntersectionObserver for scroll reveals, and Canvas Confetti for floral particle showers.
- **Visual Assets**: Procedurally generated high-definition Onasadya Banana Leaf image and custom SVG artwork.

---

## 📖 Architectural Deep-Dive

For complete engineering analysis, DSP synthesis formulations, and design specifications, refer to [GEMINI.md](file:///d:/Playground/ParbonStatic/Onam2026/GEMINI.md).