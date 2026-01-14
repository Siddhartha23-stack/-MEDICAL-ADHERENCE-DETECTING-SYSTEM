# -MEDICAL-ADHERENCE-DETECTING-SYSTEM
Verilog HDL based Drug Interaction Checker (Medical Adherence Detection System) with testbench waveform verification.

# Medical Adherence Detection System (Drug Interaction Checker) – Verilog HDL

This project is a **Medical Adherence Detection System** implemented using **Verilog HDL**, designed as a **Drug Interaction Checker**.  
The system detects unsafe combinations of medicines and generates status outputs (Safe_Flag /Unsafe_Flag) based on the input selection.

This was developed as part of a **Logic Design Laboratory / Digital Design mini-project** and verified using **testbench simulation waveforms**.

---

## 📌 Project Objective
To design a digital logic system that can **detect unsafe drug interactions** and help improve medication safety by identifying harmful combinations.

---

## ✅ Medicines Considered (Inputs)
The design uses 5 medicine input signals:

- **Paracetamol**
- **Alcohol**
- **Antihistamine**
- **Cough Syrup**
- **Metformin**

Each input is treated as a **binary signal (0/1)**:
- 1 → medicine taken/selected  
- 0 → medicine not taken

---

## ⚠️ Unsafe Drug Interactions Detected
The system flags these combinations as unsafe:

1. **Paracetamol + Alcohol**  
   → Risk of liver toxicity

2. **Antihistamine + Cough Syrup**  
   → Excessive drowsiness / central nervous system depression

3. **Metformin + Alcohol**  
   → Risk of lactic acidosis / hypoglycemia

---

## ✅ Outputs
The circuit generates two outputs:

- **Unsafe_Flag = 1** → Unsafe drug interaction detected  
- **Safe_Flag = 1** → No unsafe interaction detected  

✅ Output logic ensures correct response based on medicine combinations.

---

## 🛠️ Tools / Technologies Used
- **Verilog HDL**
- **Digital Logic Design (Combinational Logic)**
- **RTL Design**
- **Testbench**
- **Simulation Waveforms**
- (Tool used: ModelSim / Vivado / Quartus / any simulator)

---

## 📈 Verification
The design is verified using a **Verilog testbench** by applying multiple input combinations.  
Waveform simulation confirms:

- Unsafe combinations → Unsafe_Flag becomes HIGH  
- Safe combinations → Safe_Flag remains HIGH  

--------------------------------------------------------------------END
