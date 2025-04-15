# DIY Powered Air-Purifying Respirator (PAPR)

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

| Component                    | Description / Example                                    |
|-----------------------------|-----------------------------------------------------------|
| Filter                      | 3M DT-1135E or Dräger 6738801 (NATO 40mm)                |
| Fan / Blower                | Delta BFB1012M or equivalent centrifugal blower           |
| Power source                | Bosch 18V Li-ion (with 3D-printed battery holder)         |
| Buck converter              | Step-down 18V → 12V (min. 2A recommended)                 |
| PWM generator               | 5V or 12V PWM module (depending on fan spec)              |
| Mask interface              | Optrel Swiss Air replacement mask (or custom design)      |
| Hose                        | Anti-static flexible hose (like CPAP)       |
| Enclosure                   | 3D-printed case or laser-cut design for fan & filter      |

---

## 🧪 Filter Options

| Filter                 | Standard            | Suitable For                                | Notes                                            |
|------------------------|---------------------|---------------------------------------------|--------------------------------------------------|
| 3M DT-1135E 7100260628 | P3 PSL R D          | Wood dust, fumes                            | Affordable, easy to get                          |
| 3M DT-4045 7100260628  | A2B2E2K2 P3 PSL R D | Welding (incl. stainless), VOCs, ammonia    | Broad gas protection, reusable                   |
| Dräger 6738797         | A2B2E2K2 P3 Hg R D  | Welding (incl. stainless), mercury, ammonia | Industrial-grade, high protection                |
| Dräger 6738815         | A2B2E2K1 P3 Hg R D  | Welding fumes, mercury, organic gases       | Similar to 6738797, slightly less ammonia rating |


---

## 🧱 3D-Printed Parts

- 🔌 NATO 40mm to hose adapter
- 🔋 Bosch 18V battery mount
- 💨 Fan mount / filter box
- 🎭 Mask-to-hose interface

All files will be added under `/hardware`.

---

## 📷 Example Images & Diagrams

*Coming soon: CAD renderings, wiring diagrams, airflow simulations, real photos.*

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

