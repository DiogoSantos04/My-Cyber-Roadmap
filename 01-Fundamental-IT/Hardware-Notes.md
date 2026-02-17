# Computer Hardware Components

This document outlines the core hardware components of a computer system and their relevance to Cybersecurity,
as part of **Fundamental IT Skills** module.

## Core Components

### 1. Central Processing Units (CPU)
* **Function:** Known as the "brain" of computer, resposible for executing instructions and processing data

* **Security Relevance:** * Vulnerable to architectural attacks such as **Spectre** and **Meltdown**, which can leak data between processes.
    * Critical for understanding how malware executes at the instruction level.

### 2. Motherboard
* **Function:** The main circuit board that connects and allows communication between the CPU, memory and other hardware.
* **Security Relevance** * Houses the **BIOS/UEFI**, which must be secured (e.g., Secure Boot) to prevent low-level bootkits.

### 3. Random Access Memory (RAM)
* **Function** Serves as the computer's short-term memory, storing data that is actively being used by the CPU for quick access.
* **Security Relevance:** * **Volatile Data:** Data is lost when power is removed.
* **Digital Forensics:** Essential for **memory forensics** (using tools like 'memdump') to find encryption keys or malware running in stealth mode.

### 4. Storage Devices (HDD/SSD)

* **Function:** Where data is permanently stored, including the operating system, applications, and files.
* **Security Relevance:** * **Persistence:** This is where malware hides long-term.
* **Data Recovery:** Understanding the difference between "deleting" a file and "wiping" a drive is crucial for data privacy and forensic investigations.

### 5. Graphics Processing Unit (GPU)

* **Function:** Dedicated to rendering images and videos; also used for gaming and machine learning.
* **Security Relevance:** * **Password Cracking:** Highly efficient for brute-force attacks due to its ability to perform massive parallel processing.

### 6. Power Supply Unit (PSU)

* **Function:** Provides the necessary electrical power to run the components.
* **Security Relevance:** * While often overlooked, power fluctuations can cause system instability or be used in "side-channel attacks" to analyze power consumption patterns.

### 7. Input and Output Devices

* **Function:** Keyboards, mice, monitors, and printers that allow users to interact with the system.
* **Security Relevance:** * **HID Attacks:** Devices like malicious USB "Rubber Duckies" can act as a keyboard to inject commands into a target machine
