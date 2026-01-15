# 🔧 Bosch EDC15 EEPROM Editor 

![GitHub forks](https://img.shields.io/github/forks/muki01/OBD2_K-line_Reader?style=flat)
![GitHub Repo stars](https://img.shields.io/github/stars/muki01/OBD2_K-line_Reader?style=flat)
![GitHub Issues or Pull Requests](https://img.shields.io/github/issues/muki01/OBD2_K-line_Reader?style=flat)
![GitHub License](https://img.shields.io/github/license/muki01/OBD2_K-line_Reader?style=flat)
![GitHub last commit](https://img.shields.io/github/last-commit/muki01/OBD2_K-line_Reader)
![C#](https://img.shields.io/badge/Language-C%23-blue) 
![Target](https://img.shields.io/badge/Target-Bosch_EDC15-red)

A dedicated tool for modifying binary dumps from **Bosch EDC15** series Engine Control Units (ECUs), commonly found in Audi, VW, Seat, and Skoda vehicles.

## 🎯 Compatible Hardware
This tool is specifically engineered for:
* **Manufacturer:** Bosch
* **Family:** EDC15 (P / V / VM)
* **Memory:** 24C04 EEPROM (512 Bytes)

## ⚠️ IMPORTANT: DISCLAIMER
USE THIS SOFTWARE AT YOUR OWN RISK.
- This tool is provided for educational and testing purposes only.
- The developer is not responsible for any damage caused to your vehicle, ECU, or computer hardware.
- Modifying ECU data can lead to a "bricked" ECU or vehicle start failure if done incorrectly.
- Always create a backup of your original 512-byte EEPROM dump before making any modifications.

## ✨ Features
- IMMO Patching: Toggle Immobilizer status (IMMO ON / IMMO OFF) with a single click.
- Odometer Correction: Read and modify the stored mileage (Kilometers) directly in the hex data.
- Login Code (PIN) Extraction: Automatically retrieve the 5-digit Login/PIN code required for key programming and VCDS adaptations.
- Data Validation: Automatic file size check (512 bytes) to prevent accidental loading of Flash files or corrupted dumps.
- Modern Interface: High-contrast dark mode UI for professional workshop environments.

## 🚀 How to Use
- Load: Click "Open File" and select your 512-byte binary dump.
- Analyze: The tool will automatically display the current Original Status, Mileage, and PIN Code.
- Modify: * Click the IMMO STATUS button to toggle between ON and OFF.
- Enter a new value in the Odometer text box to change mileage.
- Edit the Login Code if needed for synchronization.
- Save: Click "Save Modified File" to export your patched binary.

---

## ☕ Support My Work

If you enjoy my projects and want to support me, you can do so through the links below:

[![Buy Me A Coffee](https://img.shields.io/badge/-Buy%20Me%20a%20Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/muki01)
[![PayPal](https://img.shields.io/badge/-PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/donate/?hosted_button_id=SAAH5GHAH6T72)
[![GitHub Sponsors](https://img.shields.io/badge/-Sponsor%20Me%20on%20GitHub-181717?style=for-the-badge&logo=github)](https://github.com/sponsors/muki01)

---

## 📬 Contact

For information, job offers, collaboration, sponsorship, or purchasing my devices, you can contact me via email.

📧 Email: muksin.muksin04@gmail.com

---
