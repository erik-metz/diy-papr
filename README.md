# DIY Powered Air-Purifying Respirator (PAPR)

![DIY-PAPR-front](https://github.com/user-attachments/assets/dc303964-7eeb-4b75-9b14-eb4aefdb33ad)


## ⚠️ Disclaimer
This project is provided for educational and informational purposes only. Building and using a DIY powered air-purifying respirator (PAPR) involves significant health and safety risks. The authors and contributors of this repository accept no liability for any injury, loss, or damage resulting from the use or misuse of the information provided herein.

This system is not certified for use in hazardous environments and must not be used as a substitute for professional, tested respiratory protection when safety is critical (e.g., in welding, toxic fumes, or medical settings).

Use at your own risk.

## ℹ️ Info

This open-source project documents the design and construction of a custom **PAPR system** (Powered Air-Purifying Respirator), tailored for:
- **🪵 Woodworkers 🧔‍♂️with beards🧔‍♂️**
- **👨‍🏭 Hobby welders (including stainless steel)**
- **⚛️ Makers, DIYers, and tinkerers**
- Those looking for an affordable alternative to commercial systems like:
  - JSP PowerCap Active IP
  - Optrel Swiss Air
  - 3M Versaflo Series
  - CleanSpace Ultra / CleanSpace Halo
  - Dräger X-plore 8000

---

## 🔧 Features

- 🔋 Powered by **Bosch 18V Professional** battery
- 🌬️ Active airflow via **centrifugal blower** or high-quality fan (Delta, Noctua)
- 🧰 Modular filter support using **standard NATO 40mm** filters (3M, Dräger, etc.)
- 🧱 Custom 3D-printed parts for housing, mask connectors, mounts
- 🎛️ PWM speed control for fan noise & flow balancing
- 🛡️ Designed with options for **welding fumes** protection (e.g. NO, CO, P3)

---

## 📦 Bill of Materials (BOM)

| Component                   | Description / Example                                     | My Pick                |
|-----------------------------|-----------------------------------------------------------|------------------------|
| Filter                      | 3M DT-1135E or Dräger 6738801 (NATO 40mm)                 | 3M DT-1135E 7100260628 |
| Fan / Blower                | Delta BFB1012M or equivalent centrifugal blower           | Delta BFB1012M-BG51R   |
| Power source                | Bosch 18V Li-ion (with 3D-printed battery holder)         |
| Buck converter              | Step-down 18V → 12V (min. 2A recommended)                 |
| PWM generator               | DC 12V PWM Sspeed Ccontroller                             |
| Mask interface              | Optrel Swiss Air replacement mask (or custom design)      | §M 6200
| Hose                        | Anti-static flexible hose (like CPAP)                     |
| Enclosure                   | 3D-printed case or laser-cut design for fan & filter      |

---

## 🧪 Filter Options

| Filter                 | Standard            | Suitable For                                | Notes                                            |
|------------------------|---------------------|---------------------------------------------|--------------------------------------------------|
| 3M DT-1135E 7100260628 | P3 PSL R D          | Wood dust, fumes                            | Affordable, easy to get                          |
| 3M DT-4045 7100260628  | A2B2E2K2 P3 PSL R D | Welding (incl. stainless), VOCs, ammonia    | Broad gas protection, reusable                   |
| Dräger 6738797         | A2B2E2K2 P3 Hg R D  | Welding (incl. stainless), mercury, ammonia | Industrial-grade, high protection                |
| Dräger 6738815         | A2B2E2K1 P3 Hg R D  | Welding fumes, mercury, organic gases       | Similar to 6738797, slightly less ammonia rating |

I picked the 3M DT-1135E 7100260628 since I will mainly dow oodworking with it

---

## Fan

I picked the Delta BFB1012M-BG51R since it was cheap and available on ebay

Dimensions: Height: 97 mm Depth: 94 mm Width:33 mm
AC/DC: DC Blower Fan
Voltage: DC 12V
Working Voltage: 6.0-13.2V
Power: 5.8W
Current: 0.48A
Speed: 3200 RPM
Air Flow 27.4 CFM (0.78 m3/min)
Pressure Type:  0.893 in H2O
Noise: 52.5 DBA
Red Wire: Positive (+)
Black Wire: Negative (-)
Yellow Wire: PWM
Blue Wire: Tacho
Pulses: 2 per revolution
Re-Ozone depleting substances: no containing PBBs, PBBOs, DFCs, PBBEs, PBDPEs and HCFCs
Preferred duty point of the fan: 25kHz

---

## 🧱 3D-Printed Parts

- 🔌 NATO 40mm to hose adapter
- 🔋 Bosch 18V battery mount
- 💨 Fan mount / filter box
- 🎭 Mask-to-hose interface

All files will be added under `/hardware`.

---

## 📷 Example Images & Diagrams

### Rendering
![DIY-PAPR-front](https://github.com/user-attachments/assets/67fbfd42-6420-4756-8152-1cf6973d1523)
![DIY-PAPR-back](https://github.com/user-attachments/assets/13794a9f-cb1c-475d-930d-0807509d0a8a)
![DIY-PAPR-inner](https://github.com/user-attachments/assets/8ffd31e3-29af-4cac-a495-7f377fefe52b)

### First Batch
![IMG_2879](https://github.com/user-attachments/assets/c7fa515d-95e2-4daa-aaa4-a5fad8baf159)
![IMG_2880](https://github.com/user-attachments/assets/1898ba4b-d4be-406c-a9c4-4c757aa926e7)


---

## 💡 Ideas & Improvements

- Add air pressure monitoring / flow sensor
- CO/NO sensor warning LED for welding use
- Airflow splitter for dual filters
- Replaceable filter gaskets
- Soft shoulder/backpack harness

---
## 🙌 Contributing

Have improvements, 3D models, or test results?  
Please open an issue or pull request — let's build a better and more accessible PAPR together!

