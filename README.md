<div align="center">

# 👋 Hi there, I'm Abdelrahman Adwe Ali
### 🚀 Digital IC Design & Design Verification (DV) Engineer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdelrhman-adwe/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abdelrahmanadwe@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/abdelrahmanadwe)

<p align="center">
  <b>🎓 B.Sc. in Electronics & Electrical Communications Engineering, Al-Azhar University</b><br>
  <b>🏆 Ranked 2nd in Class (Excellent with Highest Honors)</b><br>
  <b>🥉 3rd Place Winner at the Egypt Semiconductor Challenge 2026</b>
</p>

</div>

---

### 👨‍💻 About Me

I am a passionate **Digital IC Design and Advanced Verification (DV) Engineer** with a strong foundation across the full digital ASIC/FPGA development flow. My experience spans high-level microarchitectural specification, synthesizable RTL implementation, bus fabric interconnects, coverage-driven verification using **UVM**, and physical FPGA bring-up.

- 🎓 **Education:** Graduated **2nd in class with Highest Honors** from Al-Azhar University (Department of Electronics & Electrical Communications Engineering).
- 🏆 **Achievement:** Awarded **3rd Place at the Egypt Semiconductor Challenge 2026** (University Innovation Summit) for the digital design, UVM verification, and FPGA bring-up of the **UCIe 3.0 PHY Layer**.
- 🔬 **Technical Passions:** Computer Architecture, Pipelined Microprocessors, High-Speed Die-to-Die Interconnects (UCIe, Chiplets), Advanced UVM Testbench Architecture, and HW/SW Co-Design.

---

### 🛠 Tech Stack & Engineering Skills

<table>
  <tr>
    <td align="center" width="25%"><b>HDL & RTL Design</b></td>
    <td>SystemVerilog, Verilog, RTL Design, FSM Design, Microarchitecture, Pipelined CPU Datapath & Control, Logic Synthesis</td>
  </tr>
  <tr>
    <td align="center" width="25%"><b>Design Verification (DV)</b></td>
    <td>UVM (1.1d / 1.2), SystemVerilog OOP, UVM RAL, Virtual Sequences/Sequencers, SVA Assertions, Constrained-Random Stimulus, Functional & Code Coverage Closure</td>
  </tr>
  <tr>
    <td align="center" width="25%"><b>Buses & Protocols</b></td>
    <td>UCIe 3.0 (Die-to-Die PHY), AMBA AHB-Lite, AMBA APB (v2.0), AMBA AXI4, AXI4-Stream, SPI, UART, I2C</td>
  </tr>
  <tr>
    <td align="center" width="25%"><b>Processor Architecture</b></td>
    <td>5-Stage Pipeline, Hazard Detection & Forwarding, Dynamic Branch Prediction (BTB), Coprocessor 0 (CP0) Exceptions & Interrupts</td>
  </tr>
  <tr>
    <td align="center" width="25%"><b>FPGA & Embedded</b></td>
    <td>Xilinx Vivado, IP Integrator, Zynq UltraScale+ MPSoC (ZCU104), Embedded C, AMD Vitis, Bare-metal Drivers, HW/SW Co-Design, DMA</td>
  </tr>
  <tr>
    <td align="center" width="25%"><b>EDA Tools & Concepts</b></td>
    <td>Siemens QuestaSim, Questa Lint, Synopsys Design Compiler, Static Timing Analysis (STA), Clock Domain Crossing (CDC/RDC)</td>
  </tr>
  <tr>
    <td align="center" width="25%"><b>Scripting & OS</b></td>
    <td>TCL (verification & simulation automation), Python, Bash, Makefile, Git & GitHub, Linux/Unix Environment</td>
  </tr>
</table>

<div align="center">
  <br>
  <img src="https://img.shields.io/badge/SystemVerilog-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Verilog-2C3E50?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/UVM-E67E22?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/TCL-196F3D?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/Xilinx%20Vivado-D1381B?style=flat-square&logo=xilinx&logoColor=white"/>
  <img src="https://img.shields.io/badge/QuestaSim-005A9C?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
</div>

---

### ⭐ Featured Projects

#### 🔹 [UCIe 3.0 PHY Layer — Digital Design, UVM & FPGA Bring-up](https://github.com/AbdallahMoSalah/UCIe-3.0-PHY-layer)
> **Graduation Project | 🥉 3rd Place Winner at Egypt Semiconductor Challenge 2026**
- Implemented the Sideband subsystem of the UCIe 3.0 Logical PHY with multi-source pipeline arbitration (Priority & Round-Robin) and back-pressure valid-ready flow control.
- Synthesized using **Synopsys Design Compiler** targeting **1.0 GHz** for Mainband & MainSM, and **100 MHz** for Sideband.
- Developed a dual-die (Local & Partner) multi-agent **UVM testbench** with Register Abstraction Layer (RAL) and LTSM coverage, achieving **100% functional coverage**.
- Prototyped on a **Xilinx Zynq UltraScale+ MPSoC at 250 MHz**; authored AXI-Stream bridges and bare-metal C drivers in **Vitis** to walk the PHY to **ACTIVE** and validate 512-bit flit DMA streaming.

#### 🔹 [MIPS32 Pipelined SoC with AHB-Lite Matrix & APB Subsystem](https://github.com/abdelrahmanadwe/MIPS32_SoC)
> **Synthesizable 32-bit System-on-Chip (Microcontroller Architecture)**
- Architected a synthesizable 32-bit 5-stage pipelined MIPS core with an integrated **Hazard Unit** (RAW forwarding, load-use stalls).
- Integrated a 1024-entry **Branch Target Buffer (BTB)** with 2-bit saturating counters for zero-bubble branch execution, plus **Coprocessor 0 (CP0)** for vectored exceptions and hardware interrupts.
- Designed on-chip **AHB-Lite bus matrix**, a hazard-free **AHB-to-APB bridge**, 32 KB 4-bank synchronous BRAM (`byte_we[3:0]`), ARM CMSDK GPIO & Timer, and integrated custom APB UART.
- Validated through an automated regression suite of 11 assembly programs against a golden single-cycle reference.

#### 🔹 [APB-Compliant Configurable UART IP & Complete UVM Verification](https://github.com/abdelrahmanadwe/UART)
> **Production-Grade Serial IP with AMBA APB v2.0 Bus Interface**
- AMBA APB v2.0 compliant UART transceiver with programmable baud rates (up to 115.2 kbps+), variable data widths (5–8 bits), parity modes, and stop bits.
- Memory-mapped CSRs featuring an STM32-style consolidated STATUS register, 6 dedicated level/edge interrupt lines + global IRQ, hardware write-gating, and Data Overrun (DOR) detection.
- Complete **UVM 1.1d verification testbench** featuring APB and serial agents, interrupt-aware scoreboard, concurrent SVA assertions, and **100% Functional & Code Coverage**.

#### 🔹 [SPI Protocol Design & Hierarchical UVM Verification](https://github.com/abdelrahmanadwe/SPI-slave-with-single-port-RAM)
> **Hierarchical UVM Verification with Passive Agent Reuse**
- Verilog RTL implementation of an SPI slave controller integrated with single-port synchronous RAM.
- Reusable hierarchical UVM verification environment configuring dedicated SPI slave and RAM agents as passive in the top wrapper environment for non-intrusive protocol checking and **100% functional coverage**.

#### 🔹 [Synchronous FIFO Design & Verification](https://github.com/abdelrahmanadwe/Sync-FIFO-Design-and-Verification)
> **Synthesizable FIFO & Full Verification Environment**
- Parameterizable FIFO RTL design verified using class-based SystemVerilog and complete UVM testbenches with SVA assertions for full/empty corner-case validation.

---

### 📊 GitHub Activity & Stats

<div align="center">
  <img height="165" src="https://github-readme-stats-fjlm.vercel.app/api?username=abdelrahmanadwe&show_icons=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&icon_color=3fb950&border_color=30363d" alt="GitHub Stats"/>
  <img height="165" src="https://github-readme-streak-stats-three-sand.vercel.app?user=abdelrahmanadwe&background=0d1117&ring=58a6ff&fire=3fb950&currStreakLabel=58a6ff&sideLabels=c9d1d9&currStreakNum=58a6ff&sideNums=c9d1d9&dates=8b949e&border=30363d" alt="GitHub Streak"/>
</div>

---

### 📬 Connect with Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdelrhman-adwe/)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abdelrahmanadwe@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/201093980406)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/abdelrahmanadwe)

<br>
<i>"Perfection is achieved, not when there is nothing more to add, but when there is nothing left to take away."</i>
</div>
