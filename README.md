# Process Injection Demo (C++)

> **Educational demonstration only.**
>
> This project demonstrates a straightforward implementation of process injection in C++ on Windows. The implementation intentionally **does not** include any antivirus (AV) or endpoint detection and response (EDR) bypass techniques, evasion methods, or stealth features. Its purpose is to help understand the Windows API and common process injection concepts in a controlled lab environment.

## Overview

This repository contains a simple proof-of-concept that demonstrates the mechanics of injecting shellcode into a target process using standard Windows API functions.

The project was developed and tested in an isolated lab environment on:

- **Operating System:** Windows 10
- **Language:** C++
- **Compiler:** Microsoft Visual Studio (MSVC)

The injected payload used during testing was generated with **msfvenom**.

## Features

- Basic process injection example
- Clear and readable C++ source code
- No AV/EDR bypass techniques
- No obfuscation or encryption
- Intended for learning Windows internals and API usage

## Testing

The demonstration was tested on:

- Windows 10 (64-bit)

Results may vary on other Windows versions or configurations.

## Shellcode

During testing, the shellcode was generated using **msfvenom**.

This repository does **not** include generated shellcode. Users should create their own payloads in accordance with applicable laws, software licenses, and organizational policies.



## Disclaimer

This project is provided solely for educational and research purposes to demonstrate Windows process injection concepts. It is **not** intended for unauthorized access, persistence, privilege escalation, or evasion of security products.

The author makes no guarantees regarding functionality, compatibility, or fitness for any particular purpose.

Users are solely responsible for ensuring that any testing is performed only on systems they own or are explicitly authorized to assess.

## Legal Notice

Use this code only:

- In your own lab environment
- On systems you own
- With explicit written authorization

Unauthorized use against third-party systems may violate laws, regulations, or organizational policies.
