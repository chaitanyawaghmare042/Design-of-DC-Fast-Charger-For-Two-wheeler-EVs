![EV](https://img.shields.io/badge/Electric-Vehicle-green)
![SMPS](https://img.shields.io/badge/SMPS-Design-blue)
![Power Electronics](https://img.shields.io/badge/Power-Electronics-orange)
![Fast Charger](https://img.shields.io/badge/Fast-DC%20Charger-red)
![COEP](https://img.shields.io/badge/COEP-Tech-purple)

# ⚡ **SMART BATTERY CHARGER FOR TWO-WHEELER ELECTRIC VEHICLES**

![EV](https://img.shields.io/badge/Electric-Vehicle-green)
![SMPS](https://img.shields.io/badge/SMPS-Design-blue)
![Power Electronics](https://img.shields.io/badge/Power-Electronics-orange)
![Fast Charger](https://img.shields.io/badge/Fast-DC%20Charger-red)
![COEP](https://img.shields.io/badge/COEP-Tech-purple)

---

# 📌 **PROJECT OVERVIEW**

The **Smart Battery Charger for Two-Wheeler Electric Vehicles** is a high-power isolated DC fast charger designed for charging lithium-ion battery packs used in electric scooters, e-bikes, and other light electric vehicles.

The charger utilizes **High-Frequency Switch Mode Power Supply (SMPS) Technology** to convert **230V AC mains supply** into a regulated **67.2V DC output** capable of delivering up to **30A charging current** with approximately **2kW output power**.

The system significantly reduces charging time while maintaining battery safety, charging efficiency, and electrical isolation.

---

# 🎯 **PROPOSED SOLUTION**

Conventional EV chargers often require several hours to fully charge a battery due to their low charging power capability.

This project proposes a:

✅ High-Power Fast DC Charger

✅ High-Frequency Isolated SMPS Architecture

✅ Constant Current – Constant Voltage (CC-CV) Charging

✅ Efficient Thermal Management

✅ Safe Battery Charging Mechanism

✅ Compact and Lightweight Design

The charger is specifically developed for **60V Nominal Lithium-Ion Battery Systems** used in electric two-wheelers.

---

# 📖 **PROJECT DESCRIPTION**

The charger architecture consists of multiple stages:

1. AC Input Protection
2. EMI Filtering
3. Bridge Rectification
4. Bulk DC Filtering
5. High-Frequency MOSFET Switching
6. Ferrite Core Transformer Isolation
7. Secondary Rectification
8. Output Filtering
9. Optocoupler Feedback Circuit
10. CC-CV Charging Control

A PWM controller regulates the switching operation and maintains stable voltage and current throughout the charging cycle.

The feedback system utilizes a **TL431 Precision Reference IC** and **PC817 Optocoupler** to provide electrical isolation and accurate output regulation.

---

# 🎯 **OBJECTIVES**

* Study the architecture of Fast DC EV Chargers
* Design a 67.2V, 30A isolated charger
* Study High-Frequency SMPS operation
* Analyze MOSFET switching techniques
* Understand Ferrite Transformer design
* Implement CC-CV charging methodology
* Analyze thermal management techniques
* Improve charger efficiency and safety
* Study industrial EV charger architectures

---

# ⚙️ **TECHNICAL SPECIFICATIONS**

| Parameter           | Specification       |
| ------------------- | ------------------- |
| Input Voltage       | 230V AC, 50Hz       |
| Output Voltage      | 67.2V DC            |
| Output Current      | 30A                 |
| Output Power        | ~2kW                |
| Battery Type        | 60V Li-Ion Battery  |
| Switching Frequency | 45kHz – 60kHz       |
| Charging Method     | CC-CV               |
| Isolation           | Ferrite Transformer |
| Efficiency          | 85% – 90%           |

---

# 🔩 **MAJOR COMPONENTS**

| Component              | Rating / Specification | Quantity |
| ---------------------- | ---------------------- | -------- |
| Input Fuse             | 10A, 250V Slow Blow    | 1        |
| MOV Varistor           | 14D471K                | 1        |
| NTC Thermistor         | 10D-9                  | 1        |
| Bridge Rectifier       | GBU2510, 25A, 1000V    | 1        |
| Bulk Capacitor         | 330µF, 450V            | 1        |
| PWM Controller IC      | UC3845 / UC3846        | 1        |
| Power MOSFET           | 28N60, 600V, 30A       | 1        |
| Ferrite Transformer    | EE55 Core              | 1        |
| Schottky Diode         | MBR20100CT             | 2        |
| Output Capacitor       | 2200µF, 100V           | 1        |
| Optocoupler            | PC817                  | 1        |
| TL431 IC               | Adjustable Reference   | 1        |
| Current Sense Resistor | 0.003Ω, 5W             | 1        |
| Cooling Fan            | 12V DC                 | 1        |
| Aluminium Heat Sink    | High Power Type        | 2        |
| Output Relay           | 30A DC Relay           | 1        |

---

# 🔄 **WORKING PRINCIPLE**

## **Stage 1 – Input Protection & EMI Filtering**

* Fuse protects against overcurrent conditions.
* MOV suppresses voltage surges.
* NTC thermistor limits inrush current.
* EMI filter removes switching noise.

## **Stage 2 – AC to DC Conversion**

* Bridge Rectifier converts AC into pulsating DC.
* Bulk Capacitor smooths the DC bus voltage.

## **Stage 3 – High Frequency Switching**

* PWM Controller drives the MOSFET.
* MOSFET switches at 45–60 kHz frequency.

## **Stage 4 – Isolation & Voltage Conversion**

* EE55 Ferrite Transformer provides:

  * Electrical Isolation
  * Voltage Step-Down
  * Efficient Power Transfer

## **Stage 5 – Secondary Rectification**

* Schottky Diodes convert high-frequency AC into DC.

## **Stage 6 – Output Filtering**

* Capacitors and inductors reduce output ripple.

## **Stage 7 – Feedback Control**

* TL431 and PC817 continuously regulate output voltage.

## **Stage 8 – CC-CV Charging**

### Constant Current Mode (CC)

* Delivers 30A charging current.
* Rapid battery charging.

### Constant Voltage Mode (CV)

* Maintains 67.2V output.
* Charging current gradually decreases.
* Prevents battery overcharging.

---

# 📊 **EXPERIMENTAL RESULTS**

| Parameter                | Result        |
| ------------------------ | ------------- |
| Output Voltage           | 67.2V DC      |
| Maximum Charging Current | 30A           |
| Output Power             | ~2kW          |
| Charging Method          | CC-CV         |
| Estimated Efficiency     | 85% – 90%     |
| Charging Time            | 1 – 1.5 Hours |

### Key Findings

* Reduced charging time compared to conventional chargers.
* High efficiency through SMPS technology.
* Compact charger design due to high-frequency operation.
* Improved battery safety using CC-CV charging.
* Reliable electrical isolation using ferrite transformer.

---

# 🔐 **SAFETY FEATURES**

* Overcurrent Protection
* Surge Protection
* Inrush Current Limiting
* Short Circuit Protection
* Thermal Protection
* Galvanic Isolation
* EMI Suppression
* Current Limiting
* Battery Overcharge Protection

---

# 📈 **FUTURE SCOPE**

* Smart Battery Management System (BMS)
* IoT-Based Monitoring
* Mobile Application Integration
* Cloud-Based Charger Analytics
* AI-Based Battery Health Prediction
* Solar Integrated EV Charging
* Fast Charging Optimization
* Real-Time Data Monitoring Dashboard

---

# 🛠️ **TOOLS & TECHNOLOGIES USED**

* Power Electronics
* SMPS Design
* Electric Vehicle Charging Technology
* PWM Control
* CC-CV Charging
* Ferrite Transformer Design
* LTSpice
* MATLAB
* Proteus
* PCB Design

---

# 📷 **PROJECT ARCHITECTURE**

> Add your charger schematic image here

```markdown
![Charger Schematic](images/charger_schematic.png)
```

---

# 🏆 **PROJECT HIGHLIGHTS**

⭐ 2kW Fast Charging Capability

⭐ High-Frequency Isolated SMPS Design

⭐ 67.2V / 30A Output

⭐ CC-CV Charging Algorithm

⭐ Industrial Charger Architecture Study

⭐ Ferrite Transformer Isolation

⭐ Practical EV Charger Analysis

⭐ Designed for Modern Electric Mobility

---

# 👨‍💻 **TEAM MEMBERS**

### Chaitanya Waghmare

### Purvesh Chudhari

### Deep Vaidya

### Ritesh Pail

**Department of Electrical Engineering**

**COEP Technological University, Pune**

---

# ⭐ **IF YOU LIKE THIS PROJECT, DON'T FORGET TO STAR THE REPOSITORY!**
