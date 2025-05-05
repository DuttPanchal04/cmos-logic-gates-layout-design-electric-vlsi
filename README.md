# 🔌 CMOS Logic Gates Layout Design using Electric VLSI Tool ( Schematic, Layout, DRC, Simulation )

This repository contains the complete design, layout, and simulation of **basic and universal CMOS logic gates** built using the **Electric VLSI Design Tool** — a powerful open-source EDA tool.

From **schematic creation** to **layout design**, **DRC validation**, and **waveform simulation**, this project demonstrates the physical implementation of digital logic at the transistor level.

---

## 📁 Project Structure

Each Logic Gate folder includes:
- ✅ Schematic design (`.png`)
- 🧱 Layout view (`.png`)
- 🧪 Simulation waveform (`.png`)
- 🔍 DRC-verified designs
- 📂 Complete Project Library (`.jelib`) File ( open in Electric VLSI Software )
- Exported GDS File


---

## 🔧 Gates Designed

| Gate   | Type       | Status      |
|--------|------------|-------------|
| NOT / Inverter    | Basic      | ✅ Completed |
| AND    | Basic      | ✅ Completed |
| OR     | Basic      | ✅ Completed |
| NAND   | Universal  | ✅ Completed |
| NOR    | Universal  | ✅ Completed |
| XOR    | Basic      | ✅ Completed |
| XNOR   | Basic      | ✅ Completed |

---

## 🚀 Tools Used

- 🎯 **Electric VLSI Design Tool**
  - Java-based EDA tool for schematic, layout, and simulation
- 🧪 **ALS (Ambit Logic Simulator)**
  - Inbuilt for logic-level simulation
- 📁 **GDSII Export**
  - Standard for layout interoperability

---

## 📷 Project Snapshots

🔹1. CMOS Inverter / NOT Gate

![cmos inverter collage](https://github.com/user-attachments/assets/b3e0fe33-8b3c-424a-a864-65b9ea1b158f)

🔹2. CMOS AND Gate

![cmos and collage](https://github.com/user-attachments/assets/63b5717f-e5e6-4a5b-a26e-5fc2039446ba)

🔹3. CMOS OR Gate

![cmos or collage](https://github.com/user-attachments/assets/37fac568-3cc3-4d8f-b9f3-68472662bbf0)

🔹4. CMOS NAND Gate

![cmos nand collage](https://github.com/user-attachments/assets/fb1addea-a507-449c-9e45-b9be5ee0b60a)

🔹5. CMOS NOR Gate

![cmos nor collage](https://github.com/user-attachments/assets/1b03106a-a845-4e5e-ba62-8a612253fa4a)

🔹6. CMOS EX-OR / XOR Gate

![cmos xor collage](https://github.com/user-attachments/assets/f12c5237-1451-4a88-9f98-aed63476aa69)

🔹7. CMOS EX-NOR / XNOR Gate

![cmos xnor collage](https://github.com/user-attachments/assets/2fdde877-a9f9-47e1-bebe-aed5585cb291)


---

## 🧠 Learning Outcomes

- Hands-on experience with CMOS logic design
- Understanding transistor-level logic implementation
- Layout editing and DRC checking
- Using ALS simulation for waveform analysis
- Exporting standard GDS files from open-source tools

---

## 💻 How to Download, Install, and Run Electric VLSI Software

Follow this Repo:

```
https://github.com/DuttPanchal04/electric-vlsi-design-free-tool-installation-guide

```

## 💻 How to Run / Use?

### 🔹 1. Clone the Repo
```
git clone https://github.com/DuttPanchal04/cmos-logic-gates-layout-design-electric-vlsi.git
cd cmos-logic-gates-layout-design-electric-vlsi
```
### 🔹 2. Open Electric VLSI Software 

- Download from: [Electric VLSI Download](https://ftp.gnu.org/pub/gnu/electric/electric-9.08.jar)
- Launch Electric (requires Java)
- Open individual cell files (`.jelib`).

### 🔹 3. View Schematics & Layouts
- Navigate through the logic gate cells
- Open Schematic or Layout view from the cell explorer

### 🔹 4. Run Simulation
- Select Schematic → Tools → Simulator (Built-in) → ALS
- Set clock/input waveforms
- Run and observe output

### 🔹 5. Export GDS (Optional)
- Layout → Export → GDS → Save your cell as (`.gds`)

## 📤 GDS Export (What It Means)

GDS (Graphic Data System) is a standard file format used to represent IC layout artwork. It allows integration with other EDA tools such as KLayout, Magic, or even tapeout flow.

You can find the exported .gds files for each logic gate in the (`/GDS_Exports`) folder.

## 🤝 How to Contribute
I welcome contributions to enhance this project! Ideas include:

- 🔧 Delay or area optimization
- 📐 Gate sizing exploration
- 🧪 Simulation automation using scripts
- 📚 Add documentation or waveforms
- ➕ Add complex logic blocks (MUX, DEMUX, Adder, etc.)

## 📌 Steps to Contribute
Fork this repo

Create a new branch:
```
git checkout -b optimize-nand-delay
```
Make your changes, commit, and push:
```
git commit -m "Improved NAND layout to reduce delay"
git push origin optimize-nand-delay
```
Open a pull request — and you're done!

## 🔗 Connect with Me
- 💼 [LinkedIn](https://www.linkedin.com/in/dattpanchal04/)
- [GitHub](https://github.com/DuttPanchal04)
- 📧 Email: dattpanchal2904@gmail.com

## 🏷️ Tags
```
#VLSI #CMOSDesign #ElectricVLSI #EDA #OpenSourceTools #LogicGates #LayoutDesign #Semiconductor #DigitalDesign
```
