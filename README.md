# Learn-SecByte-CTF-Labs-Collection-Windows-Linux-Internals-Assembly-Lab-Setup-Practice
A curated collection of hands-on cybersecurity CTF labs covering Safe Malware Handling, Analysis Lab Setup, x86/x64 Assembly, CPU Registers, Windows &amp; Linux Internals, and OS Fundamentals from Learn SecByte.
# Learn SecByte CTF & Cybersecurity Labs Collection

Welcome to the **Learn SecByte CTF & Cybersecurity Labs Collection**. This repository is a structured, searchable index of hands-on safe malware handling, secure lab setup, assembly language, computer architecture, and low-level OS internals labs designed for cybersecurity students, CTF players, malware analysts, reverse engineers, and security researchers.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Building low-level technical proficiency in processor execution, assembly language instructions, and operating system kernel internals is vital for malware reverse engineering and security research. Hosted on [Learn SecByte](https://learn.secbyte.org/), this collection of CTF challenge labs provides foundational and structural training across core engineering domains.

From configuring isolated malware analysis environments and practicing operational security (OpSec) for sample detonation, to mastering x86/x64 assembly language, register states, CPU architecture, Windows/Linux process and thread internals, and Win32 API mechanics, these exercises establish the mandatory groundwork for binary investigation.

---

## Lab Collection & Index

Below is the complete, searchable index of all lab setup, assembly, computer architecture, and OS internals challenges in this collection:

| # | Lab / Challenge Name | Category | Focus / Key Topics | Lab Link |
|---|----------------------|----------|---------------------|----------|
| 1 | **Process and Thread Internals: Inside the Living Program** | OS Internals | EPROCESS/ETHREAD structures, TEB/PEB layout, process creation lifecycle, thread contexts | [Access Lab](https://learn.secbyte.org/ctf/process-and-thread-internals-inside-the-living-program) |
| 2 | **Linux Internals Fundamentals** | OS Internals | System calls (syscalls), task_struct, kernel vs. user space, file descriptor tables | [Access Lab](https://learn.secbyte.org/ctf/linux-internals-fundamentals) |
| 3 | **Windows Internals Fundamentals** | OS Internals | Executive subsystems, Kernel Object Manager, Security Access Tokens, NTDLL interface | [Access Lab](https://learn.secbyte.org/ctf/windows-internals-fundamentals) |
| 4 | **Windows API Fundamentals: The Beacon Trace** | API & OS Fundamentals | Win32 API calls (`VirtualAlloc`, `CreateProcess`, `InternetOpen`), API logging, DLL resolution | [Access Lab](https://learn.secbyte.org/ctf/windows-api-fundamentals-the-beacon-trace) |
| 5 | **x64 Assembly Programming: Reverse Engineering a Memory Corruption** | Assembly & Reversing | 64-bit architecture, FASTCALL calling convention, register arguments (RCX, RDX, R8, R9), stack alignment | [Access Lab](https://learn.secbyte.org/ctf/x64-assembly-programming-reverse-engineering-a-memory-corrup) |
| 6 | **x86 Assembly Language Fundamentals** | Assembly & Reversing | 32-bit registers (EAX, EBX, ESP, EBP), instruction set basics (`mov`, `push`, `pop`, `jmp`, `call`), stack frames | [Access Lab](https://learn.secbyte.org/ctf/x86-assembly-language-fundamentals) |
| 7 | **CPU Registers and Memory Fundamentals** | Architecture & Low-Level | General-purpose registers, EFLAGS/RFLAGS register, stack frame pointers, memory layout | [Access Lab](https://learn.secbyte.org/ctf/cpu-registers-and-memory-fundamentals) |
| 8 | **Computer Architecture Essentials: Firmware Leak** | Architecture & Low-Level | CPU instruction cycles, memory hierarchies, bus architectures, firmware storage layout | [Access Lab](https://learn.secbyte.org/ctf/computer-architecture-essentials-firmware-leak) |
| 9 | **Linux Fundamentals for Malware Analysts** | OS Fundamentals | POSIX file permissions, process handling, shell scripts, environment variables, Linux services | [Access Lab](https://learn.secbyte.org/ctf/linux-fundamentals-for-malware-analysts) |
| 10 | **Windows Fundamentals for Malware Analysts** | OS Fundamentals | Windows Directory structure, System32 assets, environment variables, core services | [Access Lab](https://learn.secbyte.org/ctf/windows-fundamentals-for-malware-analysts) |
| 11 | **Safe Malware Handling and Operational Security** | OpSec & Environment | Sample isolation, password-protected ZIP staging, hash logging, operational safety precautions | [Access Lab](https://learn.secbyte.org/ctf/safe-malware-handling-and-operational-security) |
| 12 | **Building a Secure Malware Analysis Lab** | OpSec & Environment | Hypervisor isolation, network host-only/fake-net routing, snapshot management, REMnux/Flare-VM pairing | [Access Lab](https://learn.secbyte.org/ctf/building-a-secure-malware-analysis-lab) |

---

## Categories

### 1. OpSec, Safe Handling & Lab Environment Setup
Establish secure, isolated sandbox environments and implement operational safety protocols for handling malicious software.
- [Safe Malware Handling and Operational Security](https://learn.secbyte.org/ctf/safe-malware-handling-and-operational-security)
- [Building a Secure Malware Analysis Lab](https://learn.secbyte.org/ctf/building-a-secure-malware-analysis-lab)
- [Windows Fundamentals for Malware Analysts](https://learn.secbyte.org/ctf/windows-fundamentals-for-malware-analysts)
- [Linux Fundamentals for Malware Analysts](https://learn.secbyte.org/ctf/linux-fundamentals-for-malware-analysts)

### 2. Assembly Language, Registers & Computer Architecture
Master low-level machine execution models, CPU register structures, memory layouts, and 32-bit/64-bit assembly instructions.
- [Computer Architecture Essentials: Firmware Leak](https://learn.secbyte.org/ctf/computer-architecture-essentials-firmware-leak)
- [CPU Registers and Memory Fundamentals](https://learn.secbyte.org/ctf/cpu-registers-and-memory-fundamentals)
- [x86 Assembly Language Fundamentals](https://learn.secbyte.org/ctf/x86-assembly-language-fundamentals)
- [x64 Assembly Programming: Reverse Engineering a Memory Corruption](https://learn.secbyte.org/ctf/x64-assembly-programming-reverse-engineering-a-memory-corrup)

### 3. Operating System & Subsystem Internals
Deconstruct Windows and Linux operating system internals, process/thread management structures, and kernel-mode interactions.
- [Windows Internals Fundamentals](https://learn.secbyte.org/ctf/windows-internals-fundamentals)
- [Linux Internals Fundamentals](https://learn.secbyte.org/ctf/linux-internals-fundamentals)
- [Process and Thread Internals: Inside the Living Program](https://learn.secbyte.org/ctf/process-and-thread-internals-inside-the-living-program)
- [Windows API Fundamentals: The Beacon Trace](https://learn.secbyte.org/ctf/windows-api-fundamentals-the-beacon-trace)

---

## Learning Path

Follow this structured progression path to build core technical prerequisites for malware analysis and binary reverse engineering:

1. **Phase 1: Lab Safety, OpSec & OS Foundations** — Configure secure analysis sandboxes and understand core OS components:
   - [Safe Malware Handling and Operational Security](https://learn.secbyte.org/ctf/safe-malware-handling-and-operational-security)
   - [Building a Secure Malware Analysis Lab](https://learn.secbyte.org/ctf/building-a-secure-malware-analysis-lab)
   - [Windows Fundamentals for Malware Analysts](https://learn.secbyte.org/ctf/windows-fundamentals-for-malware-analysts)
   - [Linux Fundamentals for Malware Analysts](https://learn.secbyte.org/ctf/linux-fundamentals-for-malware-analysts)

2. **Phase 2: Architecture, Registers & Assembly** — Understand CPU hardware mechanics and learn x86/x64 assembly instructions:
   - [Computer Architecture Essentials: Firmware Leak](https://learn.secbyte.org/ctf/computer-architecture-essentials-firmware-leak)
   - [CPU Registers and Memory Fundamentals](https://learn.secbyte.org/ctf/cpu-registers-and-memory-fundamentals)
   - [x86 Assembly Language Fundamentals](https://learn.secbyte.org/ctf/x86-assembly-language-fundamentals)
   - [x64 Assembly Programming: Reverse Engineering a Memory Corruption](https://learn.secbyte.org/ctf/x64-assembly-programming-reverse-engineering-a-memory-corrup)

3. **Phase 3: OS Internals & Subsystems** — Explore kernel structures, process lifecycle, and low-level OS management:
   - [Windows Internals Fundamentals](https://learn.secbyte.org/ctf/windows-internals-fundamentals)
   - [Linux Internals Fundamentals](https://learn.secbyte.org/ctf/linux-internals-fundamentals)
   - [Process and Thread Internals: Inside the Living Program](https://learn.secbyte.org/ctf/process-and-thread-internals-inside-the-living-program)

4. **Phase 4: API Mechanics & Execution Tracing** — Audit Win32/Native API calls and trace execution flows:
   - [Windows API Fundamentals: The Beacon Trace](https://learn.secbyte.org/ctf/windows-api-fundamentals-the-beacon-trace)

---

## How to Use the Labs

1. Select a challenge link from the index or category sections above.
2. Read the scenario directives and target exercises provided on [Learn SecByte](https://learn.secbyte.org/).
3. Use hypervisors (VMware, VirtualBox), disassemblers (Ghidra, IDA Free), debuggers (x64dbg, gdb), and system tools (Process Hacker, WinDbg) inside a secure sandbox.
4. Trace register changes, inspect PEB/TEB kernel structures, decompile assembly routines, verify API call sequences, and retrieve challenge flags.

---

## Disclaimer

This repository and its linked challenge resources are strictly intended for educational, threat research, and authorized technical training purposes. Never detonate, handle, or analyze live malware samples outside a dedicated, hypervisor-isolated lab environment.
