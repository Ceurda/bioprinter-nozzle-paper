# Bioprinter Nozzle CFD Study – Supplementary Repository

This repository contains all supplementary files associated with the paper:

**Title:** *Task-Specific Computational Fluid Dynamics Evaluation of Multi-Outlet Extrusion Nozzles for Bioprinting*  
**Authors:** *Cesar D. Vargas Urdaneta and Michael Taynnan Barros*  
**Date:** *---*  

---

## 📂 Repository Structure
.
├── Plotting_Scripts/ # LaTeX/TikZ/PGFPlots sources for figures
├── STL_Files/ # CAD geometries (STL format)
├── data/ # Simulation outputs (CSV per–outlet metrics)
├── figure_source/ # High-resolution PDFs of manuscript figures
└── workbench_journals/ # ANSYS Workbench journal files (meshing & setup)

---

## 📊 Contents

- **CAD/**  
  Geometrical models of single, dual, 4-, 8-, and 16-outlet nozzle designs (STEP + STL formats).  

- **Workbench_Journals/**  
  ANSYS Workbench journals used to generate and document the meshing and simulation setup.  

- **CSV_Data/**  
  Raw simulation outputs, organized by nozzle type and inlet pressure. Each CSV contains per-outlet velocity, pressure, and wall shear stress.  

- **Plot_TeX/**  
  LaTeX/TikZ/PGFPlots sources used to generate schematic and results figures.  

- **Figures/**  
  High-resolution PDFs of all figures used in the introduction and results sections.  

- **Manifest.md**  
  Cross-reference list mapping filenames to the corresponding figures/tables in the manuscript.  

---

## ⚙️ Usage

1. **Reproduce figures:**  
   - Compile the `.tex` files in `Plot_TeX/` (requires `tikz` and `pgfplots`).  
   - The output matches the PDFs in `Figures/`.  

2. **View CAD models:**  
   - Open files from `CAD/` in Fusion 360, SolidWorks, or any STEP/STL-compatible viewer.  

3. **Recreate meshes/simulations:**  
   - Load journals from `Workbench_Journals/` in ANSYS Workbench to reproduce meshing and CFD setup.  

---

## 📌 Notes

- Rheology parameters (K, n, μ) and solver settings are summarized in **Table 2 of the paper**.  
- Density values are literature-informed assumptions; bounds for K and n are discussed in the sensitivity analysis.  
- All files are provided exactly as used in the study for transparency and reproducibility.  

---
