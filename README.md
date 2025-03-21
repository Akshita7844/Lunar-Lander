# 🚀 Lunar Lander Simulation
A simulation of the classic Lunar Lander problem using Gymnasium &amp; Box2D. Watch as a rocket autonomously navigates physics-based terrain to land safely — or crash spectacularly! Includes a pre-recorded video demo and fully customizable Python environment.

---

## 🎥 Demo Video

Click to watch the simulation in action:

[▶️ lunar_lander_simulation.mp4](./lunar_lander_simulation.mp4)

---

## 📂 Files

- `lunar_lander.py` — Main simulation script.
- `lunar_lander_simulation.mp4` — Recorded simulation video.

---

## 💻 Run Locally

### 1. Clone the Repo
```bash
git clone https://github.com/yourusername/lunar-lander-simulation.git
cd lunar-lander-simulation
```

### 2. Create Virtual Environment (Optional)
```bash
python -m venv env
source env/bin/activate  # macOS/Linux
env\Scripts\activate     # Windows
```

### 3. Install Requirements
```bash
pip install gymnasium[box2d] pygame moviepy
```

### 4. Run Simulation
```bash
python lunar_lander.py
```

A video of the simulation will be saved as `lunar_lander_simulation.mp4`.

---

## 🧠 How It Works

- A **heuristic agent** guides the lander using environment observations.
- Rewards are based on proximity to the landing pad, speed, tilt, and leg contact.
- A **video is automatically recorded** during the simulation using MoviePy.

---

## 📜 License

MIT License

---

## 👩‍🚀 Author

- **Andrea PIERRÉ** (original environment)
- **Your Name** (modifications, video recording, and showcase)
