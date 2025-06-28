# PM - Cost and Time Estimation
 
 

## User Interface Mockup
![Sensor Data Collector UI](https://github.com/PixelPhysician/time_cost_estimation/blob/main/Screenshot%20from%202025-06-28%2020-43-37.png)

---

## Functional Scope (Function Point Analysis)

Each interactive or data-related feature is mapped to function points:

| Feature                                | FP Value |
|----------------------------------------|----------|
| Display selected sensors               | 10 FP    |
| Select sensor (dropdown)               | 5 FP     |
| Add sensor to list                     | 5 FP     |
| Remove sensor from list                | 5 FP     |
| Update UI on Add/Remove                | 6 FP     |
| Start/Stop data collection             | 5 FP     |
| Toggle UI for Start/Stop               | 5 FP     |
| Transmit collected data to backend     | 4 FP     |
| Backend API (receive/store sensor data)| 7 FP     |
| External Interface File (sensor source)| 10 FP    |

### Function Point Summary

| Type | Count | Avg Weight | Total |
|------|-------|------------|-------|
| EI (External Input)   | 5     | 4          | 20 FP |
| EO (External Output)  | 3     | 5          | 15 FP |
| ILF (Internal Logic)  | —     | —          | 10 FP |
| EIF (Ext. Sensor Data)| —     | —          | 7 FP  |
Total:  **52 FP** 

---

## Code Size Estimation

Using the Java average of 53 LOC per FP:

- `52 FP × 53 LOC = 2,756 LOC`  
- /1000 
- Converted to KLOC: 2.756 kLOC

---

## Effort Estimation (COCOMO Model)

Using basic COCOMO (semi-detached project):

- `Effort (PM) = 3.0 × (2.756)^1.12 ≈ 10.3 PM`
- Environmental Factor (EAF) = 1.1 → Adjusted effort:  
  `10.3 × 1.1 = 11.3 Person-Months`

---

## Team & Timeline

Assuming a 5-month timeline:

- Team size = 11.3 / 5 ≈ **2.5 developers**
- So, ideally ca. 2–3 developers

---

## Cost Estimation

| Element                    | Amount        |
|----------------------------|---------------|
| Developer Effort           | 11.3 PM       |
| Monthly Cost per Developer | CHF 8,000     |
| **Subtotal**               | CHF 90,400    |
| Overhead (20%)             | CHF 18,080    |
| **Total Estimated Cost**   | **CHF 108,480** |

---

all calculations are based on Inputs from relevant Medical Software Developement Lectures. Appropriate assumptions done as necessary. 

---

by Sarah Deckarm, 2025
