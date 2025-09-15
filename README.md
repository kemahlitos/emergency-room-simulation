# Emergency Room Simulation

This project is a **discrete-event simulation** of a hospital emergency room, developed during my Erasmus studies at Università degli Studi di Milano for the *Simulation* course (Spring 2024–2025).

---

## 📌 Project Description
The simulation models the patient flow in an emergency room, from arrival to exit. It captures:
- **Triage-based prioritization** (Critical, Moderate, Mild)
- **Doctor consultations** with variable availability
- **Laboratory testing** (30% probability)
- **Patient impatience and abandonment**
- **Resource utilization** (doctors, nurses)

The objective is to analyze how **resource availability**, **patient arrival rates**, and **lab test requirements** affect:
- Waiting times  
- Patient throughput  
- Impatience (patients leaving without service)  
- Doctor/Nurse utilization  

---

## 🛠️ Implementation
- **Tool**: [AnyLogic](https://www.anylogic.com/) – Process Modeling Library  
- **Programming**: Discrete-event simulation blocks (Source, Queue, Service, Delay, Sink)  
- **Statistical distributions**: Exponential, Triangular, Uniform  
- **Data Analysis**: Python (visualization of simulation results)

---

## 📊 Experiments Conducted
1. **Doctor Shift Capacity** – impact of staff availability  
2. **Patient Arrival Rate** – effect of increasing inflow  
3. **Lab Test Requirement Rate** – effect of diagnostic load  

Each experiment was simulated over 30 days, repeated 30 times, and results were exported to CSV for Python-based analysis.

---

## 🔑 Key Results
- Increasing doctor availability reduced waiting times but lowered utilization efficiency.  
- Higher patient arrival rates increased waiting and impatience, saturating system capacity.  
- Higher lab test requirements created bottlenecks, reducing throughput.  

---

## 📂 Project Files
- **Report**: [`simulationProjectReport.pdf`](./report/simulationProjectReport.pdf)  
- **AnyLogic Model**  
- **Results & Plots** 

---

## 👤 Author
- **Yusuf Kemahlı**  
- Erasmus project at Università degli Studi di Milano (Spring 2024–2025)  ****
