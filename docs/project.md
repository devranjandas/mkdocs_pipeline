# Engineering & Automation Projects Dashboard

This page provides a centralized overview of the active, planned, and completed engineering and automation projects within our research and development facility.

---

## Project Portfolio Summary

The table below outlines our primary engineering initiatives, their core technological stacks, and current operational statuses.

| Project Name | Primary Technology Stack | Target Deployment | Status |
| :--- | :--- | :--- | :--- |
| **PVD Control System Overhaul** | Schneider PLC, Citect SCADA, Modbus TCP/IP | In-House PVD Lab | 🟢 Active |
| **Agentic DB Automation** | Python, Large Language Models (LLMs) | Scientific DB Clusters | 🟡 In Progress |
| **Microbalance DAQ System** | Python, PyQt5, Real-Time Data Logging | Analytical Labs | 🔵 Validating |
| **AmbiClock Platform** | ESP32-S3, Embedded C, Hardware Sensors | Facility Infrastructure | 🔘 Completed |

*Status Legend: 🟢 Active Development | 🟡 In Progress / Design | 🔵 Validation / Testing | 🔘 Completed / Production*

---

## Detailed Project Breakdowns

### 1. PVD System Instrumentation & Control Upgrade
* **Objective:** Replace legacy, relay-based control logic with a modern, automated SCADA-PLC architecture to improve operational reliability and safety parameters.
* **Key Components:**
  * Transitioning to **Schneider Electric M241/M340** hardware.
  * Developing a comprehensive human-machine interface using **Citect SCADA**.
  * Implementing **Modbus TCP/IP** communication layers for robust field device telemetry.
* **Deliverables:** High-fidelity real-time monitoring, automated vacuum/venting sequences, and historical data logging.

### 2. Agentic AI Database Sync Engine
* **Objective:** Automate the parsing and ingestion of unstructured experimental datasets directly into structured scientific databases.
* **Key Components:**
  * Core pipeline built natively in **Python**.
  * Advanced text extraction modules to parse raw instrument log files and experimental sheets.
  * Verification routines to ensure data integrity before final database insertion.
* **Deliverables:** A fully automated background service that eliminates manual transcription errors and accelerates data availability for research teams.

### 3. Automated Microbalance Data Acquisition (DAQ)
* **Objective:** Design and implement a high-precision software layer to interface with analytical microbalance hardware.
* **Key Components:**
  * **Python-based backend** utilizing dedicated serial communication modules for real-time mass rate tracking.
  * Graphical user interface designed using **PyQt5** to provide live data visualization and immediate mass rate calculations.
  * Structured **CSV data logging** format for reliable parsing and long-term storage compatibility.
* **Deliverables:** Real-time stability indicators and automated export utilities for analytical reporting.

### 4. Smart Environment Monitor (AmbiClock)
* **Objective:** Build an embedded edge device to provide environmental telemetry and facility-wide synchronized time tracking.
* **Key Components:**
  * Custom firmware compiled for the **ESP32-S3** microcontroller.
  * Integration of local temperature, humidity, and atmospheric sensors.
* **Deliverables:** Successful physical deployment of hardware monitoring units across the lab floor.

---

## Engineering Standards & Compliance

All system designs, codebases, and user requirement specifications drafted for the above initiatives must strictly align with international engineering frameworks:
* **Requirement Engineering:** Adherence to **ISO/IEEE/IEC 29148** guidelines.
* **Documentation:** Comprehensive architecture maps, network topologies, and sequential logic charts must accompany every final code commit.

For detailed access to repository blueprints or to view specific functional requirements, please navigate to our [System Architecture Guide](architecture.md).