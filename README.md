# 🚀 Space Fight Simulator  

---
## 🔗 Project Links  

<p align="center">
  <a href="https://editor.p5js.org/c_reed/sketches/mDrgIoSPPv" target="_blank" style="margin: 10px;">
    <img src="https://img.shields.io/badge/⚙%20Source%20Code-000?style=for-the-badge&logo=p5.js&logoColor=red" 
         alt="Source Code" height="60">
  </a>
  
  <a href="https://youtu.be/hoGkSQsesn0" target="_blank" style="margin: 10px;">
    <img src="https://img.shields.io/badge/📜%20Description-000?style=for-the-badge&logo=youtube&logoColor=red" 
         alt="Description Video" height="60">
  </a>

  <a href="https://youtu.be/1mBuNrYoP-Y" target="_blank" style="margin: 10px;">
    <img src="https://img.shields.io/badge/🎮%20Demo-000?style=for-the-badge&logo=youtube&logoColor=red" 
         alt="Demonstration Video" height="60">
  </a>
</p>
---

## 🛰 Overview  
The **Space Fight Simulator** is an interactive 3D experience where players pilot a spaceship using **head-tracking controls**. Instead of traditional inputs, the game leverages **ML5.js FaceMesh** to detect facial movements, allowing players to steer and boost their ship naturally.  

The simulation features:  
- **AI-Powered Face Tracking** – Move your head to control the ship.  
- **Dynamic Asteroid Field** – Navigate through floating space debris.  
- **Multiple Camera Modes** – Switch between third-person and orbital views.  
- **Web-Based & 3D Rendered** – Runs in the browser using **WebGL & Processing.js**.  

---

## 🎮 Features  

### 🌌 **Head-Tracked Flight Controls**  
- **Tilt Left/Right** – Steer the spaceship.  
- **Look Up/Down** – Adjust pitch.  
- **Boost** – Press `Spacebar` for a speed burst.  

### 🎥 **Camera Modes**  
- **Third-Person View (`1`)** – Follow the spaceship from behind.  
- **Orbital View (`2`)** – Rotate around the scene for a wider perspective.  

### 🖥 **Technical Overview**  

#### **Object-Oriented Codebase**  
The simulator is built using **object-oriented programming (OOP)** principles, with structured classes for:  
- **Spaceship** – Handles movement, boosting, and physics.  
- **Asteroids (Orb Class)** – Floating objects that move and bounce dynamically.  
- **Camera (Cam Class)** – Manages position, transitions, and smooth tracking.  

#### **3D WebGL Rendering**  
- **Built with Processing.js** – A WebGL-based environment for real-time 3D visuals.  
- **Asteroid Physics** – Objects move with randomized velocity and rotation.  
- **Smooth Camera Movement** – Uses **linear interpolation (lerp)** for transitions.  

### 🎯 **AI-Powered Face Tracking**  
Powered by **ML5.js FaceMesh**, the game tracks facial landmarks in real time:  
- **Turn Left/Right** – Tilt your head to steer.  
- **Look Up/Down** – Adjust vertical movement.  
- **Boost** – Activate speed with the `Spacebar`.  

💡 *Face tracking detects head orientation and calculates movement for an intuitive experience.*  

---

## 🕹 How to Play  

### **Basic Controls**  
| Action | Face Tracking | Keyboard |
|--------|--------------|----------|
| Turn Left/Right | Tilt Head Sideways | N/A |
| Look Up/Down | Move Head Up/Down | N/A |
| Boost | N/A | `Spacebar` |
| Camera Mode 1 (Third-Person) | N/A | `1` |
| Camera Mode 2 (Orbital View) | N/A | `2` |

### **Gameplay Flow**  
1. **Start the Simulation** – The spaceship and asteroids load into the 3D world.  
2. **Navigate** – Move your head to steer the spaceship.  
3. **Boost When Needed** – Use `Spacebar` for a quick burst of speed.  
4. **Switch Camera Views** – Press `1` or `2` to change perspectives.  
5. **Explore & Experiment** – Interact with asteroids and adjust your viewpoint.  

---
## 📜 Citations  

This project incorporates assets and libraries from the following sources:  

🔹 **Face Tracking (ML5.js FaceMesh)**  
- [ML5.js FaceMesh Documentation](https://docs.ml5js.org/#/reference/facemesh)  
- [ML5 Face Tracking Example](https://editor.p5js.org/ml5/sketches/lCurUW1TT)  

🔹 **3D Spaceship Model**  
- [Spaceship STL Model](https://www.thingiverse.com/thing:18704) – Sourced from Thingiverse  
