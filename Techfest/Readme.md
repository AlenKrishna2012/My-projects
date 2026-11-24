# ⚡ WATTWISE — Smart Building Energy Manager

## About the Project

WATTWISE (Smart Building Energy Manager) is an interactive, browser-based 3D energy simulation platform designed to demonstrate how electricity consumption can be monitored, managed, and optimized inside a virtual building.

The project combines a 3D apartment model, interactive electrical appliances, real-time simulated energy monitoring, electricity cost estimation, and customizable device controls into a single web application.

It allows users to interact with a virtual building and explore how different electrical appliances affect overall electricity consumption and energy costs.

---

## 🎯 Project Objective

The main objective of WATTWISE is to create an interactive smart-building simulation that helps users understand electricity consumption, energy management, and the relationship between appliance usage, energy consumption, and electricity bills.

It demonstrates concepts related to:

- Smart buildings
- Energy management
- Electricity consumption
- Energy efficiency
- Digital simulation
- Interactive 3D visualization
- Sustainable energy awareness

---

## 🏠 3D Building Simulation

WATTWISE features a 3D virtual apartment built using Three.js.

Users can interact with the virtual building and its appliances.

### Features

- Interactive 3D apartment visualization.
- Virtual furniture and building components.
- Interactive electrical appliances.
- Drag-and-move functionality for objects.
- Appliance placement within the virtual building.
- 3D visualization of electrical devices.

---

## ⚡ Energy Monitoring Dashboard

The dashboard displays simulated electricity usage information.

### Live Power

Displays the currently simulated electrical power consumption of active devices.

Unit: Watts (W)

### Energy Used

Tracks the accumulated simulated energy consumption.

Unit: Kilowatt-hours (kWh)

### Estimated Electricity Cost

Calculates the estimated electricity cost using the accumulated energy and the user-defined electricity tariff.

### Active Devices

Displays the number of currently switched-on appliances.

---

## 🔌 Appliance Management

Users can manage electrical appliances inside the virtual building.

### Supported Devices

- Ceiling lights
- Wall lights
- Fans
- Televisions
- Refrigerators
- Air conditioners
- Computers

### Device Controls

- Switch devices ON or OFF.
- Add new appliances.
- Remove appliances.
- Rename appliances.
- Modify power consumption.
- Configure standby power.
- Change operating modes.
- Adjust variable power levels.

---

## 🛠️ Device Operating Modes

### Constant Power

Simulates an appliance operating at a constant power level when switched on.

### Variable Power

Allows the power consumption of an appliance to be adjusted using a level slider.

### Automatic Cycle

Simulates an appliance whose power consumption changes according to an automatic operating cycle.

---

## ⏱️ Simulation Clock

The application includes a simulation clock that allows energy usage to accumulate at different simulation speeds.

### Simulation Speeds

- 1× Real Time
- 60×
- 600×
- 3600×

This allows users to simulate longer periods of electricity consumption more quickly.

---

## 💰 Electricity Cost Calculation

The user can set an electricity tariff in ₹ per kWh.

The application estimates electricity costs using:

Cost = Energy Consumed × Electricity Tariff

The calculation is based on simulated energy consumption.

---

## 💾 Data Persistence

WATTWISE uses browser local storage to preserve its simulation data.

Saved data may include:

- Appliance settings
- Appliance states
- Building layout
- Electricity tariff
- Accumulated energy usage

The application can retain saved simulation data when the browser is reopened on the same device, provided the browser storage remains available.

---

## 🔄 Reset Controls

### Reset Calculations

Resets the accumulated energy and related calculation data.

### Reset Building

Restores the building simulation to its default configuration.

---

## 🧰 Technology Stack

- HTML5
- CSS3
- JavaScript
- Three.js
- Browser Local Storage

Three.js is used to render and interact with the 3D building.

---

## ⚠️ Important Limitation

WATTWISE is a software-based energy simulation.

It does not directly measure real electricity consumption, communicate with physical electrical meters, control real appliances, or connect to a smart electrical grid.

All energy readings, device power values, and cost calculations are simulated.

---

## 🌱 Future Development Possibilities

- Real IoT device integration.
- ESP32-based smart energy monitoring.
- Real electricity meter integration.
- Smart plug integration.
- Room-wise energy monitoring.
- Energy-saving recommendations.
- Solar energy simulation.
- Battery storage simulation.
- Automated energy management.
- Historical energy graphs.
- Energy efficiency analysis.
- Smart building automation.

---

## 🏆 Project Significance

WATTWISE demonstrates how interactive 3D technology and digital simulation can be used to explain electricity consumption and energy management.

It combines software development, 3D visualization, simulation, user interaction, and sustainability concepts into a single project.

The project aims to make energy management easier to understand through an interactive digital environment.

---

**Project Name:** WATTWISE  
**Project Type:** Interactive Web-Based 3D Energy Simulation  
**Technology:** HTML, CSS, JavaScript, Three.js  
**Purpose:** Smart Building Energy Management Simulation
