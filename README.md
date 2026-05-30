# 📡 Enhanced Sub-6 GHz Microstrip Patch Antenna with Wideband for Next-Gen Wireless Systems

<div align="center">

![Antenna Banner](https://img.shields.io/badge/Frequency-3.73%20GHz-blue?style=for-the-badge&logo=signal&logoColor=white)
![Bandwidth](https://img.shields.io/badge/Bandwidth-950%20MHz-green?style=for-the-badge)
![Return Loss](https://img.shields.io/badge/Return%20Loss--17.1%20dB-orange?style=for-the-badge)
![Simulator](https://img.shields.io/badge/Simulator-ANSYS%20HFSS-red?style=for-the-badge)
![Substrate](https://img.shields.io/badge/Substrate-FR--4-purple?style=for-the-badge)
![5G](https://img.shields.io/badge/Compatible-5G%20NR%20%7C%20WiMAX%20%7C%20IoT-teal?style=for-the-badge)

**A Phase-I B.E. Project | Electronics & Communication Engineering**  
Dhanalakshmi Srinivasan Engineering College (Autonomous), Perambalur  
Affiliated to Anna University, Chennai - 600 025

</div>

---

## 👥 Team Members

| Name | Roll Number |
|------|-------------|
| Manojkumar S | 810422106062 |
| Rajasurya J | 810422106090 |
| Selvakrishnan K | 810422106104 |
| Sivapradhosh U | 810422106109 |

**Supervisor:** Mr. N. Khadar Basha, M.E. — Dept. of ECE  
**HOD:** Dr. P. Rajeswari, M.E., Ph.D.

---

## 📋 Abstract

This project presents the design and performance analysis of a **wideband filtering microstrip patch antenna** for Sub-6 GHz wireless communication, designed using **ANSYS HFSS** (High-Frequency Structure Simulator).

The antenna integrates a **circular slot**, a **quarter-wave transformer**, and a **graded ground structure** to achieve strong frequency selectivity with a wide operational bandwidth. It resonates at **3.73 GHz** with a −10 dB impedance bandwidth of approximately **950 MHz (3.30–4.25 GHz)**, enabling efficient operation across the Sub-6 GHz 5G band.

Key highlights:
- **Substrate:** FR-4 (εr = 4.4, tan δ = 0.02, thickness = 1.6 mm)
- **Conductor:** Standard copper (0.035 mm)
- **Return Loss:** −17.1 dB minimum
- **Peak Realized Gain:** 3.00 dB
- **Directivity:** 3.33 dB
- **Two radiation nulls** for effective out-of-band suppression

---

## 🚀 Features

- ✅ Compact, low-profile planar design
- ✅ Wide −10 dB impedance bandwidth (~950 MHz)
- ✅ Integrated filtering — no external filter circuits needed
- ✅ Cost-effective FR-4 substrate fabrication
- ✅ Radiation nulls at ~2 GHz and ~5.8 GHz for sharp band-edge selectivity
- ✅ Compatible with 5G NR (n77/n78), WiMAX, IoT, and broadband systems
- ✅ Full-wave HFSS simulations (S-parameters, gain, radiation patterns)

---

## 📐 Antenna Design Parameters

| Parameter | Value |
|-----------|-------|
| Resonant Frequency | 3.73 GHz |
| Operating Band | 3.30 – 4.25 GHz |
| Bandwidth (−10 dB) | ~950 MHz |
| Return Loss (S11) | −17.1 dB |
| VSWR (at resonance) | 1.3042 |
| Realized Gain | 3.00 dB |
| Directivity | 3.33 dB |
| Substrate | FR-4 (εr = 4.4) |
| Substrate Thickness | 1.6 mm |
| Loss Tangent | 0.02 |
| Conductor Material | Copper (0.035 mm) |

### Optimized Structural Dimensions

| Parameter | Value |
|-----------|-------|
| Patch Width (Wp) | 29 mm |
| Patch Length (Lp) | 19 mm |
| Circular Slot Radius (r) | 2.7 mm |
| Ground Length (Lg) | 15 mm |
| Stripline Length (l1) | 6.7 mm |
| T-Strip Height (l2) | 9.4 mm |
| Feedline Width (Wf) | 2 mm |

---

## 🏗️ Antenna Architecture

```
┌─────────────────────────────────────┐
│         RADIATING PATCH             │
│    ┌───────────────────────┐        │
│    │   ○  Circular Slot    │        │
│    │                       │        │
│    └──────────┬────────────┘        │
│               │ Quarter-Wave        │
│               │ Transformer         │
│    ┌──────────┴────────────┐        │
│    │   T-Shaped Ground     │        │
│    │   (Radiation Nulls)   │        │
│    └───────────────────────┘        │
│         FR-4 SUBSTRATE              │
└─────────────────────────────────────┘
```

**Design Components:**
- **Rectangular Patch** — Main radiator at 3.73 GHz
- **Circular Slot** — Generates upper radiation null (~5.8 GHz)
- **T-Shaped Ground Strip** — Creates lower radiation null (~2 GHz)
- **Quarter-Wave Transformer** — Impedance matching to 50 Ω feedline

---

## 📊 Simulation Results

### S11 (Return Loss)
- Minimum S11: **−17.1 dB** at **3.72 GHz**
- −10 dB bandwidth: **3.30 GHz to 4.25 GHz** (~950 MHz)

### VSWR
- VSWR at resonance: **1.3042** (well within acceptable < 2 threshold)

### Gain & Directivity
- Peak realized gain: **3.00 dB**
- Directivity: **3.33 dB**
- Radiation nulls: **~−22 dB** suppression at null frequencies

---

## 🛠️ Software Used

| Tool | Purpose |
|------|---------|
| **ANSYS HFSS 2025 R2** | Full-wave 3D EM simulation (FEM-based) |

---

## 📡 Applications

| Domain | Application |
|--------|-------------|
| **5G NR** | Sub-6 GHz bands n77/n78 (3.3–3.8 GHz) |
| **WiMAX** | Fixed wireless broadband at 3.5 GHz |
| **IoT** | Smart city sensors, industrial automation |
| **UAV** | Drone communication and aerial navigation |
| **Radar** | Short-range civil radar and traffic monitoring |
| **Public Safety** | Emergency response network links |
| **Medical** | Wireless patient monitoring and telemetry |
| **Smart Home** | Home automation and security systems |
| **WLAN** | High-density Wi-Fi access point integration |

---

## 📂 Project Structure

```
📦 Sub-6GHz-Microstrip-Patch-Antenna/
├── 📁 docs/
│   ├── ENHANCED_SUB-6_GHZ_MICROSTRIP_PATCH.pdf    # Full project report
│   └── ENHANCED_SUB-6_GHZ_MICROSTRIP_PATCH.pptx   # Presentation slides
├── 📁 simulation/
│   ├── hfss/
│       └── results/
│           ├── S11_parameter.png
│           ├── VSWR_plot.png
│           ├── gain_plot.png
│           └── directivity_plot.png
├── 📁 figures/
│   ├── front_view_patch.png                         # Patch front view
│   ├── front_view_ground.png                        # Ground plane view
├── 📁 calculations/
│   └── design_equations.md                          # Design formulas & math
├── README.md

```

---

## 🔬 Design Equations

### Patch Width
```
W = c / (2 * fr * sqrt((εr + 1) / 2))
```

### Effective Dielectric Constant
```
εeff = (εr + 1)/2 + (εr - 1)/2 × (1 / sqrt(1 + 12h/W))
```

### Quarter-Wave Transformer Length
```
l = λg / 4     where     λg = λ0 / sqrt(εeff)
```

### Patch Length
```
L = c / (2 * fr * sqrt(εeff)) - 2ΔL
```

---

## 📈 Performance Comparison

| Parameter | Existing Design (0.8mm) | Proposed Design (1.6mm) |
|-----------|------------------------|------------------------|
| Substrate Thickness | 0.8 mm | **1.6 mm** |
| Bandwidth | ~800 MHz | **~950 MHz** |
| Return Loss | ~−12 dB | **−17.1 dB** |
| Resonant Frequency | 3.5 GHz | **3.73 GHz** |
| Peak Gain | ~2.5 dB | **3.00 dB** |
| Directivity | ~3.0 dB | **3.33 dB** |

---

## 🔭 Future Enhancements

- [ ] **Reconfigurable antenna** using PIN/varactor diodes for tunable frequency
- [ ] **MIMO configuration** for enhanced channel capacity in 5G/6G systems
- [ ] **High-performance substrates** (Rogers RT5880, Taconic) for improved gain
- [ ] **Antenna-in-Package (AiP)** integration for compact IoT devices
- [ ] **AI/ML-assisted optimization** (Gaussian Process Regression for geometry tuning)
- [ ] **Real-world VNA testing** under varying environmental conditions
- [ ] **Wearable/biomedical** form-factor adaptation

---

## 📚 References

1. N. K. Mohsin and D. K. Naji, "Design of a Compact Sub-6 GHz Wideband Filtering Patch Antenna Without Extra Structure," *Progress in Electromagnetics Research C*, vol. 155, pp. 165–175, 2025.
2. X. Liu et al., "Printed Filtering Dipole Antenna with Compact Size and High Selectivity," *IEEE Transactions on Antennas and Propagation*, vol. 72, no. 3, pp. 2355–2367, 2024.
3. H. Chu and Y.-X. Guo, "Filtering Dual-Polarized Antenna Sub-Array for Millimeter-Wave and Sub-6 GHz Stations," *IEEE TCPMT*, 2023.
4. B.-J. Chen et al., "Compact High-Selectivity Wideband Filtering Antenna with Multipath Coupling," *IEEE AWPL*, vol. 21, 2022.

*Full reference list available in the project report.*

---

## 🏫 Institution

**Dhanalakshmi Srinivasan Engineering College (Autonomous)**  
Perambalur - 621212, Tamil Nadu  
Affiliated to Anna University, Chennai - 600 025

---

## 📄 License

This project is submitted as an academic requirement for the Bachelor of Engineering degree in Electronics and Communication Engineering at Anna University. All simulation results and design methodologies are original work of the project team.

---

<div align="center">

Made with ❤️ for next-generation wireless systems

*Sub-6 GHz | 5G NR | HFSS | Microstrip | Filtering Antenna*

</div>