# 🎨 Computer Graphics Algorithms Playground (C++ + OpenGL)

A hands-on implementation of fundamental **Computer Graphics algorithms** built completely from scratch using **C++ and OpenGL (GLUT)**.

This project focuses on understanding **how pixels are actually rendered mathematically**, instead of relying on high-level graphics libraries.

It covers classic algorithms used in rendering pipelines, game engines, and low-level graphics systems.

---


## ✨ Features Implemented

### 🟢 Basic Drawing
- Points
- Lines
- Triangles
- Rectangles
- Polygons

### 📏 Line Drawing Algorithms
- DDA (Digital Differential Analyzer)
- Bresenham’s Line Algorithm

### ⚪ Curves
- Midpoint Circle Algorithm
- Midpoint Ellipse Algorithm

### 🧩 Polygon Filling
- Scanline Fill
- Boundary Fill (4-connected & 8-connected)
- Flood Fill (4-connected & 8-connected)

### 🔷 Object Rendering
- House
- Car
- Fish
- Human figure

### 🔁 2D Transformations (Manual – without built-in OpenGL transforms)
- Translation
- Rotation
- Scaling
- Reflection
- Shearing
- Fixed point transformations

### 🧊 3D Graphics
- 3D Cube rendering
- Translation, rotation, scaling using keyboard controls
- Depth testing

### ✂️ Line Clipping
- Cohen–Sutherland Algorithm
- Liang–Barsky Algorithm

### 🎬 Animations
- Moving circle (left ↔ right)
- Rotating windmill
- Simple football goal animation

---

## 🧠 What I Learned

This project helped me understand:

- How pixels are plotted manually
- How classic rasterization algorithms work
- Math behind transformations (matrix operations)
- Coordinate systems & projections
- Rendering pipelines basics
- Difference between algorithmic drawing vs built-in functions
- Foundations of game engines & graphics systems

---

## 🛠 Tech Stack

- C++
- OpenGL
- GLUT (FreeGLUT)
- VS Code / g++

---

## ⚙️ Setup & Run

### Install dependencies

### Linux / macOS
```bash
sudo apt install freeglut3-dev   # Ubuntu/Debian
