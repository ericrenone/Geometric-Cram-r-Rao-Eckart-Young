# Cramér-Rao ↔ Eckart–Young–Mirsky Geometric Unification Demo

- **Cramér-Rao Bound** (fundamental limit on variance in statistical estimation)
- **Eckart–Young–Mirsky theorem** (optimal low-rank matrix approximation error)


## Core

Both the Cramér-Rao bound and the Eckart–Young–Mirsky theorem provide **sharp geometric bounds** on how much information/precision we can lose when projecting onto a lower-dimensional space — one in continuous parameter space, the other in discrete matrix space.

## Features

- Publication-quality plots (300 dpi, clean style, consistent typography)
- Reproducible results via explicit random seed control
- Safe output directory handling
- Input validation with clear error messages
- Rectangular low-rank matrices in SVD example (realistic setting)
- Modern Python 3 (type hints, pathlib, f-strings)
- Quick smoke-test mode (`--test`)
- Mutually exclusive run modes + detailed help

---

## Overview
**FER Phase Tracker** is a **production-ready visualization tool** for analyzing kinetic phase dynamics in federated learning (FL) and decentralized systems. It combines:
- **2D Potential Field Mapping** (Inverted Fisher Information).
- **Dynamic Telemetry HUD** for real-time tracking of:
  - Momentum Flux
  - Phase Coherence
  - Geometric Tension
  - SHA-256 Delta (state integrity)

**Designed for:** Large-scale FL networks with minimal resource overhead.

---

## Key Features
### 1. **Kinetic Phase Map**
- Visualizes optimization paths in a 2D potential field.
- Gradient quiver plot for directional insight.

### 2. **Dynamic Telemetry HUD**
- **4 Metrics Panels**:
  - **Momentum Flux**: Velocity of state transitions.
  - **Phase Coherence**: Alignment of movement and gradient.
  - **Geometric Tension**: Magnitude of local gradients.
  - **SHA-256 Delta**: Cryptographic state stability.

### 3. **Low-Resource Design**
- Optimized for **communication, memory, and energy efficiency**.
- Aligns with your research on dismantling the "compute wall" in FL.

### 4. **Production-Ready**
- Smooth animation, fixed scaling, and clean visuals.
- Configurable parameters for adaptability.

