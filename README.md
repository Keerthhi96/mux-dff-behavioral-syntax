# 📘 Verilog RTL Designs: D Flip-Flop & 4:1 Multiplexer

This repository contains basic RTL design implementations in Verilog:
- ✅ D Flip-Flop (DFF) with reset
- ✅ 4:1 Multiplexer (MUX)

These are fundamental building blocks for digital design and VLSI systems.

---

## 🔹 1. D Flip-Flop (DFF)

### 📌 Description
A **D Flip-Flop** captures the value of input `d` on the **rising edge of the clock (`clk`)** and stores it in output `q`.  
It includes a **reset** signal to initialize the output.

### ⚙️ Features
- Edge-triggered (`posedge clk`)
- Synchronous reset
- Uses **non-blocking assignment (`<=`)**

