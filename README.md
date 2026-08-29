# Power-Aware Low-Power Domain Design with UPF

## Project Overview

🔗 **GitHub Live Repository:** 
https://github.com/Tanu1092/powerawarelowpowerdomaindesignwithUPF
This project demonstrates a power-aware digital system using Verilog HDL and Unified Power Format (UPF). The project focuses on low-power design concepts such as power domains, power management, and isolation.

## Objectives

- Understand low-power VLSI design concepts.
- Design digital logic using Verilog HDL.
- Define power domains using UPF.
- Understand isolation and power-state management.
- Verify the power-aware design using a testbench.

## Technologies Used

- Verilog HDL
- Unified Power Format (UPF)
- Simulation and verification tools
- Visual Studio Code
- GitHub

## Project Structure

```text
PowerAwareLowPowerDomainDesignwithUPF/
├── alu.v
├── tb_alu.v
├── README.md
├── .gitattributes
├── Project_Presentation.pptx
├── Project_Report.pdf
└── PowerAware_Source_Code.zip
```

## Low-Power Design Concept

The design uses power domains to control the power consumption of different parts of the circuit. When a power domain is switched off, isolation logic can be used to prevent invalid or unknown signals from affecting an active domain.

UPF is used to describe the power intent, including power domains, supply networks, isolation, and power states.

## Verification

The Verilog testbench is used to apply input combinations and check the expected outputs. Power-aware behavior can also be evaluated during different power states.

## Expected Outcome

The project demonstrates how Verilog HDL and UPF can be combined to create and verify a power-aware low-power digital design.

## Conclusion

This project provides practical understanding of low-power digital design, power domains, isolation, and UPF-based power-intent specification.
