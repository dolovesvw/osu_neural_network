# osu_neural_network

**osu_neural_network** is a deep learning project designed to enable Eve (my AI VTuber) to play the rhythm game [osu!](https://osu.ppy.sh/) autonomously. The goal is to create a vision-based neural network that can analyze the game screen in real time and simulate gameplay with high accuracy.

## Project Goal

Create a neural network that allows Eve to:
- Read osu! game screen inputs (circles, sliders, spinners)
- Predict where and when to click
- Simulate human-like reactions and accuracy
- Eventually learn and improve over time

---

## Planned Features

- Real-time screen capture using OpenCV or MSS
- Input simulation with PyAutoGUI or pynput
- CNN-based model to identify hit objects and track cursor
- Optional reinforcement learning for continuous improvement
- Integration with Eve's AI control system

## Current Status

> This project is in the as I would like to call it, the **idea and planning phase**.  
> No code has been written yet.

## Future Steps

1. Collect training data from osu! replays or live gameplay  
2. Train a simple CNN to detect hit objects and predict actions  
3. Create a script to simulate clicks based on model output  
4. Test and refine live gameplay performance  
5. Add memory or learning modules for long-term skill development  

## About osu!

osu! is a rhythm game where players click, hold, and spin in sync with music. This project will start with standard osu! mode (not Mania or Taiko).

---

*This README will evolve as development progresses.*
