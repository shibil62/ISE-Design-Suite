# ISE Project Navigator — Educational Recreation

> A browser-based educational recreation of a digital design development environment inspired by traditional FPGA and Verilog development workflows.

![HTML](https://img.shields.io/badge/HTML5-Web%20Application-orange?style=for-the-badge&logo=html5)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla%20JS-yellow?style=for-the-badge&logo=javascript)
![Verilog](https://img.shields.io/badge/Verilog-Simulation-purple?style=for-the-badge)
![Educational](https://img.shields.io/badge/Purpose-Educational-green?style=for-the-badge)

---

## 📌 Overview

**ISE Project Navigator — Educational Recreation** is a browser-based recreation of a classic digital logic development environment.

The project provides an interactive workspace where users can explore a simplified workflow involving:

- Digital design projects
- Verilog source code
- Code editing
- Compilation-style feedback
- Simulation
- Console output
- Digital waveform visualization

The application is designed primarily as an **educational tool** for students learning Verilog and digital system design.

---

## ✨ Features

### 📁 Project Workspace

- Project-style navigation
- Design hierarchy
- Process panel
- Source file workflow
- Interactive project structure

### 📝 Verilog Code Editor

- Built-in code editing interface
- Line numbering
- Syntax highlighting
- Verilog-oriented editing environment
- Cursor position tracking

### ⚙️ Verilog Support

The project includes a simplified Verilog parser and simulator designed for educational experimentation.

Supported concepts include:

- Modules
- Inputs and outputs
- Wires and registers
- Continuous assignments
- Procedural assignments
- `initial` blocks
- `always` blocks
- Conditional statements
- Basic expressions
- Delays
- Clock-based logic

---

## 🧪 Included Digital Logic Experiments

The application includes reference implementations for several common digital electronics experiments.

### 🔀 Combinational Logic

- 4:1 Multiplexer
- 1:4 Demultiplexer
- 4-to-2 Encoder
- 2-to-4 Decoder

### 🔢 Display Logic

- Seven-Segment Display

### 🔄 Sequential Logic

- D Flip-Flop
- Synchronous Counter

---

## 📊 Simulation Environment

The application includes an integrated simulation workspace featuring:

- Instance navigation
- Object inspection
- Simulation controls
- Signal monitoring
- Waveform visualization
- Simulation timeline controls

This allows users to observe how digital signals change over time.

---

## 🖥️ Interface Components

The recreation includes several familiar development-environment concepts:

### 🗂️ Design Panel

Used for:

- Project hierarchy
- Source navigation
- Process management

### 📝 Editor

Provides:

- Source editing
- Syntax highlighting
- Line numbers
- Verilog code support

### 💻 Console

Displays:

- Console messages
- Errors
- Warnings
- Information

### 📈 Simulation View

Provides:

- Signal lists
- Object values
- Waveform visualization
- Simulation output

---

## 🛠️ Technologies Used

This project is built entirely with standard web technologies.

- **HTML5**
- **CSS3**
- **Vanilla JavaScript**
- **Canvas API**

No frameworks or external dependencies are required.

---

## 🚀 Getting Started

### Run Locally

1. Clone the repository:

```bash
git clone https://github.com/your-username/ise-project-navigator-recreation.git
```

2. Navigate to the project folder.

3. Open:

```text
index.html
```

in a modern web browser.

No installation or additional setup is required.

---

## 🧑‍💻 Basic Workflow

### 1. Create or Open a Project

Start by creating a project and adding a source module.

### 2. Write Verilog

Use the built-in editor to create or modify Verilog source code.

Example:

```verilog
module and_gate(
    input A,
    input B,
    output Y
);

assign Y = A & B;

endmodule
```

### 3. Run a Process

Use the available process controls to execute the simulation workflow.

### 4. Review Output

Check the console for:

- Errors
- Warnings
- Information
- Simulation messages

### 5. Open the Simulation View

Inspect signals and observe waveform behaviour over time.

---

## 📂 Project Structure

```text
ISE-Project-Navigator/
│
├── index.html
│
└── README.md
```

The application is currently packaged as a lightweight, self-contained browser application.

---

## 🎓 Educational Purpose

This project is intended to help students understand the general workflow of digital hardware design and simulation.

It can be useful for learning:

- Verilog fundamentals
- Combinational logic
- Sequential circuits
- Digital system design
- Hardware simulation concepts
- Waveform analysis
- FPGA development workflows

---

## ⚠️ Important Disclaimer

This project is an **independent educational recreation**.

It is **not affiliated with, endorsed by, or associated with AMD, Xilinx, or any official FPGA development software vendor**.

The application is intended purely for educational and demonstration purposes and should not be considered a replacement for professional FPGA development tools.

---

## 🔮 Future Improvements

Possible future additions include:

- Support for more Verilog constructs
- Additional simulation features
- More advanced waveform controls
- Project import/export
- Multiple source files
- Improved syntax highlighting
- Additional digital logic experiments
- Enhanced error reporting
- Improved mobile compatibility

---

## 👨‍💻 Author

**Shibil P A**

Created as an educational project focused on digital logic, Verilog, and hardware simulation concepts.

---

## 📄 License

This project is intended for educational and learning purposes.

Feel free to explore the code, learn from it, and build upon the project with appropriate attribution.

---

⭐ **If this project helped you learn something, consider giving the repository a star!**
