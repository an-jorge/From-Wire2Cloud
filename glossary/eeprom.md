---
icon: e
---

# EEPROM

**EEPROM** (Electrically Erasable Programmable Read-Only Memory) is a type of **non-volatile memory**, meaning it **retains data even without power**.\
It is widely used in microcontrollers to store **settings, calibrations, or any data that must persist after power-off**.



#### Typical Hardware use:

* **Non-volatile**: keeps data without power.
* **Electrically rewritable**, byte by byte.
* **Limited write cycles** (usually 100,000 to 1,000,000 writes per cell).
* **Small size** (commonly 512 bytes to a few kB in microcontrollers).



* Storing Wi-Fi credentials
* User preferences
* Counters or simple logs
* Permanent system settings



* The ESP32 **does not have a physical EEPROM**, but emulates it using **internal flash** with the `EEPROM.h` library.
* It behaves similarly but is actually writing to flash memory.

***

**One-sentence summary:**\
EEPROM is a small non-volatile memory used to store important data that must persist even when the device is powered off.

####
