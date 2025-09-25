---
icon: b
---

# Bootloader

**A bootloader** is a small program that runs when a computer, phone, or other device is powered on. Its job is to **initialize the hardware** and **load the operating system (OS)** into memory so the system can start working.



Bootloaders are not just "startup helpers" — they have **many applications** depending on the system. Here are the main ones:

#### **Operating System Loading**

* The classic job: load the OS kernel into memory and hand over control.
* Example: GRUB loads Linux, Windows Boot Manager loads Windows.

#### **Multi-Boot Systems**

* Lets you choose which OS to start if you have more than one installed.
* Example: Dual-booting Windows + Ubuntu.
* **Multiple boot options** - Can load different firmware versions and enter recovery mode
* **Failsafe mechanism** - if the main firmware fails, the bootloader can reload a backup
* **Peripheral support** - Enables booting from USB, SD card, or network sources
