# Onam 2026 — Celebrating Harmony, Prosperity & Culture (കേരളോത്സവം)

A tribute web experience dedicated to **Onam**, the harvest festival of Kerala. Celebrating King Mahabali, Athapookkalam floral art, the grand 26-dish Onasadya served on a plantain leaf, Vallam Kali snake boat races, Pulikali, and the rich cultural heritage of God's Own Country.

---

## 🌟 Key Features & Interactive Modules

1. **👑 Ornamental Onam Greeting Card Creator & High-Res PNG Download (`v1.3`)**:
   - **Authentic Kerala Visual Aesthetics**: Multi-layered Kasavu gold zari brocade borders, 4-corner lotus & paisley filigrees, glowing brass *Nilavilakku* oil lamp with animated aura, hanging Marigold & Jasmine flower garlands, subtle *Athapookkalam* mandala watermark, and royal *Ponn Onam 2026* seal medallion.
   - **Retina-Grade PNG Exporter with Strict Aspect Ratio Preservation**: Direct procedural HTML5 Canvas engine rendering at ultra-crisp resolutions matching selected aspect ratios:
     - **Landscape (4:3)**: 1600 × 1200 px
     - **Square (1:1)**: 1400 × 1400 px
     - **Portrait (9:12 / 3:4)**: 1080 × 1440 px
   - **Proportional Flexbox-Matched Budgeting**: Dynamic vertical space calculations that prevent clustering or awkward gaps, ensuring the wish text and Athapookkalam watermark remain vertically centered in all formats.
   - **Rich Customization Controls**: Theme palettes (*Kasavu Gold*, *Royal Maroon*, *Plantain Leaf*, *Sunset Saffron*), Ornamentation styles (*Royal Kasavu*, *Temple Arch*, *Pookkalam*, *Heritage*), Aspect ratios (*Landscape*, *Square*, *Portrait*), and live editable blessing text.
   - **Instant Sharing**: 1-click PNG download with celebration confetti and temple chime audio, plus 1-click clipboard copy and WhatsApp sharing.
2. **🍃 Authentic Onasadya Plantain Leaf & Feast Explorer**:
   - High-definition flat-lay visual of the traditional 26-dish Onasadya banquet arranged in ceremonial order on a fresh banana leaf (*Thalavazha Ila*).
   - Dual-view switcher: **Authentic Banana Leaf Feast** photo mode and **Interactive Dish Guide** with rich cultural notes on Matta Rice with Ghee & Parippu, Ada Pradhaman, Avial, Olan, Sambar, Injipuli, Thoran, Upperi Chips, Sharkara Varatti, Pappadam, and Pachadi.
3. **🌸 Interactive Athapookkalam Flower Mandala**:
   - Dynamic 10-ring floral carpet with interactive color-palette cycling (Golden Kasavu, Marigold Sunset, Royal Crimson, Emerald Bloom).
4. **🚣 Kerala Cultural Tapestry Gallery**:
   - Rich SVG art and photography showcase featuring *Chundan Vallam* (Snake Boat Race), *Kathakali Paccha*, *Pulikali Tiger Dance*, *Nilavilakku Grace*, and the *Grand Onasadya Leaf*.
5. **📅 The 10 Sacred Days Timeline (Atham to Thiruvonam)**:
   - Interactive day-by-day journey outlining rituals from *Atham*, *Chithira*, *Chodhi*, *Vishakam*, *Anizham*, *Thriketa*, *Moolam*, *Pooradam*, *Uthradam* (First Onam) to *Thiruvonam* (Main Feast Day).
6. **🎵 Procedural Audio & Confetti Flower Showers**:
   - Synthesized temple chimes & bell harmonics via Web Audio API (Mohanam raga pentatonic scale), accompanied by petal-particle showers using Canvas Confetti.
7. **🌐 Social Sharing & Open Graph Link Preview Optimization (`v1.4`)**:
   - Fully compliant Open Graph, LinkedIn Post Inspector, and Twitter Card metadata with canonical URLs, secure URLs, and a high-resolution 1200×675 raster share banner (`og-image.jpg` / `og-image.png`).

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
- **Canvas Rendering**: High-DPI HTML5 Canvas 2D engine with dynamic proportional space budgeting for PNG card exporting.
- **Interactivity**: Vanilla JavaScript (ES6+), Web Audio API for synthetic bell chimes, IntersectionObserver for scroll reveals, and Canvas Confetti for floral particle showers.
- **Visual Assets**: Procedurally generated high-definition Onasadya Banana Leaf image and custom SVG artwork.

---

## 📖 Architectural Deep-Dive

For complete engineering analysis, DSP synthesis formulations, and design specifications, refer to [GEMINI.md](file:///d:/Playground/ParbonStatic/Onam2026/GEMINI.md).