# Aver Engine - Core Binaries & Runtime

Welcome to the official precompiled binary repository for **Aver Engine**.

Aver Engine is a custom, high-performance C++ game engine designed for modern systems. It combines a low-level **Direct3D 12** rendering pipeline with a fast, zero-overhead **C# scripting interop** layer.

This repository hosts the compiled engine runtime DLLs, core executables, and D3D12 render pipeline baselines.

---

## 🚀 Starter Templates & Quick Start

Project templates and starter setups are maintained in a separate repository to keep your project setups isolated from core runtime updates.

👉 **Get Starter Templates:** [github.com/hydrogen-isotope/Aver-Engine-Templates](https://github.com/hydrogen-isotope/Aver-Engine-Templates)

### How to Run:
1. Clone or download the starter project from the [Aver-Engine-Templates](https://github.com/hydrogen-isotope/Aver-Engine-Templates) repository.
2. Download the latest release package from this repository's **Releases** tab.
3. Place the compiled engine runtime binaries into your template project's `Engine/Binaries/` directory.
4. Launch `AverEngine.exe` (or your template executable) to start testing.

---

## ⚡ Core Architecture Features

* **Native Direct3D 12 Execution:** Built from the ground up for low-overhead GPU command processing and consistent frame times.
* **Modern C# Interop:** Write high-level, expressive gameplay logic in C# while the C++ engine core handles raw rendering and hardware execution.
* **Lean Runtime Footprint:** No bloatware, invasive background services, or required third-party launchers.

---

## 💻 System Requirements

* **OS:** Windows 10 / 11 (64-bit)
* **GPU:** DirectX 12 compatible (Feature Level 12_0 or higher)
* **Runtime:** [.NET 8.0 Runtime or newer](https://dotnet.microsoft.com/)

---

## 🛠️ Feedback & Benchmarking

If you are testing frame times, checking memory allocation, or inspecting D3D12 execution passes:

* Please submit detailed reports on the [GitHub Issues](https://github.com/hydrogen-isotope/Aver-Engine/issues) tab.
* Include your **GPU model**, **driver version**, and **frame time metrics (ms)** with your feedback.

---

## 📜 License
Usage of these binaries is governed by the [Aver Engine EULA](LICENSE.md) included in this repository.
