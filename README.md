# MINI-Project
Determining the Volume of Liquid Petroleum Gas (LPG) Using a Load Cell 
# Volume Measurement of Gas in LPG Using Load Cell  
 
This project presents a cost-effective and reliable method to measure the volume of LPG gas in a cylinder using load cells interfaced with an Arduino UNO and HX711 module. The system helps users continuously monitor the gas level and avoid sudden exhaustion of LPG.

---

## 🔍 Introduction
Liquefied Petroleum Gas (LPG) is widely used in households and industries across India. A common problem faced by users is not knowing when the gas cylinder will run out.  
This project proposes a **load cell-based measurement system** that continuously monitors the weight of an LPG cylinder, maps it to the remaining gas volume, and displays the information for the user.

---

## 🛠 Problem Statement
- Consumers are often unaware when the gas cylinder is about to get exhausted.  
- Current pressure-based measurement techniques are inaccurate due to temperature variations and gas composition differences.  
- Need for a **low-cost, reliable, and user-friendly** solution.  

---

## ⚙️ System Design
The system uses **4 half-bridge load cells** connected through an **HX711 ADC module** to an **Arduino UNO**. The weight data is processed and displayed as the percentage of gas remaining in the cylinder.

### Block Diagram
![Block Diagram] (https://github.com/DEV-Glitch-A/Mini-Project/blob/cf92b177dba203ff8d7c3288a142731db753c79e/assets/Block%20diagram.png?raw=true)


---

## 🔧 Components Used
- **Load Cell (50kg Half-Bridge) × 4**
- **HX711 Module × 1**
- **Arduino UNO × 1**
- **Gas Cylinder Holder × 1**
- **Wooden Base (13 cm radius) × 1**
- **Connecting Wires**
- **USB Data Cable**

---

## ⚡ Working
1. Load cells form a Wheatstone bridge arrangement.  
2. HX711 amplifies and digitizes the signal from the load cells.  
3. Arduino UNO receives and processes the signal.  
4. The system is calibrated with known weights to ensure accuracy.  
5. The output displays the **percentage of LPG remaining** in real-time.  

📌 [Arduino Code Here](https://github.com/DEV-Glitch-A/Mini-Project.git)  

---

## 📊 Results
- Successfully measured the gas weight and converted it to percentage volume.  
- Users can monitor gas levels in real-time and store the data in EEPROM for future analysis.  

---

## ✅ Conclusion and Future Scope
- Developed a cost-effective prototype to measure LPG volume using load cells.  
- Helps users know when to book a new cylinder in advance.  

### Future Enhancements
- Add **Wi-Fi module** for smartphone notifications.  
- Integrate into **Smart Home systems**.  
- Extend to **industrial boilers and hotels**.  
- Enable cloud-based **IoT monitoring** for large-scale usage.  

---

## 📚 References
- [HX711 Datasheet](https://pdf1.alldatasheet.com/datasheet-pdf/view/1132222/AVIA/HX711.html)  
- [IoT Based Gas Level Detection Research](https://www.researchgate.net/publication/342378827_An_Assessment_of_the_Level_of_Safety_Awareness_among_the_LPG_Consumers_in_Dhaka_City_Bangladesh)  
- [Load Cell Weight Sensor Tutorial](http://files.microjpm.webnode.com/200002653-90b4a92a93/Tutorial_for_Load_Cell_weight_sensor%2050KG.pdf)  

---

## 📌 Repository
> This repository contains the Arduino source code, documentation, and related resources for the project.  

---
