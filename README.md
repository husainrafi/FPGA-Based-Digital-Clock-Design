FPGA-Based Digital Clock Design

# Overview

This project implements a 24-hour Digital Clock (HH:MM:SS) using Verilog HDL and simulates the design on a laptop without requiring physical FPGA hardware.

The clock updates seconds, minutes, and hours using sequential logic and demonstrates concepts of digital design, counters, timing, and RTL simulation.

---

# Features

- 24-hour clock format
- Hours (00–23)
- Minutes (00–59)
- Seconds (00–59)
- Reset functionality
- RTL simulation support
- Waveform generation

---

# Project Architecture

Clock Input
↓
Clock Divider
↓
Second Counter
↓
Minute Counter
↓
Hour Counter
↓
Digital Display

---

# Tools Used

- Verilog HDL
- EDA Playground
- Icarus Verilog
- EPWave (Waveform Viewer)
- Xilinx Vivado (Optional)

---

# Project Structure

FPGA_Digital_Clock/

├── rtl/
│ └── digital_clock.v

├── tb/
│ └── tb_clock.v

├── waveform/

└── README.md

---

# How to Run

1. Open EDA Playground
2. Select Language → Verilog
3. Select Simulator → Icarus Verilog
4. Paste "digital_clock.v"
5. Paste "tb_clock.v"
6. Click Run
7. Open EPWave to view simulation waveform

---

# Expected Output

Time = 0:0:1
Time = 0:0:2
Time = 0:0:3

...

Time = 0:1:0

---

# Simulation Result

# The clock increments:

- Seconds from 00–59
- Minutes after every 60 seconds
- Hours after every 60 minutes
- Resets to 00:00:00 after 23:59:59

---

# Future Enhancements

- 12/24 Hour Mode
- Alarm Function
- Stopwatch
- Seven Segment Display
- FPGA Board Implementation
- Clock Divider Optimization

---

# Learning Outcomes

- Verilog HDL Coding
- Sequential Logic Design
- Counter Design
- Testbench Development
- RTL Simulation
- Waveform Analysis

---

# Author

shaikh husain rafi
Electronics and Communication Engineering
