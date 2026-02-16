#  H-Shaped Patch Antenna for Wi-Fi / WiMAX

##  Project Overview

This project presents the **design and simulation of a dual-band H-shaped microstrip patch antenna** using **ANSYS HFSS**.
The antenna is designed to operate efficiently at **4.1 GHz and 5.8 GHz** for modern wireless communication applications such as **Wi-Fi, WiMAX, IoT modules, and portable communication devices**.

The H-slot structure modifies surface current distribution to achieve **dual-band resonance, improved bandwidth, and better impedance matching** without increasing antenna size.

---

##  Aim

To design and simulate a compact H-shaped microstrip patch antenna capable of dual-band operation at **4.1 GHz and 5.8 GHz** and evaluate performance parameters including:

* Return Loss (S11)
* VSWR
* Gain
* Bandwidth
* Radiation Pattern

---

##  Objectives

* Design compact dual-band patch antenna
* Optimize slot dimensions and feed location
* Achieve S11 < –10 dB at both bands
* Maintain VSWR < 2
* Obtain gain between 3–6 dBi
* Validate theoretical vs simulated results
* Verify suitability for wireless communication devices

---

##  Software Used

**ANSYS HFSS (High Frequency Structure Simulator)**
3D electromagnetic simulation software based on FEM (Finite Element Method) used to analyze RF and antenna performance.

---

## Antenna Design Details

| Parameter       | Value                     |
| --------------- | ------------------------- |
| Antenna Type    | H-Shaped Microstrip Patch |
| Substrate       | FR4 (εr ≈ 4.4)            |
| Feeding         | Microstrip line feed      |
| Frequency Bands | 4.1 GHz & 5.8 GHz         |
| Application     | Wi-Fi / WiMAX             |

### Working Principle

* RF power excites surface current on patch
* H-slots increase current path length
* Multiple resonance modes are generated
* Produces dual-band operation with wider bandwidth

---

##  Methodology

1. Requirement identification based on Wi-Fi/WiMAX standards
2. Theoretical calculation of patch dimensions
3. Geometry modeling in HFSS
4. Material assignment (FR4 & Copper)
5. Boundary & excitation setup
6. Frequency sweep (1–7 GHz)
7. Simulation & analysis
8. Optimization of slots & feed position
9. Validation with theory

---

##  Simulation Results

### Return Loss (S11)

| Frequency | S11      |
| --------- | -------- |
| 4.1 GHz   | ≈ –18 dB |
| 5.8 GHz   | ≈ –22 dB |

### VSWR

| Frequency | VSWR  |
| --------- | ----- |
| 4.1 GHz   | ≈ 1.3 |
| 5.8 GHz   | ≈ 1.2 |

### Gain

| Frequency | Gain          |
| --------- | ------------- |
| 4.1 GHz   | 3.5 – 4.2 dBi |
| 5.8 GHz   | 5.0 – 6.0 dBi |

### Bandwidth

| Band    | Bandwidth     |
| ------- | ------------- |
| 4.1 GHz | 80 – 100 MHz  |
| 5.8 GHz | 150 – 200 MHz |

---

##  Radiation Characteristics

* Broadside radiation pattern
* Directional coverage suitable for WLAN
* Higher efficiency at higher frequency

---

##  Applications

* Wi-Fi routers
* IoT communication modules
* Wireless sensor networks
* WLAN systems
* Portable wireless devices
* WiMAX communication links

---

##  Advantages

* Compact size
* Lightweight and low-profile
* Dual-band operation
* Improved bandwidth
* Better impedance matching
* Easy PCB fabrication

---

##  Conclusion

The H-shaped microstrip patch antenna successfully achieves **dual-band operation at 4.1 GHz and 5.8 GHz** with good return loss, acceptable VSWR, and adequate gain.
The slotting technique enhances bandwidth and performance without increasing antenna size, making it suitable for modern wireless communication systems.

---

##  Future Work

* Fabrication & real-time measurement
* MIMO antenna extension
* 5G band adaptation
* Gain enhancement using metasurfaces

