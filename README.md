# Awesome-Reverse-Engineering-Binary-Disassembly

# Top Reverse Engineering & Binary Disassembly Ecosystem

**Curated List of SaaS/Proprietary Platforms & Open-Source GitHub Projects**  
*Focused on Disassemblers, Decompilers, Symbolic Execution, Binary Diffing, Dynamic Debuggers & AI Binary Analysis*  
**Last updated: November 2026**

This repository tracks notable **SaaS/proprietary commercial reverse engineering tools** and **open-source GitHub projects** for **Reverse Engineering & Binary Disassembly**. These tools enable security researchers, malware analysts, vulnerability researchers, and firmware engineers to disassemble machine code, decompile binaries back into high-level C/C++ pseudocode, trace execution dynamically, perform symbolic execution, and analyze mobile/embedded firmware.

**Examples** include Ghidra, Radare2, Rizin, Cutter, angr, RetDec, ImHex, x64dbg, Frida, Capstone, Binwalk, ioncodes/gecko, IDA Pro, Binary Ninja, JEB Decompiler, Hopper Disassembler, and RevEng.AI.

**Open-source emphasis**: This list heavily expands on active open-source multi-architecture decompilers, command-line/GUI disassembly frameworks, binary hex editors, dynamic instrumentation engines, and symbolic execution suites — ideal for malware analysts, CTF players, vulnerability researchers, and low-level systems engineers.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[IDA Pro & Hex-Rays Decompiler / IDA Cloud](https://hex-rays.com)**  
  The industry-standard commercial interactive disassembler and decompiler supporting dozens of processor architectures, Lumina cloud metadata sharing, and Python/C++ SDK scripting.

- **[Binary Ninja (Vector 35)](https://binary.ninja)**  
  Modern commercial reverse engineering platform featuring multi-level Intermediate Languages (LLIL/MLIL/HLIL), collaborative enterprise cloud sync, and an extensible Python/C++/Rust API.

- **[JEB Decompiler (PNF Software)](https://pnfsoftware.com)**  
  Commercial multi-architecture reverse engineering suite renowned for Android APK/DEX/native ARM decompilation alongside x86/x64, MIPS, and WebAssembly analysis.

- **[RevEng.AI](https://reveng.ai)**  
  Cloud-based AI binary analysis and reverse engineering platform using foundation models to identify similar functions, recover symbols, and detect vulnerabilities across compiled binaries.

- **[Hopper Disassembler](https://hopperapp.com)**  
  Commercial interactive disassembler, decompiler, and debugger for macOS and Linux tailored for x86, x64, and ARM/Apple Silicon binaries.

- **[Dogbolt (Decompiler Explorer)](https://dogbolt.org)**  
  Hosted web-based multi-decompiler comparison platform allowing researchers to upload binaries and compare side-by-side outputs from Ghidra, Hex-Rays, Binary Ninja, Angr, and RetDec.

- **[VMRay Analyzer & Joe Sandbox Cloud](https://vmray.com)**  
  Cloud malware analysis and automated dynamic binary detonation sandboxes providing deep function-call tracing and behavioral disassembly reports.


## Open-Source GitHub Projects

- **[Ghidra (NationalSecurityAgency/ghidra)](https://github.com)**  
  Flagship open-source software reverse engineering (SRE) suite developed by the NSA featuring a multi-architecture decompiler, collaborative Ghidra Server, P-Code IR, and Java/Python scripting.

- **[Radare2 (radareorg/radare2)](https://github.com)**  
  Portable, unix-like open-source reverse engineering framework and command-line disassembler, hex editor, debugger, and binary analyzer supporting virtually every CPU architecture.

- **[Rizin (rizinorg/rizin)](https://github.com)** & **[Cutter (rizinorg/cutter)](https://github.com)**  
  Modern, clean-architecture fork of Radare2 (`Rizin`) paired with `Cutter`, a free and open-source Qt-based GUI reverse engineering platform integrating Ghidra's decompiler.

- **[angr (angr/angr)](https://github.com)**  
  Powerful open-source Python binary analysis platform combining static analysis, dynamic symbolic execution, VEX IR lifting, and decompilation for automated vulnerability discovery.

- **[RetDec (avast/retdec)](https://github.com)**  
  Open-source retargetable machine-code decompiler based on LLVM supporting ELF, PE, Mach-O, COFF, and raw firmware across x86, ARM, MIPS, PowerPC, and PIC32.

- **[Gecko (ioncodes/gecko)](https://github.com)**  
  Open-source reverse engineering and binary analysis utility crafted for streamlined low-level inspection, disassembly, and binary exploration workflows.

- **[ImHex (WerWolv/ImHex)](https://github.com)**  
  Feature-rich, open-source hex editor engineered specifically for reverse engineers, featuring a custom C-like pattern language, built-in disassembler, data inspector, and YARA rules.

- **[x64dbg (x64dbg/x64dbg)](https://github.com)**  
  The premier open-source x64/x32 dynamic debugger for Windows featuring an integrated assembler/disassembler, Scylla import reconstructor, and rich plugin ecosystem.

- **[Frida (frida/frida)](https://github.com)**  
  Dynamic instrumentation toolkit allowing reverse engineers to inject JavaScript/C hooks into native apps on Windows, macOS, Linux, iOS, and Android in real time.

- **[Capstone (capstone-engine/capstone)](https://github.com)**, **[Keystone (keystone-engine/keystone)](https://github.com)** & **[Unicorn (unicorn-engine/unicorn)](https://github.com)**  
  The foundational open-source disassembly, multi-architecture assembler, and QEMU-based CPU emulator trio powering modern reverse engineering tools.

- **[Binwalk (ReFirmLabs/binwalk)](https://github.com)**  
  Fast, Rust-rewritten open-source firmware analysis tool for identifying, extracting, and reverse-engineering embedded filesystems and compressed blobs from binary images.

- **[Jadx (skylot/jadx)](https://github.com)**  
  Popular open-source Dex-to-Java decompiler with both CLI and GUI interfaces for inspecting Android APK, DEX, AAR, and Java bytecode binaries.

- **[ILSpy (icsharpcode/ILSpy)](https://github.com)** & **[dnSpyEx (dnSpyEx/dnSpy)](https://github.com)**  
  Essential open-source .NET assembly browsers, decompilers, and live binary debuggers for inspecting and patching C#/IL executables.

### Additional Strong Open-Source Options

- **[GDB (GNU Debugger)](https://sourceware.org)** with **[pwndbg](https://github.com)** / **[GEF](https://github.com)** — Enhanced open-source Linux dynamic debugging environments tailored for exploit development and binary reverse engineering.
- **[BinDiff / Diaphora (joxeankoret/diaphora)](https://github.com)** — Advanced open-source program diffing plugin for comparing patched vs. unpatched binaries to locate security fixes.
- **[Triton (JonathanSalwan/Triton)](https://github.com)** — Dynamic binary analysis (DBA) library providing taint analysis, symbolic execution, and SMT solver integration.
- **[Decompyle++ / pycdc (zrax/pycdc)](https://github.com)** & **[uncompyle6](https://github.com)** — Open-source Python bytecode (`.pyc`) disassemblers and decompilers.
- **[OBJDUMP / LLVM-Objdump / Readelf (llvm/llvm-project)](https://github.com)** — Foundational open-source command-line binary inspection and disassembly utilities for ELF, Mach-O, and COFF object files.
- **[RecStudio / Snowman / Reko (uxmal/reko)](https://github.com)** — Open-source multi-architecture decompiler written in C# supporting vintage and modern CPU instruction sets.

**Frameworks for building custom systems**: Combine **Ghidra** or **Cutter (Rizin)** for static decompilation with **x64dbg** / **pwndbg** + **Frida** for live dynamic instrumentation, **ImHex** for binary format parsing, and **Capstone + Unicorn + angr** for automated Python binary analysis pipelines.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- **Malware & Safety Notice**: Reverse engineering unknown or malicious binaries carries execution risks; always perform static and dynamic analysis inside isolated, snapshot-enabled virtual machines (`QEMU/KVM`, `VirtualBox`) with network egress disabled or routed through controlled analysis gateways (`INetSim`).
- Respect software licenses, anti-circumvention statutes, and responsible vulnerability disclosure policies when analyzing proprietary software or firmware.

---

**Made for reverse engineers, malware analysts, vulnerability researchers, CTF players, and low-level systems programmers.**  
Let's make binary disassembly, decompilation, and security research transparent, reproducible, and open to everyone.
