# MIPS Single-Cycle Processor – CprE 381 Project Part 1
This project implements a single-cycle MIPS processor using structural VHDL. It was developed as part of the CprE 381 course at Iowa State University.

## 📁 Project Structure
├── src # VHDL source files\
├── test # Testbench files\
├── mips/ # MIPS assembly test programs\
├── Proj1_report.pdf # Final project report\
├── submit.zip # Auto-generated project submission\
└── README.md # Project documentation\


## 🛠 Features
The processor supports the following MIPS instructions:
add, addi, addiu, addu, and, andi, lui, lw, nor, xor, xori, or, ori, slt, slti,
sll, srl, sra, sw, sub, subu, beq, bne, j, jal, jr, lb, lh, lbu, lhu, sllv, srlv, srav

### Core Components
- **Instruction Fetch Unit**
- **Control Unit (with control logic spreadsheet)**
- **32-bit ALU (with logical & arithmetic shifts)**
- **Register File**
- **Memory System (byte addressable)**
- **Testbenches for all modules**

## 🧪 Testing
All components and the full processor were tested using the automated test framework (`381_tf.sh`) and QuestaSim.

### Assembly Tests:
- `Proj1_base_test.s`: Tests all arithmetic and logic instructions
- `Proj1_cf_test.s`: Tests all control-flow instructions (with call depth ≥ 5)
- `Proj1_bubblesort.s`: Implements Bubble Sort algorithm

## 💻 Synthesis
The processor was synthesized to an Altera DE2 FPGA using Quartus. The report includes:
- Maximum clock frequency
- Critical path analysis
- Suggestions for optimization


