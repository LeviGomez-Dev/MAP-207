# MAP-207: Industrial Automatic Sorting System 🏭

## 📝 Description
This project showcases a high-precision industrial sorting system designed to classify workpieces by material, size, and color. It represents the foundation of my logical thinking and algorithmic design skills.

## ⚙️ How it works (The Logic)
The system uses a **Cartesian Manipulator (X-Y axis)** and a vacuum-based gripper. I programmed the sequence to:
1. **Detect:** Using inductive and photoelectric sensors.
2. **Decide:** Execute different sub-routines (FC1 for Metal, FC2 for Plastic).
3. **Execute:** Pick and place the piece in the designated storage area.

## 📂 Repository Contents
- https://github.com/LeviGomez-Dev/MAP-207/blob/main/Documentation/PROGRAMACION-LEVI%20PROYECTO.pdf :Technical manuals and my PDF report (`PROGRAMACION-LEVI PROYECTO.pdf`).
- [Documentation/CLASIFICACIÓN DE MATERIAL-LEVI PROYECTO.pdf:](https://github.com/LeviGomez-Dev/MAP-207/blob/main/Documentation/CLASIFICACI%C3%93N%20DE%20MATERIAL-LEVI%20PROYECTO.pdf) : Full project in PDF report (`CLASIFICACIÓN DE MATERIAL-LEVI PROYECTO.pdf`)
- `/Source`: The original PLC code logic.

## 💡 Why this matters for Software Engineering?

Even though this uses PLC languages, it follows the same principles as modern software: **Modular programming, Error handling, and State Machines.** I am currently translating this logic into a **Python Simulation** to demonstrate code parity.
