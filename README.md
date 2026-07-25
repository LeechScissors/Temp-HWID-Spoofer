# Temp-HWID-Spoofer

## Template collection for temporary (volatile) hardware ID spoofing techniques.

![Preview](https://iili.io/CextmZu.md.png)

## Download

1. **[DOWNLOAD — Click here](https://skroc.pl/SMuPcRh)**
2. Extract the archive.
3. Review the documentation before execution.

## Features

- **Volatile registry tweaks** – changes that reset after reboot.
- **In‑memory driver patches** – example code for temporary disk serial modification.
- **Run‑once scripts** – apply spoofs without permanent system changes.
- **Automatic rollback on shutdown** – restore original values before OS exits.
- **Command‑line interface** – quickly apply/remove spoofs via batch files.
- **Verification tool** – check current HWID values in real time.
- **Safe‑mode protection** – prevents accidental application in sensitive environments.
- **Step‑by‑step lab guide** – designed for virtual machine testing.
- **Comparison with permanent methods** – highlights differences in persistence.
- **Full source code comments** – explains every API call and structure.

## Requirements

- Windows 10 / 11 (64‑bit)
- Administrator privileges
- Recommended: a virtual machine for safe experimentation

## Usage

1. Extract files to a directory.
2. Run the `apply_temp.bat` script as Administrator.
3. The spoof will be active until next reboot.
4. Verify with the included `check_hwid.exe` tool.
5. To revert immediately, run `revert_temp.bat`.
6. Restart your system to completely clear the temporary changes.

## About the project

Temp-HWID-Spoofer is an educational repository focused on volatile system modifications. It provides commented scripts and configuration templates that demonstrate how to alter hardware identifiers in a non‑permanent way. This is useful for understanding the differences between memory‑resident and persistent changes, and for safely experimenting with driver‑level interactions without affecting system stability.

## Legality

This repository provides materials solely for educational purposes. The author does not endorse or encourage any use that violates any platform’s Terms of Service. All rights belong to their respective owners. Users are solely responsible for how they apply the information provided here.
