# Principles of Embedded Systems

> 🚧 **Work in Progress**

## Course Description

This course gives a concept-first introduction to the architecture, design and software stack of application-specific computing systems. You will explore the divergence between general-purpose computing and constrained embedded environments, then trace how execution happens across the whole system stack: silicon hardware blocks, memory maps, layered software and firmware, and the toolchain that turns high-level code into machine code.

The course is concept-driven, with short guided labs on real hardware (NUCLEO-F411RE). It builds the structural mental models you need to analyze, design and reason about embedded hardware-software co-design before moving on to full hands-on deployment.

| | |
|---|---|
| **Intended audience** | Second/third-year undergraduates, hobbyists, aspiring and junior embedded systems engineers |
| **Prerequisites** | Introduction to Computer Science; Digital Logic / Basic Computer Architecture (recommended); basic C programming (recommended) |
| **Hardware** | NUCLEO-F411RE (optional for early modules) |

## Course Structure

| Module | Title | Focus |
|---|---|---|
| 1 | Paradigms of Computing | General-purpose vs. application-specific; the constraint model |
| 2 | Embedded Hardware Architectures | MPU vs. MCU, Von Neumann vs. Harvard, CISC vs. RISC, memory mapping |
| 3 | The Embedded Software Stack | Layers, boundaries and the Hardware Abstraction Layer |
| 4 | The Build Pipeline & Toolchains | Cross-compiler, assembler, linker, locator |
| 5 | Source to Silicon (The Blinky Paradigm) | C, assembly and hex; what the MCU does during a toggle |

## Course Learning Objectives

By the end of this course you will be able to:

1. **Differentiate** general-purpose and embedded systems using design constraints: power, size, cost, reliability and deterministic execution.
2. **Compare** microprocessors (MPUs) and microcontrollers (MCUs) structurally, economically and operationally, and compare Harvard and Von Neumann architectures.
3. **Map** how a microcontroller organizes its memory spaces (flash, RAM, peripherals) using memory mapping and register boundaries.
4. **Deconstruct** the embedded software stack by identifying the roles, boundaries and communication paths of hardware, drivers, middleware, firmware and application software.
5. **Trace** the compilation pipeline, explaining how the cross-compiler, assembler, linker and locator turn C code into an executable binary.
6. **Translate** a conceptual application (a "Blinky" routine) between C, assembly syntax and machine hex code, and explain its execution flow.
