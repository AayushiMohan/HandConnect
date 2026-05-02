# Neon Aura AR

Neon Aura AR is a browser-based augmented reality experience that uses real-time hand tracking to generate interactive neon visuals and audio effects. It runs directly in the browser using your webcam—no additional software required.

---

## Overview:

The system detects hand landmarks from a live camera feed and applies gesture-based logic to render dynamic effects like glowing fingertips, particles, lightning arcs, and sound feedback. The goal is to create an engaging, responsive AR experience using only web technologies.

---
## Made by using :
Claude and Antigravity 
---
## Tech Stack:

- HTML, CSS, JavaScript  
- MediaPipe Hands (hand tracking)  
- Canvas API (2D rendering)  
- Web Audio API (sound effects)

---

## Key Features:

- Real-time tracking of up to 2 hands  
- 21 landmark points detected per hand  
- Pinch gesture detection (thumb + index)  
- Open hand / fist recognition  
- Neon glow fingertips with particle trails  
- Shockwave effect on pinch  
- Lightning interaction between both hands  
- Animated matrix-style background  
- Multiple themes: Rainbow, Cyberpunk, Lava, Ocean, Galaxy  
- Audio feedback based on interaction and hand distance  

---

## How It Works:

1. Webcam stream is captured in the browser  
2. MediaPipe processes frames and returns hand landmarks  
3. Gesture logic interprets finger positions  
4. Canvas renders visual effects in real time  
5. Web Audio API generates responsive sound  

---

> Recommended: Use VS Code Live Server for smoother performance.

---

## Requirements:

- Modern browser 
- Webcam access  
- Internet connection (for CDN libraries)

---

## Use Cases:

- Interactive AR demos  
- Gesture-based UI experiments  
- Creative coding projects  
- Portfolio showcase  

---

## Summary-

A lightweight web AR project that turns hand gestures into real-time neon visuals and sound, combining computer vision, graphics, and audio in a single-page application.
