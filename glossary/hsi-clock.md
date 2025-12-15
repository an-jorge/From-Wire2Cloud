---
icon: h
---

# HSI CLOCK

**HSI (High-Speed Internal) Clock** is an **internal oscillator** built into the microcontroller that provides a clock signal **without requiring any external components**.



#### **Key Characteristics**

* **Internal clock source** (no external crystal needed)
* **Fast startup time**
* Typically runs at a **fixed frequency** (varies by microcontroller family)
* **Lower accuracy** compared to external crystal oscillators
* Less affected by external noise or component failure

#### Typical Uses

* Early system startup and boot processes
* Low-cost or space-constrained designs
* Applications where **high precision timing is not critical**
* Backup clock source in case the external oscillator fails



#### **Considerations**

* Frequency may drift due to **temperature and voltage variations**
* Not ideal for precise communication protocols or time-critical applications without calibration



***

#### One-sentence summary

The HSI clock is a built-in high-speed oscillator that enables quick startup and simple designs but offers lower timing accuracy than external clock sources.

