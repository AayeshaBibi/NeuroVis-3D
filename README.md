# 🧠 NeuroVis 3D: Interactive Brain Connectome & Atlas

<p align="center">
  <b>An advanced interactive 3D visualization platform for exploring the human brain connectome, neurotransmitter pathways, and neural activity in real time.</b>
</p>

---

# 🌐 Live Demo

🚀 https://www.linkedin.com/posts/ayesha-bibi-8991b3319_neuroscience-braincomputerinterface-threejs-ugcPost-7464198158974296065-KTPE/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFCnMDUB5w--9OObQunIUKNJEfShK5WNuA0

---

# ✨ Features

## 🔍 Deep Hierarchical Brain Navigation

Navigate through the brain’s structure from large-scale regions to microscopic circuits:

* Cerebrum
* Limbic System
* Hippocampus
* CA1 Region
* Dentate Gyrus

Each anatomical node contains:

* Functional descriptions
* Estimated neuron counts
* Activity metrics
* Connectivity information
* Neurotransmitter associations

---

## ⚡ Dynamic Neural Signal Routing

Visualize live neurotransmitter signal propagation through animated neural pathways.

### Supported Neurotransmitter Systems

| Neurotransmitter | Function                |
| ---------------- | ----------------------- |
| Glutamate        | Excitatory signaling    |
| GABA             | Inhibitory signaling    |
| Dopamine         | Reward & motor control  |
| Serotonin        | Mood & sleep regulation |
| Norepinephrine   | Alertness & arousal     |
| Acetylcholine    | Attention & learning    |

### Signal Engine Highlights

* Animated pulse propagation
* White matter tract visualization
* Real-time connectome mapping
* Smooth spline-based neural routing

---

# 🌊 Brain Wave Visualization

Observe where brain waves originate and how they propagate across regions.

| Brain Wave | Frequency Range | Function              |
| ---------- | --------------- | --------------------- |
| Delta      | 0.5 – 4 Hz      | Deep sleep            |
| Theta      | 4 – 8 Hz        | Memory & meditation   |
| Alpha      | 8 – 13 Hz       | Relaxation            |
| Beta       | 13 – 30 Hz      | Focus & cognition     |
| Gamma      | 30 – 100 Hz     | High-level processing |

### Included Visualizations

* Live frequency animations
* Origin region mapping
* Consumption target tracking
* Dynamic waveform displays

---

# 🎨 Visualization Modes

## Exterior Mode

* Procedural textured rendering
* Realistic cortical shading
* Full anatomical surface view

## Cutaway Mode

* Semi-transparent cortex
* Internal structure exploration
* Reveals hidden regions

## X-Ray Mode

* Wireframe visualization
* Structural inspection
* Lightweight rendering

## Signals Mode

* Activates animated neural pathways
* Displays neurotransmitter routing
* Enables connectome activity view

---

# 📊 Real-Time Analytics Dashboard

Interactive analytics panel updates dynamically based on user selection.

### Dashboard Displays

* Active neuron count
* Total neuron count
* Activity percentage bars
* Incoming signal regions
* Outgoing signal targets
* Synaptic connectivity metrics

---

# 🛠️ Tech Stack

## Frontend

* HTML5
* CSS3
* JavaScript (ES6 Modules)

## 3D Rendering

* Three.js (r160)
* WebGL 2.0
* OrbitControls

## Graphics Features

* ACES Filmic Tone Mapping
* Dynamic lighting
* Procedural geometry generation

---

# ⚙️ Technical Architecture

## 🧬 Procedural Anatomy Generation

The brain geometry is procedurally generated rather than imported as a static model.

### Techniques Used

* Fractional Brownian Motion (FBM)
* Vertex displacement
* Procedural noise synthesis
* Dynamic cortical folding

This creates realistic:

* Cerebral sulci
* Gyri
* Cerebellar folia

---

## 🛰️ Neural Pathway System

Signal routes are generated using:

* `CatmullRomCurve3`
* Interpolated spline curves
* Dynamic pulse animation
* Real-time trajectory calculations

---


## 🏷️ Adaptive Label Rendering

Level-of-detail (LOD) based labeling system:

* Labels fade based on distance
* Prevents UI clutter
* Optimizes rendering performance
* Enhances readability

---

# 🚀 Getting Started

## 📥 Clone Repository

```bash
git clone https://github.com/AayeshaBibi/NeuroVis-3D.git
cd NeuroVis-3D
```

---

# ▶️ Running Locally

## Option 1 — VS Code Live Server (Recommended)

1. Open project in VS Code
2. Install **Live Server** extension
3. Right-click `3D_Brain_Connectsome.html`
4. Select **Open with Live Server**

---

## Option 2 — Direct Browser Launch

Simply open:

```bash
3D_Brain_Connectsome.html
```


---

# 📁 Project Structure

```bash
NeuroVis-3D/
│
├── index.html
├── README.md
```

---

# 🧠 Science & AI Inspiration

NeuroVis 3D was inspired by the intersection of:

* Artificial Intelligence
* Neuroscience
* Neural Engineering
* Brain-Computer Interfaces (BCI)

Understanding biological neural systems helps advance:

* Artificial Neural Networks (ANNs)
* Cognitive Computing
* Neuro-AI architectures
* Human-computer interaction systems

This project demonstrates how neuroscience concepts can be transformed into interactive computational visualizations for education, research, and AI exploration.

---

# 💡 Development Philosophy

The neuroscience architecture, data hierarchy, visualization logic, and interaction systems were engineered and designed by me and used z.ai for coding.

AI tools were used as development accelerators for:

* Three.js boilerplate
* Rendering optimization
* Shader experimentation
* Rapid prototyping

This reflects a modern AI-assisted engineering workflow where domain expertise drives system design.

---

# 👩‍💻 Author

## Ayesha Bibi

**AI & Machine Learning Engineer | BCI Researcher**

### 🔗 Connect With Me

* LinkedIn: https://www.linkedin.com/in/ayesha-bibi-8991b3319/

---

# ⭐ Support

If you found this project interesting:

* ⭐ Star the repository
* 🍴 Fork the project
* 🧠 Share with neuroscience & AI enthusiasts
* 🚀 Contribute new features
