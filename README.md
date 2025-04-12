# STM32 Bluetooth Firmware Tool 🔧📡

> A modern desktop utility to **upload firmware to STM32 microcontrollers** over **UART** and **Bluetooth (HC-05)**.  
> ✅ Built with **C++/Qt 6.8.2** — works on Windows (tested on Windows 11).  
> ❗ Requires **Microsoft Visual C++ Redistributable (MSVC 2022)** to run!

---

## ⚠️ Requirements

> Before launching the application, please ensure the following:

- ✅ **MSVC Redistributable for Visual Studio 2022**  
  https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist
  https://visualstudio.microsoft.com/vs/features/cplusplus/
- ✅ Windows 10 or 11 (64-bit)
- ✅ USB to UART adapter (e.g., FTDI)
- ✅ HC-05 Bluetooth module

---

## 📦 Download & Usage

> This project is precompiled — **no installation required**. Just download and run the executable.

1. Download the latest `.zip` file from [Releases](#)
2. Extract the archive
3. Run `Firmware Updater.exe`  
4. ✅ You're ready to go!

---

## STM32 Devices

Tested and verified on:

- STM32F030F4P6
- STM32F103C8T6
- STM32F411RE (Nucleo-64)
  
> Bootloader must be active (Boot0 pin set HIGH + Reset)

---

### 📡 Bluetooth (HC-05)

- Baudrate: **9600 (default)**  
- First, **pair the HC-05 module with your PC**  
- Then, select the COM port in the UI  
- Supported commands:
  - Get Commands
  - Get Chip ID
  - Get Version
  - Mass Erase
  - Flash Firmware

> ⚠️ Make sure the **PC Bluetooth is turned ON** before scanning.

---

## ❓ Troubleshooting

| Issues and Solutions |

| ❌ “Missing MSVC DLL” | Install MSVC Redistributable |
| ❌ Bluetooth not detected | Pair HC-05 with Windows first / Enter your PIN of Bluetooth Module |
| ❌ STM32 doesn’t respond | Check Boot0 HIGH, Reset, correct pins |
| ❌ NACK | Recheck baudrate/parity/settings |

---

## 📥 License

This project is **not open source**. You are free to use the compiled binary for non-commercial purposes.  
All rights reserved © 2025 Cem Y.

---

## 💼 Author

**Cem Y.**  
📧 cem.ylcin@gmail.com  
🔗 [LinkedIn] http://linkedin.com/in/cemylcin35 

---


