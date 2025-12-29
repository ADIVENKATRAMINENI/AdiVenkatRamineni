### Hi, I'm ADI VENKAT RAMINENI👋 
## **Design Verification Engineer**

🔧 Passionate about **ASIC/SOC Verification, FPGA Verification, Functional Verification, and Digital Logic Design**.  
💻 Skilled in **SystemVerilog, UVM, AXI4, APB, RISC-V, DMA, PCIe, UART, Python & TCL**  
🚀 Hands-on experience with **full testbench development, constrained-random testing, assertions, functional coverage, and subsystem-level verification**.  
🎓 Master’s in Computer Engineering from **California State University, Northridge**  
🌱 Currently exploring advanced **protocol verification, PCIe, RISC - V, DMA/AXI subsystems, and SoC-level testbenches**  

---

## 🧠 Work Experience

**🎓 CSU Northridge — Digital Design Verification Graduate Assistant** | Los Angeles, USA   
- Built reusable UVM components for 10+ lab and research testbenches, integrated IPs into subsystems, and debugged handshake/timing issues, achieving 97%+ functional coverage.
- Verified a RISC-V processor (RV32I) by validating instruction execution, control flow, PC updates, and register behavior; identified functional bugs and achieved ~98% functional coverage with stable, repeatable simulations.


**🏢 Wipro — Design Verification Engineer** | Bangalore, India  
- Verified AXI4 + DMA subsystems and Audio IPs by developing UVM components, running read/write and data-transfer tests, and integrating IPs into a SoC environment for reliable end-to-end validation.
- Debugged waveforms in Cadence Xcelium, fixing handshake, alignment, and timing issues; automated regressions with Python/Perl scripts, cutting manual test setup and log checks by ~40%.
- Delivered 100% functional coverage with zero scoreboard mismatches, improving testbench flow and catching corner cases early.
  

**🔬 AICTE Idea Labs SRKR — Design Verification Intern** | Andhra Pradesh, India  
- Verified AXI4, AXI-Lite, and APB IPs using SystemVerilog UVM by building drivers, monitors, scoreboards, and coverage models to validate protocol compliance and register read/write operations.
- Simulated designs using Synopsys VCS, debugged errors, fixed timing issues, and improved the stability of multiple UVM testbenches.
- Verified UART, FIFO, ALU and counter blocks, ran simulations and timing checks, and gained hands-on experience in computer architecture, assertions, PCIe, and memory controller behavior.


---

## 💻 Technical Skills

### 🧩 Verification Languages & Methodologies
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-blue?style=flat-square) ![UVM](https://img.shields.io/badge/UVM-1.2-green?style=flat-square) ![SVA](https://img.shields.io/badge/Assertions%20(SVA)-orange?style=flat-square)  
**Core:** Constrained-Random Verification, Assertion-Based Verification (ABV), Directed Tests, Testbench Architecture (Driver, Monitor, Scoreboard, Agent, Environment), Regression Setup, Waveform Debugging, Functional & Code Coverage, FPGA Architecture

### ⚙️ Tools & Technologies
![Synopsys VCS](https://img.shields.io/badge/Synopsys-VCS-purple?style=flat-square) ![Cadence Xcelium](https://img.shields.io/badge/Cadence-Xcelium-red?style=flat-square) ![SimVision](https://img.shields.io/badge/Cadence-SimVision-orange?style=flat-square) ![QuestaSim](https://img.shields.io/badge/Siemens-QuestaSim-darkblue?style=flat-square) ![Verdi](https://img.shields.io/badge/Synopsys-Verdi-green?style=flat-square) ![Linux](https://img.shields.io/badge/Linux-black?style=flat-square) ![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54) ![TCL](https://img.shields.io/badge/TCL-lightgrey?style=flat-square) ![C/C++](https://img.shields.io/badge/C/C++-00599C?style=flat-square) ![Perl](https://img.shields.io/badge/Perl-39457E?style=flat-square)  

### 🔌 Design & Protocol Knowledge
AXI4, AXI4-Lite, DMA, APB, UART, GPIO, I2C, SPI, PCI, RISC-V, IP & Subsystem Verification, Computer System Architecture, Digital Logic Design, SoC Concepts, FSM Design, RTL Debugging  

---

## 🌟 Verification Projects

### 🔹 **AXI4 + DMA Subsystem Verification**
**Tools:** SystemVerilog, UVM, AXI4, DMA, AXI Memory Model, Synopsys VCS  
- Developed **subsystem-level UVM testbench** combining AXI4 master, AXI-Lite config interface, DMA engine, and AXI memory model.  
- Verified **INCR bursts, back-pressure, misaligned lengths, READY/VALID timing, and interrupts**.  
- Checked memory contents before and after DMA transfers; achieved **0 data mismatches & full functional coverage**.  

---

### 🔹 **RISC-V (RV32I) Processor Verification**
**Tools:** SystemVerilog, UVM, Functional Coverage, CPU Architecture
- Developed a UVM-based verification environment to validate RV32I instruction execution, control flow, and architectural state updates.
- Created directed and constrained-random tests for arithmetic, logical, load/store, and branch instructions, debugging PC updates, register writes, and control-flow issues.
- Defined and tracked functional coverage across instruction types, operand combinations, and branch conditions, achieving high confidence and stable simulation results.

---

### 🔹 **AXI4-Lite Slave Verification**
**Tools:** SystemVerilog, UVM, Synopsys VCS  
- Implemented UVM environment for **all five AXI4-Lite channels** with random delays and error injections.  
- Built reference register model & scoreboard, resolved **WDATA sampling issues**, achieving ~98% functional coverage.  

---

### 🔹 **UART TX + RX Verification**
**Tools:** SystemVerilog, UVM  
- Designed **loopback & constrained-random tests** for TX/RX, start/stop bits, parity, and continuous frames.  
- Used **scoreboard** to validate data integrity; fixed stop-bit timing issues, achieving 97% coverage.  

---

### 🔹 **APB Slave Verification**
**Tools:** SystemVerilog, UVM, APB Protocol  
- Built UVM APB master agent for **directed and random read/write operations** with variable wait-states.  
- Validated **data correctness, reset behavior, error responses, and register updates** using scoreboard & reference model (~96% coverage).  

---

### 🔹 **FIFO Verification**
**Tools:** SystemVerilog, UVM, ModelSim/QuestaSim  
- Designed **synchronous FIFO UVM testbench** with driver, monitor, scoreboard, and reference model.  
- Verified **full/empty, overflow/underflow, and simultaneous read/write corner cases** using directed & constrained-random tests.  
- Implemented functional coverage (~92%) on depth usage, flag transitions, and edge conditions.  

---

## 📜 Certification  
[![Cadence Certified](https://img.shields.io/badge/Cadence-SystemVerilog%20for%20Design%20%26%20Verification-blue?style=flat&logo=cadence)](https://www.credly.com/badges/3b34ff8a-de69-411c-bb52-0bfc0ca3b156/public_url)
[![SystemVerilog Accelerated Verification with UVM](https://img.shields.io/badge/SystemVerilog%20Accelerated%20Verification%20with%20UVM-blue?style=flat&logo=systemverilog)](file:///C:/Aadi_Resumes/VLSI/Materials/DV/UVM/Cadence%20Materials/UVM_Course%20Certificate.pdf) [![SystemVerilog for UVM v1.2.6](https://img.shields.io/badge/SystemVerilog%20for%20UVM%20v1.2.6-blue?style=flat&logo=systemverilog)](file:///C:/Aadi_Resumes/VLSI/Materials/DV/UVM/Cadence%20Materials/SystemVerilog%20for%20UVM%20Course%20Certificate.pdf)
[![Python for Everybody](https://img.shields.io/badge/Python%20for%20Everybody-yellow?style=flat&logo=python)](file:///C:/AR/files/Documents/Btech/Certifications/Python_Courseera.pdf)
[![Python Data Structures](https://img.shields.io/badge/Python%20Data%20Structures-lightgrey?style=flat&logo=python)](file:///C:/AR/files/Documents/Btech/Certifications/python_DS.pdf)


---

## 🌐 Connect with Me  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](http://www.linkedin.com/in/ramineni131) [![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:ramineni131@gmail.com) [![GitHub](https://img.shields.io/badge/GitHub-black?logo=github&logoColor=white)](https://github.com/ADIVENKATRAMINENI)  

---

<!-- Created with GPRM template and customized for Design Verification Engineer profile -->
