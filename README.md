# ⚡ RLC Resonance Analysis (Series & Parallel)

## 📌 Overview
This project analyzes series and parallel RLC circuits using:
- Transient analysis
- AC analysis
- Bode plots

Theoretical and simulation results are compared.

---

## 🎯 Objectives
- Study resonance phenomenon
- Verify resonance frequency
- Plot Bode magnitude and phase
- Compare series vs parallel resonance

---

## ⚙️ Tools Used
- LTspice

---

## 📖 Theory

### Resonance Condition
Resonance occurs when:
XL = XC

At this condition:
- Circuit behaves as purely resistive

---

## 🔹 Series Resonance
- Impedance is minimum
- Current is maximum
- Called acceptor circuit

---

## 🔹 Parallel Resonance
- Impedance is maximum
- Current is minimum
- Called rejector circuit

---

## 📊 Key Formulas

- Resonant Frequency:
  f₀ = 1 / (2π√LC)

- Bandwidth:
  BW = f₀ / Q

---

## 🧪 Simulations

### Series RLC
- AC Analysis
- Bode Plot
- Transient Response

### Parallel RLC
- AC Analysis
- Admittance Plot
- Transient Response

---

## 📊 Observations
- Magnitude at phase = -90° matches theory
- Resonance frequency matches theoretical value
- Series: current max at resonance
- Parallel: impedance max at resonance

---

## ⚠️ Practical Considerations
- Inductor requires small series resistance
- Ideal sources may give incorrect results
- Proper grounding/reference is required

---

## 📉 Results Summary
| Parameter | Series | Parallel |
|----------|--------|---------|
| Resonance Frequency | Same | Same |
| Impedance | Minimum | Maximum |
| Current | Maximum | Minimum |

---

## ✅ Conclusion
Both series and parallel RLC circuits show strong agreement between theoretical and simulation results. Proper modeling (including parasitic resistance) is necessary for accurate simulation.

---

## 📁 Files
- `Resonance_RLC.pdf` → Full report->[Resonance_RLC.pdf](https://github.com/user-attachments/files/26917312/Resonance_RLC.pdf)
- Simulation graphs

---

## 🚀 Future Work
- Filter design applications
- High-Q circuits
- Real-world component analysis
