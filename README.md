<h1 align="center">Hi, I'm Ernst Reidinga 👋</h1>

<p align="center">
  <strong>Software Engineer · Cloud & Web · Runtime & Compiler Engineering · Embedded Systems</strong>
</p>

<p align="center">
  I build software across the stack — from virtual machines, compilers and embedded systems<br>
  to desktop applications, developer tooling and connected hardware.
</p>

<p align="center">
  <a href="https://erdesigns.be">Website</a> ·
  <a href="https://erdesigns.be/playground">ERD-TSVM Playground</a> ·
  <a href="https://erdesigns.be/blog">Engineering Journal</a>
</p>

---

## 👨‍💻 About me

I'm a software engineer from Belgium with a strong interest in understanding and building systems from the ground up.

My work spans high-level web and cloud applications, SaaS platforms and frontend development, all the way down to runtime architecture, compiler design, virtual machines, embedded systems and hardware integration.

I enjoy building complete systems rather than isolated pieces: designing the architecture, implementing the low-level foundations, creating the developer tooling around them, and making the result approachable enough for others to build upon.

Some of the areas I work in:

* Runtime & virtual machine architecture
* Compiler engineering
* Embedded systems and microcontrollers
* TypeScript / JavaScript language tooling
* C++ systems programming
* Delphi / Object Pascal
* Developer tooling and IDEs
* Industrial IoT and automation
* Hardware/software integration
* Networking and connected devices

---

# 🚀 ERD-TSVM

One of my largest ongoing projects is **ERD-TSVM**, a complete TypeScript execution platform consisting of an AOT compiler, bytecode format, virtual machine, runtime, debugger and development toolchain.

The goal is to make it possible to write modern TypeScript and execute the same application architecture across constrained embedded devices, desktop systems, servers and WebAssembly.

```text
TypeScript
    │
    ▼
 Lexer / Parser
    │
    ▼
Semantic Analysis
    │
    ▼
 Type Checking
    │
    ▼
  Optimizer
    │
    ▼
Code Generator
    │
    ▼
 ERD Bytecode
    │
    ▼
   ERD-TSVM
    │
    ├── ESP32 / FreeRTOS
    ├── Linux
    ├── macOS
    ├── Windows
    └── WebAssembly
```

### Some of the platform features

* TypeScript and modern ECMAScript support
* Self-hosted TypeScript compiler
* Ahead-of-time compilation
* Compact register-based bytecode VM
* Generational garbage collector
* Hidden classes / object shapes
* Inline caches
* Multi-pass optimizer
* Async/await, generators and promises
* Standard library implemented through native runtime modules
* DAP-compatible debugging
* Bytecode disassembler
* Heap snapshots
* ESP32 hardware APIs
* Desktop and server targets
* WebAssembly runtime
* OTA deployment and embedded tooling

ERD-TSVM is **not open source yet**. The project is currently being developed towards its first public release, with the intention of **open-sourcing the platform in 2027**.

In the meantime, architecture documentation, technical articles, platform information and a working browser playground are already publicly available.

👉 **[Explore ERD-TSVM](https://erdesigns.be/platform)**
👉 **[Technical architecture](https://erdesigns.be/stack)**
👉 **[Try the ERD-TSVM Playground](https://erdesigns.be/playground)**
👉 **[Read the engineering journal](https://erdesigns.be/blog)**

---

## Open-source projects

I maintain several open-source Delphi projects covering automotive diagnostics, hardware integration, custom VCL components and connected devices.

Some of them are pinned below, including **Delphi-OBD**, **HID Macro Keyboard**, **Delphi Inspector** and **Philips Hue**.

👉 [Browse all repositories](https://github.com/erdesigns-eu?tab=repositories)

---

# 🔧 Technologies

I don't really define my work by a fixed technology stack — the technology depends on what layer of the system I'm working on.

**Languages**

`C++` · `TypeScript` · `JavaScript` · `Delphi / Object Pascal` · `C` · `WebAssembly` · `PHP` · `Python`

**Web & Cloud**

`SaaS` · `Web Applications` · `REST APIs` · `HTTP` · `WebSockets` · `Docker` · `Cloud Infrastructure` · `MongoDB` · `Authentication` · `Multi-tenant Applications`

**Runtime & Compiler**

`VM Architecture` · `Bytecode` · `AOT Compilation` · `Garbage Collection` · `Language Semantics` · `Optimization`

**Embedded**

`ESP32` · `ESP-IDF` · `FreeRTOS` · `GPIO` · `I²C` · `SPI` · `UART` · `BLE` · `WiFi`

**Application Development**

`Node.js` · `TypeScript` · `React` · `Vue` · `Meteor` · `VCL` · `Native Desktop`

**Systems & Tooling**

`CMake` · `DAP` · `VS Code` · `Docker` · `Linux` · `macOS` · `Windows`

---

# 🧠 Engineering interests

I'm particularly interested in the boundary between high-level developer experience and low-level system design.

A lot of my work revolves around one question:

> **How much low-level complexity can we hide without giving up control, determinism or performance?**

That applies equally to a TypeScript VM running on a microcontroller, a compiler toolchain, an embedded hardware API or a Delphi component.

I like systems where developers can start at a high level, but where every layer underneath remains understandable and accessible.

---

# 🌐 ERDesigns

**ERDesigns** is where I publish my larger engineering projects, experiments and technical documentation.

The main focus is currently on embedded runtimes, compiler engineering, developer tooling and industrial IoT.

🌍 **https://erdesigns.be**

There you'll find:

* ERD-TSVM architecture and documentation
* The online TypeScript playground
* Embedded projects
* Technical articles
* Runtime and compiler development updates
* Industrial IoT projects
* Downloads and tooling

---

<p align="center">
  <strong>From idea to impact.</strong>
</p>

<p align="center">
  <a href="https://erdesigns.be">erdesigns.be</a>
</p>
