<div align="center">

# Arpan Chandra

### Electrical Engineering @ NIT Durgapur · Digital VLSI & RTL Design

Class of 2027 · Seeking front-end VLSI / RTL design roles and internships

[![GitHub](https://img.shields.io/badge/GitHub-Arpan060504-181717?style=for-the-badge&logo=github)](https://github.com/Arpan060504)
[![Email](https://img.shields.io/badge/Email-YOUR_EMAIL_HERE-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:arpangraphy@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-YOUR_HANDLE_HERE-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arpan-chandra-3078b8283/)

</div>

---

## About

I design digital hardware in Verilog and verify it with self-checking testbenches. My main work is AI-oriented datapaths: a floating-point softmax unit and a parameterized INT8 systolic array. I'm now adding the pieces my projects still lack: synthesis results, randomized verification, and measured numbers.

## Featured projects

### [FP32 Softmax Accelerator](https://github.com/Arpan060504/softmax-accelerator)
A synthesizable 4-input softmax datapath in IEEE-754 single precision, built from scratch: custom FP32 adder and multiplier, piecewise-linear exponential unit, LUT + Newton–Raphson reciprocal, and an FSM tying them together.

- **Verified:** reciprocal unit against 18 vectors, max error 0.092% (positive inputs only).
- **Limits:** fixed 4-wide, inputs restricted to [-4, 4], no max-subtraction stabilization.
- **Not done yet:** end-to-end accuracy vs. a float64 reference, standalone exp-unit testbench, synthesis numbers. No CPU/ISA integration exists; that is future work.

<sub>Verilog · FP32 arithmetic · FSM · Icarus Verilog</sub>

### [Parameterized INT8 Systolic Array](https://github.com/Arpan060504/rtl-int8-ai-accelerator)
Matrix-multiplication accelerator built up from a signed MAC to a processing element, a 2×2 array, an FSM controller, and a parameterized N×N array (`N`, `DATA_WIDTH`, `ACC_WIDTH`).

- **Verified:** self-checking testbench comparing RTL output against a software golden model.
- **Limits:** the array is parameterized, but the controller's streaming schedule is currently fixed to 2×2.
- **Not done yet:** generic controller, synthesis and cycle-count results across N.

<sub>Verilog · Systolic arrays · Generate constructs · Golden-model verification</sub>

### Other RTL blocks
[MIPS32 pipelined processor](https://github.com/Arpan060504/mips32-pipelined-processor) · [Parameterized integer ALU](https://github.com/Arpan060504/rtl-parameterized-integer-alu) · [Synchronous FIFO](https://github.com/Arpan060504/Verilog-Synchronous-FIFO) · [UART TX/RX](https://github.com/Arpan060504/Verilog_UART_TX_RX)

## Skills

| | |
|---|---|
| **Used in my projects** | Verilog, Icarus Verilog, GTKWave, Linux/WSL, Git, Python |
| **Learning (not yet applied in the projects above)** | SystemVerilog assertions and coverage, Yosys synthesis, OpenROAD |

## In progress

- [ ] Yosys synthesis of both flagship projects, with cell counts reported
- [ ] Softmax accuracy vs. float64 reference over random inputs
- [ ] Systolic array results (cells, cycles per matmul) for N = 2, 4, 8
- [ ] Randomized tests (cocotb) and CI regression via GitHub Actions

## Contact

- Email: YOUR_EMAIL_HERE
- LinkedIn: [YOUR_HANDLE_HERE](https://www.linkedin.com/in/YOUR_HANDLE_HERE)
- NIT Durgapur, Electrical Engineering, 2023–2027
