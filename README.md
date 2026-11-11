# Ex. No. 2.1 — Creation of a 3D Solid Model from an Isometric Drawing

![CAD Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)
![Domain](https://img.shields.io/badge/Domain-CAD%20%2F%203D%20Modeling-blue?style=flat-square)
![Software](https://img.shields.io/badge/Software-AutoCAD%20%2F%20SolidWorks%20%2F%20Creo-orange?style=flat-square)

---

## 👨‍🎓 Student Details
* **Name:** [V KAMALESH KANNAN]
* **Register Number:** [26011247]
* **Department:** [COMPUTER SCIENCE ENGINEERING]
* **Course Code & Title:** 19AI302 — Computer Aided Design Lab

---

## 🎯 Aim
To construct an accurate 3D solid model from the given 2D isometric drawing specifications and dimensions using CAD software tools.

---

## 💻 System & Software Requirements
- **Operating System:** Windows 10/11 (64-bit)
- **CAD Software:** AutoCAD 3D / Autodesk Fusion 360 / SolidWorks / Creo Parametric
- **RAM:** Minimum 8 GB
- **Display Resolution:** 1920 × 1080 with True Color

---

## 🛠️ Key Commands & Modeling Features Used

| Command / Tool | Short-key / Icon | Function |
| :--- | :--- | :--- |
| **UNITS / LIMITS** | `UN` / `LIMITS` | Configures system units (mm) and defines the drawing boundary limits. |
| **POLYLINE** | `PL` | Constructs closed 2D profiles to prepare for extrusion. |
| **EXTRUDE** | `EXT` | Converts 2D planar profiles into 3D solid features along a specified height/axis. |
| **PRESSPULL** | `Ctrl + Shift + E` | Dynamically modifies bounded areas into 3D geometry. |
| **BOOLEAN (UNION / SUBTRACT)** | `UNI` / `SU` | Joins components together or carves cavities/holes out of the main solid. |
| **FILLET / CHAMFER EDGE** | `SOLIDEDIT` | Adds rounded or beveled transitions along specified edges. |
| **VIEW CUBE** | `SE Isometric` | Changes camera angle between orthographic planes and 3D isometric perspectives. |

---

## 📋 Procedure

1. **Workspace Setup:**
   - Launch CAD software and switch the workspace to **3D Modeling**.
   - Set drawing units to **Millimeters (`mm`)** and decimal precision to `0.00`.
   - Adjust drawing limits and run `ZOOM > ALL`.

2. **2D Base Profile Construction:**
   - Orient the view to the appropriate reference plane (Top, Front, or Right).
   - Draw the foundational geometry using `LINE`, `POLYLINE`, `CIRCLE`, and `TRIM` according to the dimensions given in the problem statement.
   - Ensure all sketches form closed loops (`REGION` or `JOIN`).

3. **Solid Feature Generation:**
   - Use the `EXTRUDE` or `PRESSPULL` command to generate base 3D volume.
   - For internal slots, holes, or steps, sketch auxiliary profiles on the faces and perform `SUBTRACT` operations.

4. **Finishing & Verification:**
   - Apply fillets and chamfers as specified in the blueprint.
   - Switch the visual style from **2D Wireframe** to **Conceptual / Shaded with Edges**.
   - Verify dimensions and mass properties against the original drawing.

---

## 🖼️ Input Blueprint vs. 3D Model Output

| Input Isometric Drawing | Final 3D Solid Model |
| :---: | :---: |
| ![Isometric Input](<img width="680" height="563" alt="image" src="https://github.com/user-attachments/assets/771bde52-903e-49bf-93bf-270b008fecb6" />
) | ![3D Output](
) |
## DRAWING:
<img width="1057" height="752" alt="Screenshot 2026-11-10 184329" src="https://github.com/user-attachments/assets/915316c9-b0bd-40e6-99f8-f0dee95d7875" />


## 📌 Result
The 3D solid model was successfully created from the given isometric drawing following all dimensional tolerances and geometric constraints.
