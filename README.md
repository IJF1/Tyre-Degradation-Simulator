# Tyre-Degradation-Simulator
A simple simulator coded in python, that utilizes Tkinter and Matplotlib to explore the effects of different tyre Compounds over the course of a stint.
The simulator demonstrates tyre wear, grip, temperature, and pressure evolution under different conditions, and how these factors influence lap times and puncture risks.
The base lap time for this project is 87secs which corresponds to the base time of Silverstone.Please refer to the repository to view my analysis of my simulator and comparison to real world tyre data.

---

## Features

- **Tyre Compounds**: Soft, Medium, Hard (unique wear rates, grip profiles, base lap times)  
- **Dynamic Tyre Modelling**  
  - Grip reduction with wear, temperature deviation, and pressure imbalance  
  - Temperature & pressure updates based on driver aggression  
  - Puncture logic once the wear threshold is exceeded  
- **Lap Time Calculation** influenced by: grip loss, wear, temperature effects, punctures  
- **User Controls**: compound selection, stint length, aggression level, track abrasion factors  
- **Visualisations** (live-updated per lap):  
  - Grip  
  - Wear  
  - Temperature  
  - Pressure  
  - Lap time  
- **CSV Export**: automatic save of all stint data  

---

## 🖼️ Screenshots

(Add example screenshots of GUI + plots here)

<p align="center">
  <img src="screenshots/example.png" alt="Simulator screenshot" width="500"/>
</p>

---

## How to Run

1) Clone this repository:  [https://github.com/IJF1/f1-tyre-degradation-sim.git](https://github.com/IJF1/Tyre-Degradation-Simulator.git)
2) Install requirements , MATPLOTLIB may be required - Copy this (pip install matplotlib) into CMD ,TKinter is pre-installed on Python
3) Run the simulator
4) Please refer to the short video in this repository on how to use the application
5) When a CSV file is saved it is saved to downloads as "tyre_simulation_results.csv" , The CSV file contains lap, compound, grip, wear, temperature, pressure, punctured and lap_time for the simulation that has been run


---

## Skills Demonstrated

- **Physics Modelling**: tyre wear dynamics, pressure-temperature relationships, thermal sensitivity  
- **Software Engineering**: modular OOP design (F1Tyre class), Tkinter GUI, file handling  
- **Data Visualisation**: live Matplotlib plots for performance metrics  
- **Simulation Thinking**: realistic failure modes (punctures, overheating, sliding wear)  

---

## Future Improvements

- User customizable track-specific modelling (abrasion, layout effects)  
- Weather conditions (rain, track temperature)  
- Multi-tyre stints with pit stops  
- Full race strategy integration
- Use of Monte carlo to improve randomness. 

---

## 👤 Author

**Imaad Javaid**  
📧 [Imaad.Javaid@outlook.com](mailto:Imaad.Javaid@outlook.com) 

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/imaad-javaid-854941369)  
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/IJF1)

---

👉 *This project is part of my **F1 Simulation Portfolio**, showcasing my passion for motorsport engineering and ability to apply physics + coding to realistic race scenarios.*


