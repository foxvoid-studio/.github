# Welcome to Foxvoid Studio

**Building the tools. Forging the games. Mastering the stack.**

Foxvoid Studio is an independent game development and software engineering laboratory. We do not just build games; we build the foundational technologies, engines, and cloud infrastructures that power them. 

Our philosophy is rooted in the **"Lab Approach"**: prioritizing deep technical mastery, custom-built architectures, and zero-compromise cross-platform deployment over off-the-shelf solutions.

---

## Our Philosophy
At Foxvoid Studio, we believe that understanding the machine at every layer—from low-level memory management to high-level cloud synchronization—is the ultimate path to engineering excellence. 
*   **No Black Boxes:** We build our own game engines instead of relying on generic giants. If a bug occurs, we fix it at the source code level.
*   **Write Once, Deploy Everywhere:** Every technology we build targets Native Desktop (Windows/Linux), Mobile (Android), and the Web (WebAssembly) seamlessly.
*   **Ecosystem Synergy:** Games do not exist in a vacuum. We develop the game client, the authoritative servers, and the web APIs as a single, unified ecosystem.

---

## The Engineering Laboratory

To support our creative vision, Foxvoid Studio develops and maintains its own proprietary technology stack across three different languages:

### Foxvoid Engine (C++ / Python)
A highly optimized, cross-platform 2D engine built in C++. 
* **Architecture:** Custom Entity Component System (ECS), SAT-based physics, and Virtual File System (VFS).
* **Scripting:** Seamless `pybind11` integration, allowing gameplay logic to be written rapidly in Python while heavy lifting is handled natively in C++.
* **Networking:** Agnostic transport layer (WebSockets/TCP) ready for authoritative headless server deployment.

### Elyria Engine (C# / .NET 8+)
A modern, 3D low-poly engine pushing the limits of the .NET ecosystem.
* **Architecture:** Unity-style Entity-Component (EC) architecture, prioritizing rapid gameplay iteration and intuitive object-oriented scripting. Engineered with zero-allocation hot paths where it matters most, leveraging `structs`, `Span<T>`, and Native AOT compilation to combat Garbage Collection latency.
* **Graphics & Physics:** Powered by Veldrid for cross-API rendering (Vulkan/D3D11/OpenGL ES), paired with JoltPhysicsSharp for highly multithreaded physical simulation.

### Foxvoid Cloud & SSO (Python / Django)
The backbone of our cross-platform experience, hosted on custom Proxmox LXC infrastructure.
* **Features:** Single Sign-On (SSO) for all Foxvoid games, cloud saves, cross-platform rewarded ad validation, and a custom CI/CD "One-Click Deploy" pipeline bridging the engines directly to the web.

---

## Current Roadmap & Projects

We enforce a strict **Scope Freeze** policy to balance our engineering ambitions with actual game releases. Our current trajectory:

* **Tappy Plane:** A technical WebAssembly validation demo to prove the Foxvoid Engine's web rendering and Python scripting pipeline.
* **The Commercial Clicker:** Our first production game. Designed with exponential mathematical loops to test player retention, SSO integration, and our cross-platform monetization architecture.
* **Project Elyria:** A 3D low-poly RPG currently in deep architectural development, serving as the flagship title for the Elyria Engine.

---

## Explore Our Architecture

Are you a developer curious about how we handle WebAssembly file systems, C# Zero-Allocation ECS, or hybrid WebSocket/QUIC netcode? 

We document every major technical decision we make. Dive into our **Architecture Decision Records (ADR)** to understand the *why* behind our code:

> **[Read the Foxvoid Studio Architecture Manifesto](https://github.com/foxvoid-studio/FoxvoidArchitecture)**

---
*Foxvoid Studio is proudly developed and maintained by [Ethan Rucar](https://github.com/ikigami0513).*
