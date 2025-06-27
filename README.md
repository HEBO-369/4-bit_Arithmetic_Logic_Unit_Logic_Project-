# 🧮 4-Bit Arithmetic Logic Unit (ALU)

This project implements a simple **4-bit Arithmetic Logic Unit (ALU)** using digital logic gates. Designed in **Logisim**, it performs arithmetic, logical, and bitwise operations based on a 4-bit opcode input and provides result flags for specific operations.

## 📥 Inputs
- **A, B**: Two 4-bit operands.
- **Opcode**: 4-bit control code that selects the operation.

## 📤 Outputs
- **8-bit result** of the operation.
- **Status flags**:
  - **Zero (Z) Flag**
  - **Carry/Borrow (C) Flag**
  - **Overflow (O) Flag**

## ⚙️ Supported Operations

| Type      | Opcode | Operation               |
|-----------|--------|-------------------------|
| Arithmetic| 0000   | A + B                   |
|           | 0001   | A - B                   |
|           | 0010   | B - A                   |
|           | 0011   | A * B                   |
| Logic     | 0100   | A AND B                 |
|           | 0101   | A OR B                  |
|           | 0110   | A XOR B                 |
|           | 0111   | A NAND B                |
| Bitwise   | 1000   | Two's Complement of A   |
|           | 1001   | One's Complement of A   |
| Shifts    | 1010   | Logical Left Shift A    |
|           | 1011   | Logical Right Shift A   |
|           | 1100   | Arithmetic Left Shift A |
|           | 1101   | Arithmetic Right Shift A|
| Rotations | 1110   | Circular Left Shift A   |
|           | 1111   | Circular Right Shift A  |

## 📄 Deliverables
- ✔️ Truth Tables  
- ✔️ Minimization Steps  
- ✔️ Logisim Circuit Diagrams  

## 👥 Team Members
- **Mohamed Wahban**  
- *Karim Basem*
- *Omar Ahmed*
- *Mohamed Abdallah*
- *Mohamed Gomaa*
## 🛠️ Tools Used
- [Logisim](http://www.cburch.com/logisim/) (Digital Logic Simulator)
## 👨‍💻 Author
**Mohamed Wahban**  
Computer Engineering & Systems Department  
Faculty of Engineering, Alexandria University  
GitHub: [HEBO-369](https://github.com/HEBO-369)

---
