# MC68000 Visualizer

A web-based interactive visualizer for the **Motorola 68000 (MC68000) microprocessor**.  
Designed for educational purposes, this tool helps students understand the execution of instructions, memory operations, stack behavior, and register updates.

---

## Features

- **Step-by-step execution** of MC68000 assembly-like instructions.
- **Auto-play mode** to run programs continuously.
- **Visual memory grid** highlighting read and write operations.
- **Registers display** (D0-D7, A0-A7) with real-time updates.
- **Program code panel** showing all instructions, highlighting the current one.
- **Output screen** simulating TRAP #15 output.
- **Multiple example programs** demonstrating basic operations, loops, stack usage, LEA, and TRAP instructions.

---

## Example Programs

Some included example programs:

1. **Basic MOVE/ADD/SUB**
2. **Loop Addition**
3. **Stack Operations (PUSH/POP)**
4. **LEA Addressing**
5. **TRAP #15 Output**
6. **Sum Array**
7. **LEA with Array Loop**
8. **TRAP Display Loop**
9. **Stack PUSH/POP Example**
10. **Memory Copy Loop**
11. **Sum Memory Loop**

---

## Usage

1. Open `index.html` in a modern web browser.
2. Select an example program from the dropdown.
3. Click **Load Program** to initialize memory and registers.
4. Use **Step** to execute instructions one at a time.
5. Use **Auto Play** to run the program automatically.
6. Use **Reset** to clear memory and registers and start over.
7. Observe memory changes, register updates, and output in real-time.

---

## How it Works

- **Registers:** D0-D7 (data), A0-A7 (address/stack pointer)
- **Memory:** 128 cells, each displaying a numeric value.
- **Instructions Supported:**  
  `MOVE`, `ADD`, `SUB`, `PUSH`, `POP`, `MOVE_MEM_REG`, `MOVE_REG_MEM`, `ADD_IMM`, `SUB_IMM`, `LEA`, `BNE`, `BRA`, `TRAP #15`
- **Visualization:**  
  - Reads highlighted in **blue**, writes in **green**.  
  - Registers affected by the current instruction are highlighted in **orange**.  
  - The current instruction in the code panel is highlighted.

---

## Technology Stack

- HTML5 / CSS3
- JavaScript (ES6)
- No external libraries required

---

## Contributing

Feel free to fork this repository and add:

- More MC68000 instructions
- Larger example programs
- Customizable memory size
- Enhanced output visualization

---

## License

This project is **open-source** and available under the MIT License.