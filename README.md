# 2D LiDAR Simulator

An interactive **browser-based LiDAR simulator** built with **HTML5 Canvas + JavaScript**.  
It visualizes ray-casting scans with noise, supports random obstacle generation, and lets you navigate a robot through a virtual world.

---

## ✨ Features
- **Adjustable scan parameters**
  - Field of View (10°–360°)  
  - Number of rays (60–1440)  
  - Maximum range (2–40 m)  
  - Gaussian noise control  

- **Simulation modes**
  - Scan beams only  
  - Point cloud only  
  - Both scan + points  

- **World editing**
  - Draw walls interactively with mouse  
  - Add random segments or boxes  
  - Clear and reset environment  

- **Robot control**
  - `WASD` for movement  
  - `Q` and `E` for rotation  
  - Hold `Shift` for faster motion  

- **Utilities**
  - Screenshot capture  
  - Reset pose button  
  - Link to full documentation  

---

## 🚀 Live Demo
👉 [Try it here](https://aotlacan.com/lidar.html)

---

## 📖 How It Works

### Ray Casting
Each LiDAR beam is modeled as a **ray** from the robot’s position:
