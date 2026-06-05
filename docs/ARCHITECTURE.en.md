# How it works (the part you need)

[中文](ARCHITECTURE.md) | **English**

## What you see in the browser

- **Canvas & interaction (frontend)**: renders geometry and function graphs; handles dragging, constraints/snapping, and instant recompute
- **Backend service**: user/auth & permission, subscription features, and AI request orchestration
- **AI model**: converts your input into an executable “drawing steps” plan

## How AI “draws” (simplified)

- You already have some objects on the canvas → the app maintains the current canvas state
- You describe what you want → the system sends your input + current state to the model
- The model returns **drawing steps** (not a single rendered image)
- The canvas executes steps in order → you see objects appear step-by-step

## Why this is good for learning & teaching

- **Inspectable**: every step is explicit—you can judge correctness immediately
- **Extendable**: AI gives you a starting diagram; you can continue manually on top of it
- **Hard to “break”**: constraints/snapping keep relationships valid while dragging

