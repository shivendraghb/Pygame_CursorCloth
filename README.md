# 🕸️ Pygame Interactive Cloth Simulation

A lightweight, real-time 2D cloth simulation built entirely in Python using `pygame` and `math`. 

This project uses **Verlet integration** to simulate a physics-based mesh. The cloth is suspended from the top of the screen, reacts to gravity, and is fully interactive—you can drag the fabric around or tear it apart using your mouse!

## ✨ Features
* **Verlet Physics:** Realistic, stable fabric physics using point-masses and spring constraints.
* **Interactive Dragging:** Grab and pull the cloth using the left mouse button.
* **Dynamic Tearing:** Snap the threads by over-stretching them, or cut through the cloth using the right mouse button.
* **Minimalist & Fast:** Highly optimized 6-iteration constraint solver running smoothly at 60 FPS in fullscreen.
* **Neon Aesthetic:** Rendered with a sleek, glowing wireframe style against a dark background.

## 🚀 Getting Started

### Prerequisites
You will need Python 3.x installed on your machine, along with the `pygame` library.

If you don't have Pygame installed, you can add it via pip:
```bash
pip install pygame
