# 🤖 Three-JS Robot – 3D Model with Bloom Effect

Welcome to the Three-JS Robot project — a visually stunning 3D demo built using **Three.js**. This project loads a robot model (`.glb`) into a 3D scene, applies HDRI lighting for realistic reflections, and enhances visuals with bloom post-processing. Orbit controls allow interactive camera movement, making it a perfect showcase of modern WebGL rendering.

---

## 📚 Table of Contents  
- About the Project  
- Technologies Used  
- Features  
- Getting Started  
- File Structure  
- Contributing  

---

## 🧩 About the Project  
This project demonstrates how to:  
- Load and render a 3D robot model using **GLTFLoader**  
- Apply HDRI environment maps for realistic lighting  
- Use **OrbitControls** for interactive navigation  
- Add bloom effects with **UnrealBloomPass** for cinematic visuals  
- Handle responsive resizing for different screen sizes  

Perfect for:  
- Beginners exploring Three.js basics  
- Developers learning model loading and post-processing  
- Portfolio projects showcasing 3D graphics  

---

## 🛠 Technologies Used  
- **Three.js** – Core 3D rendering library  
- **GLTFLoader** – For loading `.glb` robot models  
- **RGBELoader** – For HDRI environment textures  
- **OrbitControls** – Interactive camera controls  
- **EffectComposer & UnrealBloomPass** – Post-processing pipeline for bloom effects  

---

## ✨ Features  
🤖 **3D Robot Model:**  
- Loads `robot.glb` with proper scaling and positioning  

🌌 **HDRI Environment:**  
- Realistic reflections and lighting using HDR textures  

🎮 **Interactive Controls:**  
- OrbitControls with damping for smooth navigation  

💡 **Directional Lighting:**  
- Adds depth and highlights to the robot model  

⚡ **Bloom Effect:**  
- Cinematic glow with adjustable intensity, radius, and threshold  

📱 **Responsive Rendering:**  
- Handles window resizing dynamically  

---

## 🚀 Getting Started  
### Prerequisites  
- Node.js installed  
- Basic knowledge of Three.js  

### Installation  
```bash
# Clone the repo
git clone https://github.com/yourusername/threejs-robot.git

# Navigate into the folder
cd threejs-robot

# Run a local server (e.g., using VS Code Live Server or npm http-server)
```

Open `index.html` in your browser to see the robot in action.

---

## 📁 File Structure  
```
threejs-robot/
├── index.html
├── script.js
├── robot.glb
└── textures/
    └── studio_small_03_1k.hdr
```

Inside `script.js`:  
- Scene, camera, and renderer setup  
- HDRI environment loading  
- Robot model loading with GLTFLoader  
- OrbitControls for navigation  
- Bloom post-processing pipeline  

---

## 🤝 Contributing  
Enhancements you can add:  
- Animation clips for robot movement  
- GUI controls for bloom intensity and lighting  
- Multiple models or scene switching  
- Shadows and PBR materials for realism  

Would you like me to also draft a **step-by-step setup guide** (with `npm install three` and imports) so the README doubles as a tutorial for anyone cloning your repo?
