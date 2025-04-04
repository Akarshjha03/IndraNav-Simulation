# 🚗 INDRANAV: ADAPTIVE DRIVING SYSTEM - SIMULATION 🛣️

A fully functional self-driving car simulation built using vanilla JavaScript, featuring a neural network for autonomous navigation. No external libraries required! 🎯

---

## 📌 Features

- 🏎️ Car simulation with physics-based motion
- 🧠 Neural network-based decision-making
- 🎯 Collision detection and lane navigation
- 📈 Machine learning with a simple backpropagation algorithm
- 🖥️ Customizable road and traffic settings

---

## 📂 Project Structure
```text
IndraNav - Visualize
├── 📁 assets        # Image assets (if any)
├── 📄 index.html    # Main HTML file
├── 📄 style.css     # Styling for the simulation
├── 📄 script.js     # Core JavaScript logic
├── 📄 car.js        # Car class implementation
├── 📄 road.js       # Road and lane drawing logic
├── 📄 network.js    # Simple neural network implementation
└── 📄 utils.js      # Helper functions
```

## 🖥️ Usage
- Use the arrow keys to manually control the car (optional).
- Refresh the page to restart the training process.
- Adjust neural network parameters in network.js for better learning results.

## 💡 How It Works
1. The car senses its surroundings using raycasting sensors.
2. A neural network processes sensor data and determines the best steering actions.
3. The car continuously learns from interactions with obstacles and other cars.

## 🛠️ Technologies Used
- JavaScript (Vanilla) - Core logic
- HTML & CSS - Interface and visualization
- Canvas API - Graphics rendering

---

## 📜 License
This project is open-source under the MIT License.

## 🙌 Contributing
Contributions are welcome! To contribute:

- Fork the repository 🍴
- Create a new branch 🔀
- Implement your changes 🚀
- Submit a pull request ✅
