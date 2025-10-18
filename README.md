# ⚙️ Full Adder in VHDL (ModelSim Simulation)

## 📘 Overview
This project implements a **Full Adder** circuit using **VHDL** and simulates it in **ModelSim**.  
A Full Adder performs binary addition on **three single-bit inputs** (A, B, Cin) and produces **Sum** and **Carry** outputs.

---

## 🎯 Objective
To design and verify a **Full Adder** using VHDL and confirm its functionality through simulation in ModelSim.

---

## 🧠 Theory
A **Full Adder** adds three binary inputs — two significant bits (**A**, **B**) and one carry input (**Cin**) — and generates a **Sum** and a **Carry** output.

The logical equations are:
- **SUM = A XOR B XOR Cin**  
- **CARRY = (A AND B) OR (B AND Cin) OR (A AND Cin)**

| A | B | Cin | SUM | CARRY |
|:-:|:-:|:---:|:---:|:------:|
| 0 | 0 | 0 | 0 | 0 |
| 0 | 0 | 1 | 1 | 0 |
| 0 | 1 | 0 | 1 | 0 |
| 0 | 1 | 1 | 0 | 1 |
| 1 | 0 | 0 | 1 | 0 |
| 1 | 0 | 1 | 0 | 1 |
| 1 | 1 | 0 | 0 | 1 |
| 1 | 1 | 1 | 1 | 1 |

---

## 🧰 Software and Language
- **Software:** ModelSim — for simulation and waveform analysis  
- **Language:** VHDL (IEEE STD_LOGIC_1164) — for circuit design and testbench creation

---

## 📊 Simulation Result
✅ The waveform confirms correct operation of the Full Adder circuit.  
- **SUM** = High when an odd number of inputs are high.  
- **CARRY** = High when two or more inputs are high.  

