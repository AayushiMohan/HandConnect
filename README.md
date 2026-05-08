# Neon Aura AR

Neon Aura AR is a browser-based augmented reality experience that uses real-time hand tracking to generate interactive neon visuals and audio effects. It runs directly in the browser using your webcam—no additional software required.

---

## Overview:

The system detects hand landmarks from a live camera feed and applies gesture-based logic to render dynamic effects like glowing fingertips, particles, lightning arcs, and sound feedback. The goal is to create an engaging, responsive AR experience using only web technologies.

---
## Made by using :

- Claude and Antigravity 
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
---

# Neon Aura AR

> A browser-based Augmented Reality experience that turns your hand gestures into real-time neon visuals and sound — no installation required.

---

## Overview

Neon Aura AR uses your webcam to detect hand landmarks in real time and renders interactive effects like glowing fingertips, lightning arcs, particle trails, and audio feedback — all inside a single HTML file using only web technologies.

---

## Features

-  Real-time tracking of up to 2 hands simultaneously
-  21 landmark points detected per hand
-  Lightning arcs when both hands come close
-  Shockwave ripple on pinch gesture
-  Neon glowing fingertips with particle trails
-  Audio feedback based on hand movement and distance
-  Matrix-style animated background
-  5 visual themes — Rainbow, Cyberpunk, Lava, Ocean, Galaxy
-  Gesture recognition — Pinch, Open Hand, Fist

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Hand Tracking | MediaPipe Hands (Google AI) |
| Visual Effects | HTML5 Canvas API |
| Sound Effects | Web Audio API |
| Language | HTML, CSS, JavaScript |
| Deployment | Single HTML file — runs in any browser |

---

## How It Works

1. Webcam stream is captured in the browser
2. MediaPipe processes frames and returns 21 hand landmarks per hand
3. Gesture logic interprets finger positions (pinch, fist, open hand)
4. Canvas API renders neon visuals and particle effects in real time
5. Web Audio API generates responsive sound based on hand interactions

---

## How to Run

### Option 1 — Direct Open
Simply open `index.html` in any modern browser → allow camera access → click **"Enter Experience"**

### Option 2 — VS Code Live Server (Recommended)
1. Install the **Live Server** extension in VS Code
2. Right click `index.html` → **Open with Live Server**
3. Allow camera access → click **"Enter Experience"**

---

## Requirements

- Modern browser (Chrome recommended)
- Webcam access
- Internet connection (for MediaPipe CDN)

---

## Visual Themes

| Theme | Vibe |
|-------|------|
| Rainbow | Colorful, vibrant |
| Cyberpunk | Red and cyan neon |
| Lava | Warm orange and red |
| Ocean | Cool blue tones |
| Galaxy | Deep purple and violet |

---

## Use Cases

- Interactive AR demos
- Gesture-based UI experiments
- Creative coding portfolio showcase
- Computer vision learning project
---
