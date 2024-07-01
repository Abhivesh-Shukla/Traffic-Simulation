# Traffic Simulation

This Python-based simulation project demonstrates a traffic intersection scenario with dynamic vehicle movement and traffic signal control.

![Traffic Simulation](images/simulation_snapshot.png)

## Overview

The Traffic Simulation project simulates an intersection where vehicles of different types move according to traffic signals. It visualizes how traffic signals (red, yellow, green) manage vehicle flow through the intersection.

## Features

- **Dynamic Vehicle Generation:** Random generation of cars, buses, trucks, and bikes approaching the intersection from four directions.
- **Traffic Signal Management:** Implementation of traffic signals with timers for red, yellow, and green phases.
- **Realistic Vehicle Movement:** Vehicles move realistically within their lanes, respecting stopping gaps and speeds.
- **Graphical User Interface (GUI):** Pygame library utilized for graphical representation of the intersection and vehicles.
- **Simulation Continuity:** Continuous simulation loop ensures ongoing traffic flow and signal management.

## Components

### Traffic Signals

- **Red Signal:** Stops vehicles from entering the intersection.
- **Yellow Signal:** Prepares vehicles to stop as the signal transitions.
- **Green Signal:** Allows vehicles to proceed through the intersection.

### Vehicle Types

- **Car:** Average speed of 2.25 units.
- **Bus/Truck:** Average speed of 1.8 units.
- **Bike:** Average speed of 2.5 units.

### Directions

- **Right, Left, Up, Down:** Vehicles approach the intersection from these cardinal directions.

## Installation and Execution

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Abhivesh-Shukla/CPU-Scheduler-Project.git
   cd Traffic-Simulation
   
2. **Install Dependencies:**  
- Ensure you have Python and Pygame installed.
  
3. **Run the Simulation:**
   ```bash
   python traffic_simulation.py

## File Structure
- The project files are organized as follows:
  ```bash
   Traffic-Simulation/
  │
  ├── traffic_simulation.py     # Main simulation script
  ├── images/                   # Directory for images used in simulation
  │   ├── intersection.png      # Background image of the intersection
  │   ├── signals/              # Directory for signal images (red, yellow, green)
  │   │   ├── red.png
  │   │   ├── yellow.png
  │   │   └── green.png
  │   └── <vehicle_type>/       # Directory for vehicle images (car.png, bus.png, etc.)
  │       ├── car.png
  │       ├── bus.png
  │       ├── truck.png
  │       └── bike.png
  └── README.md                 # Project documentation

## Contributing
- Contributions are welcome! If you find any issues or have enhancements to propose, please fork the repository and submit a pull request. 
