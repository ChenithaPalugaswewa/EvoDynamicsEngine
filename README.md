
# Evolution Dynamics Engine : Cheni Makes :/
A dynamic, grid-based ecosystem simulation featuring autonomous creatures, food generation, evolution behavior, and real-time visualization. Built using Python and Matplotlib, designed for experimentation, optimization, and long-term ecosystem modeling.

---

## 🚀 Features
- 🧬 **Autonomous Creatures** with wander, seek, and eat behaviors  
- 🌱 **Food Generation System** with adjustable growth rate & max limits  
- 🧠 **Evolution Parameters** (speed, perception, efficiency, etc.)  
- 🎨 **Smooth Real-Time Visualization** using Matplotlib animation  
- 🛠️ **Configurable Settings** for grid size, population, and food mechanics  
- 🐾 **Trail Rendering** with fade-out to reduce clutter  
- 🧹 **Anti-Glitch Movement** (no jittering, no flying across map)

---

## 📦 Installation & Setup
To get started, clone the repository and navigate into it by running:
```bash
git clone https://github.com/ChenithaPalugaswewa/EvoDynamicsEngine
cd EvoDynamicsEngine
```
Make sure you have Python 3.10 or higher installed. Check your version with:
```bash
python --version
```
If Python is not installed, download it here: https://www.python.org/downloads/

Next, install the required dependencies using pip:
```bash
pip install matplotlib numpy
```
Alternatively, if you have the `requirements.txt` file, run:
```bash
pip install -r requirements.txt
```

Once everything is installed, run the simulation with:
```bash
python sim.py
```
This will open the simulation window and start running the ecosystem.

You can customize the simulation by modifying the parameters at the top of `sim.py`, for example:
```python
GRID_SIZE = 50
NUM_CREATURES = 30
INITIAL_FOOD = 60
FOOD_MAX = 150
FOOD_GROWTH_RATE = 0.02
CREATURE_SPEED = 0.8
TRAIL_FADE_TIME = 20
```
Adjust these values to experiment with different ecosystem behaviors.

---

## 🤝 Contributing
Contributions are welcome! Fork the repository, make your changes, and open a pull request. Please ensure your code is clean and documented.

---

## 📜 License
This project is licensed under the MIT License. You are free to use, modify, and distribute it as long as credit is given.

---

## ⭐ Credits
- **ChenithaP** — Lead Developer  
- **QuantumLeap Studios Inc.** — Project Owner  
Community contributions are welcome.

---

## 💬 Contact
For questions or feedback: https://github.com/ChenithaPalugaswewa

