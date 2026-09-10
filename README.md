# 🌌 Gravity Simulator

A real-time gravity simulation built in C++ using OpenGL and GLFW. It simulates Newtonian gravitational forces, orbital trajectories, and mass attraction between bodies.

## ✨ Features

* Real-time calculation of gravitational forces between multiple bodies
* Trajectory tracking and orbital visualization
* Interactive camera controls

## 🛠️ Tech Stack

* **Language:** C++
* **Graphics:** OpenGL
* **Window & Input Handling:** GLFW

## 🚀 How to Run

### Compilation
Compile using `g++` and link the required OpenGL/GLFW libraries:

```bash
g++ gravity_sim.cpp -o gravity_sim -lglfw3 -lopengl32 -lgdi32
