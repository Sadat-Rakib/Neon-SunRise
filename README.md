# Neon-SunRise

# 🌅 Neon SunRise - MSBR Studio

A retro-futuristic, neon-infused 3D sunrise experience powered by [Three.js](https://threejs.org/) and custom shader effects. Inspired by synthwave aesthetics and classic vaporwave visuals, this project creates a dynamic, animated landscape with glowing terrain, a wireframe sun, and a touch of analog TV distortion.

---

## 🚀 Features

- **Procedural Neon Terrain:** Dynamic, undulating wireframe ground.
- **Wireframe Sun:** A glowing icosahedron "sun" rising over the horizon.
- **Analog TV Effects:** BadTV, static, film grain, and RGB shift shaders for a nostalgic look.
- **Animated Starfield:** Floating neon particles in the background.
- **Multi-Pass Postprocessing:** Layered scenes with advanced shader effects.
- **Responsive Fullscreen Canvas:** Immersive experience on any screen.

---

## 📦 Getting Started

### 1. **Clone the Repository**

git clone https://github.com/Sadat-Rakib/Neon-SunRise.git
cd neon-sunrise

text

### 2. **Open the App**

Just open `index.html` in your favorite browser.  
No build steps or server required!

> **Note:**  
> This project uses [Three.js r84](https://cdnjs.cloudflare.com/ajax/libs/three.js/84/three.min.js) and external shader scripts via CDN.  
> For best results, use Chrome or Firefox.

---

## 📁 Project Structure

neon-sunrise/
│
├── index.html # Main HTML file, loads all scripts via CDN
├── style.css # Neon-inspired CSS for fullscreen visuals
├── main.js # Core Three.js and shader logic
└── README.md # This file!

text

---

## ⚙️ Customization

- **Shaders:**  
  Tweak the parameters in `main.js` for BadTV, Static, Film, and RGBShift shaders to create your own unique visual flavor.
- **Colors:**  
  Change terrain, sun, and light colors for different moods.
- **Geometry:**  
  Try different geometries for the sun or terrain for new effects.

---

## 🛠️ Dependencies

- [Three.js r84](https://cdnjs.cloudflare.com/ajax/libs/three.js/84/three.min.js)
- [BadTVShader](https://www.airtightinteractive.com/demos/js/badtvshader/)
- [EffectComposer & Postprocessing](https://threejs.org/examples/#webgl_postprocessing)
- [Custom Shaders (Static, Film, RGBShift, etc.)](https://www.airtightinteractive.com/demos/js/badtvshader/)

All dependencies are loaded via CDN in `index.html`.

---

## 🖌️ Credits

- **Three.js:** [threejs.org](https://threejs.org/)
- **BadTVShader & Film Effects:** [Airtight Interactive](https://www.airtightinteractive.com/demos/js/badtvshader/)
- **Inspiration:** [Synthwave & Vaporwave Art](https://en.wikipedia.org/wiki/Vaporwave)

---

## 🤝 Contributing

Pull requests are welcome!  
Feel free to open issues or suggest features.

---

## 📜 License

MIT License.  
See [LICENSE](LICENSE) for details.

---

## 💡 Tips

- For a modern version with more features and mobile support, try upgrading to the latest [Three.js](https://threejs.org/) and using [UnrealBloomPass](https://threejs.org/examples/?q=bloom#webgl_postprocessing_unreal_bloom).
- Want music? Add a synthwave soundtrack for full immersion!

---

**Enjoy your journey into the neon sunrise!**  
*— MSBR Studio*
