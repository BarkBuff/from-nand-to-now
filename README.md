# ⚙️ from-nand-to-now

**A full 16-bit computer system, built from first principles — from NAND gates to a working compiler.**  
This is my journey through the legendary [NAND2Tetris](https://www.nand2tetris.org/) project — implemented, debugged, and documented end-to-end.

---

## 🚀 Overview

`from-nand-to-now` walks through the entire computing stack, layer by layer.  
Starting with a single NAND gate, I built up all the way to a working operating system and high-level programming language.

This repo is more than coursework — it's a systems engineering story in code.

---

## 🔧 What’s Inside

### 🧱 Hardware (HDL)
- Primitive logic gates (AND, OR, XOR, etc.)
- Multiplexers, adders, ALU
- Memory modules: RAM, Registers, Program Counter
- 16-bit CPU and full computer architecture

### 🧠 Software Stack
- **Assembler**: Converts Hack assembly into binary machine code
- **Virtual Machine (VM)**: Stack-based VM translator (written in [Your Language])
- **Compiler**: Jack → VM translation pipeline
- **Operating System**: Math, Memory, I/O libraries to support high-level programs

---

## 🧪 Key Concepts

- Hardware Description Language (HDL)
- Instruction set design & assembly
- Virtual machine design & stack-based architecture
- Recursive descent parsing & compiler construction
- OS abstractions and runtime support

---

## 🛠️ How to Run

> Requires [Nand2Tetris software suite](https://www.nand2tetris.org/software) for HDL simulation and program testing.

Clone the repo and run `.hdl` files using the supplied hardware simulator.

```bash
git clone https://github.com/BarkBuffer404/from-nand-to-now.git
