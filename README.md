# 5G-Filtering-Antenna-Design

An integrated monopole antenna with **nested resonator** and **hairpin bandpass filters** for sub-6 GHz 5G applications.  
This project focuses on antenna–filter integration to achieve compactness, harmonic suppression, and stable gain across the working band.

---

## 📌 Abstract
This work proposes a novel filtering monopole antenna design for wideband wireless communication systems.  
The antenna integrates two different bandpass filter structures (nested resonator and hairpin filter) directly into the antenna feed, eliminating the need for separate RF front-end filters.  

- Operating frequency: **4.36 GHz**  
- Bandwidth: **31% 10 dB fractional bandwidth** (3.32 – 4.54 GHz)  
- Gain: **~2.3 dB** (constant in the working band)  
- Radiation nulls: **-11.95 dB @ 2.84 GHz** and **-6.73 dB @ 6.16 GHz**  
- Suitable for **sub-6 GHz 5G frequency band** applications  

---

## 🛠️ Tools & Technologies
- **Ansys HFSS** → Electromagnetic design and simulation  
- **FR4 Substrate** (εr = 4.4, thickness = 0.035 mm)  
- **Microstrip technology** for feeding network  
- MATLAB/Python (optional) for data plotting  

---

## 📐 Design Overview
1. **Wideband Hexagonal Monopole Antenna** – chosen for compact wideband operation.  
2. **Nested Resonator Filter** – concentric rectangular loops for frequency selectivity.  
3. **Hairpin Resonator Filter** – meandered structure for compact bandpass filtering.  
4. **Integration** – combining antenna + filters to realize a single **filtering antenna**.  

---

## 📊 Results
- **Reflection Coefficient (S11)** → antenna resonates at **4.36 GHz**  
- **Gain Plot** → nearly flat gain of **2.3 dB**  
- **Radiation Patterns** → stable omnidirectional performance  
- **Comparison** → shows superior bandwidth and size vs. earlier designs  

---
