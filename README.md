# GRBL‑Maintenance‑Generator

A lightweight web‑based tool for woodworking CNC operators.  
It generates two safe, spindle‑off G‑code programs for machine maintenance:
- **Greasing Routine**: deep‑cleaning “pecking” sequence to purge & apply grease  
- **Exercise Routine**: simple warm‑up movements  

All settings are saved locally in your browser — **no server or internet required**.

---

## 🚀 Features  
- Fully offline — just open the HTML file in your browser.  
- Automatically saves your settings for next time.  
- Generates ready‑to‑use G‑code files compatible with UGS, Candle, and similar CNC sender software.  
- Open‑source and licensed under [GNU GPL v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html).

---

## 💾 How to Use  
### 1. Download the Tool  
1. [Download the HTML file](https://raw.githubusercontent.com/rkolbi/GRBL-Maintenance-Generator/main/cnc_maintenance_generator.html)  
2. Save it as `cnc_maintenance_generator.html` (or a name you prefer) to a convenient location.

### 2. Open in Your Browser  
- Double‑click the saved file.  
- It will open in your default browser (Chrome, Firefox, Edge, etc.).  
- No internet connection is required after downloading.

### 3. Generate G‑Code  
1. Enter your machine’s settings (these are saved automatically).  
2. Click **Generate Greasing G‑Code** or **Generate Exercise G‑Code**.  
3. Click **Save as .gcode** to download the file.  
4. Load it into your CNC sender software and run it safely with the spindle off.

### ⚠️ Safety Note  
The generated G‑code is spindle‑off and designed only for maintenance and warm‑up routines. **Always verify your settings before running on your machine.**
