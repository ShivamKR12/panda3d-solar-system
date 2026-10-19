# Panda3D Solar System Simulation

A 3D animated and interactive Solar System simulation and tutorial sample built using the [Panda3D](https://www.panda3d.org/) game engine in Python.

It demonstrates 3D scene-graph hierarchy, planetary orbits, rotational day/year intervals, celestial textures, and an interactive event-handling system.

## 🪐 Features

- **Sun, Inner Planets, and Moons**: Realistic textured models for the Sun, Mercury, Venus, Earth & Moon, and Mars with Phobos & Deimos.
- **Accurate Relative Timings**: Configured day and orbital revolutions using Panda3D intervals.
- **Hierarchical Node Positioning**: Moons attached directly to planet orbital roots, orbiting while their parent planets orbit the Sun.
- **Interactive Controls**: Toggle individual planet orbits/rotations on and off or pause the entire simulation.

## 🕹️ Controls (in Step 6)

- **Left Mouse Click**: Pause / Resume the entire Solar System simulation
- **S**: Toggle Sun rotation
- **Y**: Toggle Mercury orbit and rotation
- **V**: Toggle Venus orbit and rotation
- **E**: Toggle Earth & Moon orbit and rotation
- **M**: Toggle Mars orbit and rotation
- **Esc**: Exit simulation

## 📚 Tutorial Steps

The repository includes a step-by-step tutorial progression:
1. `step1_blank_window.py`: Opens a standard Panda3D display window.
2. `step2_basic_setup.py`: Sets up background, camera orientation, and scale parameters.
3. `step3_load_model.py`: Loads the celestial sphere model and applies the Sun texture.
4. `step4_load_system.py`: Loads all planets and moons into their hierarchical orbit nodes.
5. `step5_complete_solar_system.py`: Sets up and loops `hprInterval` rotations for all celestial bodies.
6. `step6_controllable_system.py`: Adds on-screen UI, earth-year event counters, and interactive keyboard/mouse controls.

## 🚀 Getting Started

### Prerequisites

- Python 3.8+ installed.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ShivamKR12/panda3d-solar-system.git
   cd panda3d-solar-system
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the interactive simulation:
   ```bash
   python main.py
   ```
   *(or run any individual step, e.g. `python step5_complete_solar_system.py`)*

## 🛠️ Credits & Tech Stack

- **Game Engine**: [Panda3D](https://www.panda3d.org/)
- **Language**: Python 3
- **Authors**: Phil Saltzman and Shao Zhang (Official Panda3D Sample)
