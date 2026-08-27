# Two-Stage Miller OTA

Comprehensive design and analysis of a Two-Stage Miller Operational Transconductance Amplifier (OTA). This project involved designing a custom analog integrated circuit to meet rigorous performance specifications.

### 🛠️ Tools & Technology
* **Methodology:** $g_m/I_D$ sizing methodology
* **EDA Tool:** Cadence Virtuoso
* **Technology Node:** CMOS 180nm

### 📊 Performance Specifications

The following table outlines the target requirements for the OTA alongside the final achieved simulation results, successfully meeting or exceeding all design parameters.

| Parameter | Required Specification | Achieved Result | Status |
| :--- | :--- | :--- | :---: |
| **Phase Margin (PM)** | $\ge$ 70° | 73.84° | ✅ |
| **DC Gain** | $\ge$ 66 dB | 70.07 dB | ✅ |
| **Current Consumption** | $\le$ 60 μA | 59.94 μA | ✅ |
| **CMRR @ DC** | $\ge$ 74 dB | 75.74 dB | ✅ |
| **Slew Rate** | $\ge$ 5 V/μs | 5.124 V/μs | ✅ |
| **Output Swing** | 0.2 V to 1.6 V | 0.12 V to 1.69 V | ✅ |
| **Static Gain Error** | $\le$ 0.05% | 0.039% | ✅ |
