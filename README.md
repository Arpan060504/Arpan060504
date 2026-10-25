<div align="center">

# Arpan Chandra

### Electrical Engineering @ NIT Durgapur
**Digital VLSI | RTL Design | AI Hardware Acceleration**

B.Tech, Class of 2027

[![GitHub](https://img.shields.io/badge/GitHub-Arpan060504-181717?style=for-the-badge&logo=github)](https://github.com/Arpan060504)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:arpangraphy@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Arpan_Chandra-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arpan-chandra-3078b8283/)

</div>

---

## About

I'm an Electrical Engineering undergraduate at **NIT Durgapur**, graduating in 2027, with a focus on digital hardware design, RTL development, and AI-oriented hardware acceleration.

My work includes Verilog-based datapaths and control logic, an IEEE-754 single-precision softmax accelerator, a parameterized INT8 systolic array for matrix multiplication, and a pipelined MIPS32 processor. I use simulation and self-checking testbenches to debug designs and compare RTL behavior against reference models.

I'm interested in **RTL Design, digital hardware development, and Design Verification** opportunities in the semiconductor industry.

## Featured Projects

### FP32 Softmax Accelerator

[**View Repository →**](https://github.com/Arpan060504/softmax-accelerator)

A Verilog implementation of a four-element softmax datapath using custom floating-point arithmetic units and an FSM-based controller.

- Implemented custom IEEE-754 single-precision floating-point addition and multiplication units.
- Developed a piecewise-linear exponential approximation.
- Implemented reciprocal computation using a lookup table and Newton–Raphson refinement.
- Integrated the arithmetic units into a sequential softmax datapath.
- Tested the reciprocal unit against 18 reference vectors, with a reported maximum error of 0.092% for positive test inputs.

**Design scope:** Four-element datapath with inputs restricted to [-4, 4]. Maximum-subtraction stabilization and comprehensive end-to-end accuracy validation are not yet implemented.

`Verilog` · `FP32 Arithmetic` · `Datapath Design` · `FSM` · `Icarus Verilog`

### Parameterized INT8 Systolic Array Accelerator

[**View Repository →**](https://github.com/Arpan060504/rtl-int8-ai-accelerator)

A modular matrix-multiplication accelerator developed from a signed multiply-accumulate (MAC) unit to a processing-element array and parameterized N×N architecture.

- Designed a signed MAC datapath and processing element.
- Integrated processing elements into a 2×2 systolic array.
- Developed an FSM-based controller and a parameterized array using Verilog generate constructs.
- Built a self-checking testbench comparing RTL results against a software golden model.
- Organized the design into reusable modules for scalable hardware development.

**Design scope:** The array is parameterized, while the controller's streaming schedule remains fixed to the 2×2 implementation.

`Verilog` · `Signed Arithmetic` · `MAC Datapath` · `Systolic Arrays` · `Golden-Model Verification`

### MIPS32 Pipelined Processor

[**View Repository →**](https://github.com/Arpan060504/mips32-pipelined-processor)

A Verilog implementation exploring processor datapath organization, instruction execution, control logic, and pipelined architecture.

- Implemented a pipelined MIPS32 processor.
- Developed and integrated processor datapath and control components.
- Used simulation to debug and evaluate RTL behavior.

`Verilog` · `Computer Architecture` · `Pipelining` · `Processor Datapath`

## Additional RTL Projects

- [**Parameterized Integer ALU**](https://github.com/Arpan060504/rtl-parameterized-integer-alu) — Configurable arithmetic and logic operations.
- [**Synchronous FIFO**](https://github.com/Arpan060504/Verilog-Synchronous-FIFO) — Synchronous buffering and read/write control.
- [**UART TX/RX**](https://github.com/Arpan060504/Verilog_UART_TX_RX) — Serial communication logic implemented in Verilog.

## Technical Skills

| Category | Skills |
|---|---|
| RTL Design | Verilog, combinational and sequential logic, finite-state machines, parameterized modules, generate constructs |
| Digital Design | Processor datapaths, pipelining, ALUs, MAC units, FIFOs, UART, systolic arrays |
| Arithmetic & Hardware Acceleration | Fixed-width signed arithmetic, FP32 datapaths, matrix-multiplication architectures |
| Verification | Self-checking testbenches, directed testing, software golden-model comparison |
| Simulation & Debugging | Icarus Verilog, GTKWave |
| Development Tools | Git, GitHub, Linux, WSL, Python |
| Synthesis & Physical Design | Yosys, OpenROAD |

## Experience

### Electrical Engineering Intern — Reliance Industries Limited
**Electrical Division | RRTF, Jamnagar**

Worked on industrial power distribution system analysis and optimization, including transformer and feeder loading analysis, fault studies, motor-starting impact assessment, and redundancy evaluation across 33 kV, 6.6 kV, and 415 V distribution networks.

This experience provided exposure to industrial electrical systems, power distribution, and reliability-focused engineering analysis.

## Contact

- **Email:** [arpangraphy@gmail.com](mailto:arpangraphy@gmail.com)
- **LinkedIn:** [Arpan Chandra](https://www.linkedin.com/in/arpan-chandra-3078b8283/)
- **GitHub:** [Arpan060504](https://github.com/Arpan060504)

**NIT Durgapur · Department of Electrical Engineering · Class of 2027**
