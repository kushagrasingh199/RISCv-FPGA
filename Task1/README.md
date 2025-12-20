# Task-1: Environment Setup and RISC-V Reference Validation

This repository documents the setup of the development environment and the successful validation of a RISC-V reference program using the Spike simulator, along with initial VSD FPGA lab tasks.

---

##  Environment

- **Platform:** GitHub Codespaces  
- **Operating System:** Linux  

The development environment was configured and verified successfully in GitHub Codespaces.

---

##  RISC-V Reference Program

- **Repository:** `vsd-riscv-v2`  
- **Program Path:** `samples/`  

### Description
A reference RISC-V program was compiled and executed using the Spike simulator to validate the toolchain and environment setup.

### Execution Result
- **Status:** Successfully compiled and executed  
- **Simulator:** Spike  
- **Output:**
  ```text
  Sum from 1 to 9 is 45
<img width="1918" height="915" alt="C coding " src="https://github.com/user-attachments/assets/63faa350-aeaf-43f7-aa24-6e2ab394844e" />
output using gcc

<img width="1918" height="1013" alt="Code run in VNC" src="https://github.com/user-attachments/assets/e6ba27c5-93b8-421e-bb55-9ff72cdff1e0" />

output using spike has also been verified

terminal novnc has been activated for a session and change in program done using GEDIT command in Command window

<img width="1910" height="1018" alt="change in code VNC" src="https://github.com/user-attachments/assets/12e6afc6-fb11-4980-9c9f-3b9c56292e49" />

### Step 3: VSDFPGA Labs Execution
- Cloned `vsdfpga_labs` repository inside the same Codespace.
- Executed the `basicRISCV` lab:
  - Generated BRAM hex from firmware
  - Integrated firmware with RTL
  - Completed simulation-based build successfully
- No FPGA hardware tools were used.
the hex code has been seen in the output

<img width="1911" height="912" alt="make bram hex" src="https://github.com/user-attachments/assets/be2e7a73-c30c-4017-aa2b-fb283dd19f7b" />

The banner pattern was added to the RISC-V firmware source using nano and executed using the Spike ISA simulator, with the output displayed on the terminal.

<img width="1917" height="967" alt="FPGA output" src="https://github.com/user-attachments/assets/842f250d-d1f6-4b14-94e1-522bb2ba853b" />

## Reference Repositories
- RISC-V Reference: https://github.com/vsdip/vsd-riscv2
- FPGA Labs: https://github.com/vsdip/vsdfpga_labs

---

## Proof of Execution
Screenshots and logs are available in the `Task1` directory.

---









