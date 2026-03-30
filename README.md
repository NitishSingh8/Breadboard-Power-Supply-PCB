#  Breadboard Power Supply PCB Design

##  Project Overview
This project focuses on designing a **Breadboard Power Supply Module PCB** that provides a stable and regulated DC output for breadboard-based electronic prototyping.

The PCB is compact and designed to directly interface with a standard breadboard, making it suitable for testing and developing electronic circuits.

---
##  Motivation
Breadboards require a stable and portable power source. 
This project was designed to create a compact and efficient 
solution for powering circuits during prototyping.


##  Objectives
- Design a reliable and compact power supply for breadboard use
- Implement proper PCB layout techniques
- Generate manufacturing-ready files (Gerber, Drill)
- Validate the design using 3D visualization

---

## Tools Used
- **KiCad** (Schematic & PCB Design)
- PCB Viewer (3D Visualization)

---

##  Technical Specifications
- PCB Type: Breadboard Compatible Power Module
- Layers: 2-Layer PCB (Top & Bottom)
- Copper Layers: F.Cu & B.Cu
- Ground Plane: Copper Zone Filled
- Output: Regulated DC Supply
- File Outputs: Gerber Files, Drill Files, Manufacturing Report

---

##  Electrical Design Details
- Input Voltage: (e.g., 7V–12V DC)
- Output Voltage: (e.g., 5V regulated)
- Voltage Regulator Used: (e.g., 7805 / AMS1117)
- Filtering Capacitors: (value)
- Protection: (if any diode/fuse used)

  ---
  
  ##  Working Principle
The input DC voltage is regulated using a linear voltage regulator. 
Capacitors are used for filtering and стабlizing the output voltage. 
The regulated output is provided to breadboard rails for circuit prototyping.

---

##  Design Workflow
1. Schematic Design
2. Footprint Assignment
3. PCB Layout Design
4. Component Placement Optimization
5. Routing (F.Cu & B.Cu Layers)
6. Copper Zone Filling (Ground Plane)
7. 3D Visualization (Front & Back)
8. Gerber File Generation

---

##  Project Files
- `/Schematic` → Circuit design files
- `/PCB Layout` → PCB design files
- `/Gerber` → Manufacturing files
- `/Images` → PCB images (3D, layout, schematic)

---

##  Project Preview

### 🔹Schematic
<img width="1172" height="805" alt="image" src="https://github.com/user-attachments/assets/5c67d305-2dee-4161-a561-035ef16a5718" />


### 🔹 PCB Layout (Zone Filled)
<img width="215" height="359" alt="Screenshot 2026-03-08 141918" src="https://github.com/user-attachments/assets/6012a2f1-a66f-4208-9c0b-db04ae9626bb" />


### 🔹 3D View (Front)
<img width="988" height="679" alt="Screenshot 2026-03-08 140249" src="https://github.com/user-attachments/assets/4f4cb9b8-8c32-44bf-898e-0ab90d5be9d0" />


### 🔹 3D View (Back)
<img width="1029" height="762" alt="Screenshot 2026-03-08 140150" src="https://github.com/user-attachments/assets/b15d3b60-3a90-4b23-b760-27124ce84a82" />


### 🔹 Top Layer (F.Cu)
<img width="211" height="363" alt="Screenshot 2026-03-08 141444" src="https://github.com/user-attachments/assets/09fa3059-9b39-4a8c-9f65-6b321001db52" />


### 🔹 Bottom Layer (B.Cu)
<img width="243" height="359" alt="Screenshot 2026-03-08 141359" src="https://github.com/user-attachments/assets/291adc6c-42a8-4118-bd5b-dce76c89cd62" />

---

##  Bill of Materials (BOM)

| Component | Value | Quantity |
|----------|------|----------|
| Voltage Regulator | 7805 | 1 |
| Capacitor | 10uF | 2 |
| Capacitor | 0.1uF | 2 |
| LED | - | 1 |
| Resistor | 330Ω | 1 |

---

## 🔍 Applications
- Powering Arduino / microcontroller circuits
- Breadboard prototyping
- Testing analog and digital circuits

  ---
  
##  Key Features
- Compact and breadboard-friendly design
- Clean and optimized PCB routing
- Ground plane for improved stability
- Manufacturing-ready design outputs

---

##  Skills Demonstrated
- PCB Design
- Schematic Capture
- Component Placement
- Routing Techniques
- Design for Manufacturing (DFM)

---

##  Future Improvements
- Add adjustable voltage output
- Include current limiting protection
- Improve efficiency with switching regulators

---

##  Feedback
Feel free to suggest improvements or provide feedback!

---

## Author
**Nitish Singh**  
Electronics & Communication Engineer  
