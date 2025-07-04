# CSE 2033 CT 4 Assignment - CPU Design

## Project Overview
This repository contains the implementation of a CPU designed as part of the CSE 2033 CT 4 Assignment (Roll No: 1903113). The CPU is built using **Logisim**, a digital logic simulation tool, based on the provided specifications. The project includes circuits for the ALU, Register Set, RAM, ISA, and the complete CPU, along with a demonstration video showcasing the CPU's functionality.

## Assignment Requirements
The CPU is designed with the following specifications:
- **Word Size of CPU**: 3 bits
- **ALU Operations**: NOT, ADD, ROL (Rotate Left)
- **Number of Registers**: 6
- **RAM Size**: 7 words
- **Word Size of ISA and RAM**: 17 bits
- **CPU Instructions**: 
  - Register Mode
  - Immediate Mode
  - Branching (JMP, JE)

## Repository Contents
This repository includes the following components:
1. **Logisim Circuit Files**:
   - **ALU Circuits**:
     - 3-bit Adder Circuit
     - 3-bit Rotate Left Circuit
     - 3-bit ALU Circuit
   - **Register Set Circuits**:
     - 3-bit Register Circuit
     - Top-level Register Set Circuit
   - **RAM Circuits**:
     - 1x1 RAM Circuit
     - 1x17 RAM Circuit
     - 7x17 RAM Circuit
   - **CPU Circuits**:
     - 3-bit Program Counter
     - 3-bit Add One Circuit
     - Control Unit
     - 3-bit CPU Circuit (Top-level with output pins for ALU, Register Set, and RAM)
2. **Instruction Set Architecture (ISA)**:
   - Definitions for Register Mode and Immediate Mode instructions
   - Sample machine code for testing the CPU
3. **Demonstration Video**:
   - A video showcasing the CPU running sample machine code, executing one instruction at a time.
   - Video Link: [Google Drive Link](https://drive.google.com/file/d/1HeJczZHHHeJ8BAnUJy1mZLIY4GcYSTylk/view?usp=drive_link)

## Tools Used
- **Logisim**: Used for designing and simulating all digital circuits (ALU, Register Set, RAM, and CPU).
- **Google Drive**: Used for hosting the demonstration video with appropriate permissions.

## How to Run the Project
1. **Install Logisim**:
   - Download and install Logisim from [Logisim's official site](http://www.cburch.com/logisim/) or a trusted source.
2. **Open Circuit Files**:
   - Clone this repository to your local machine.
   - Open the `.circ` files in Logisim to explore the circuits for ALU, Register Set, RAM, and CPU.
3. **Run Simulations**:
   - Load the sample machine code provided in the ISA section into the RAM circuit.
   - Simulate the CPU circuit in Logisim to verify its functionality.
   - Refer to the demonstration video for a step-by-step execution of the sample machine code.
4. **View Demonstration Video**:
   - Access the video via the provided [Google Drive link](https://drive.google.com/file/d/1HeJczZHHHeJ8BAnUJy1mZLIY4GcYSTylk/view?usp=drive_link) to see the CPU in action.

## Checklist Compliance
The project adheres to the assignment's checklist:
- **ALU Circuits**: Includes all required circuits except the Full Adder (as per instructions).
- **Register Set**: Includes all circuits from 1-bit Register to the top-level Register Set.
- **RAM**: Includes 1x1 RAM, 1x17 RAM, and 7x17 RAM circuits.
- **ISA**: Provides definitions for Register Mode and Immediate Mode, along with sample machine code.
- **CPU**: Includes Program Counter, Add One Circuit, Control Unit, and top-level CPU circuit with output pins for verification.
- **Video**: A demonstration video is provided to show the CPU executing the sample machine code.

## Notes
- Ensure all Logisim circuit files are opened in the correct order (bottom to top) to avoid dependency issues.
- The demonstration video is essential for verifying the CPU's functionality, as it shows the step-by-step execution of instructions.
- For any issues with the circuit files or video access, please check the file permissions or contact the repository owner.

## License
This project is for educational purposes only and is part of the CSE 2033 CT 4 Assignment submission.
