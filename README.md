# Bioprinter Nozzle CFD Study – Supplementary Repository

This repository contains all supplementary files associated with the paper:

**Title:** *Task-Specific Computational Fluid Dynamics Evaluation of Multi-Outlet Extrusion Nozzles for Bioprinting*  
**Authors:** *Cesar D. Vargas Urdaneta and Michael Taynnan Barros*  
**Date:** *---*  

---

## Repository Structure
```text
.
├── Plotting_Scripts/        # LaTeX/TikZ/PGFPlots sources for figures
├── STEP_files/              # CAD geometries (STEP format)
├── STL_Files/               # CAD geometries (STL format)
├── mesh_files/              # Exported FLUENT mesh files (.msh)
├── data/                    # Simulation outputs (CSV per–outlet metrics)
├── figure_source/           # High-resolution PDFs of manuscript figures
├── introductory_figure/     # Introductory schematic figures
├── workbench_journals/      # ANSYS Workbench journal files
├── WorkbenchArchives/       # Placeholder/reference to full archives (see Zenodo)
```
---

## Contents

**CAD**
- STEP_files/: STEP models of nozzle geometries.
- STL_Files/: STL models of nozzle geometries.

**Meshes**
- mesh_files/: Exported ANSYS FLUENT mesh files (.msh) corresponding to the geometries used in the CFD simulations.

**Simulation metrics**
- data/: CSV exports of per-outlet metrics (velocity, pressure, wall shear stress), organized by nozzle configuration and inlet pressure.

**Figure generation**
- Plotting_Scripts/: LaTeX/TikZ/PGFPlots sources used to generate manuscript figures.
- figure_source/ and introductory_figure/: High-resolution PDFs of manuscript figures.

**Workbench automation and reproducibility**
- workbench_journals/: ANSYS Workbench journal files documenting the meshing and setup workflow.
- WorkbenchArchives/: placeholder directory to indicate where full Workbench project archives belong; complete 4-outlet archives are hosted on Zenodo.

---

## Usage

1. **Reproduce figures:**  
   - Compile the `.tex` files in `Plot_TeX/` (requires `tikz` and `pgfplots`).  
   - The output matches the PDFs in `Figures/`.  

2. **View CAD models:**  
   - Open files from `CAD/` in Fusion 360, SolidWorks, or any STEP/STL-compatible viewer.  

3. **Inspect meshes**
   - Load .msh files in mesh_files/ directly in ANSYS Fluent to inspect grid topology, boundary naming, mesh quality, and size.

4. **Recreate meshes/simulations:**  
   - Load journals from `Workbench_Journals/` in ANSYS Workbench to reproduce meshing and CFD setup.  

---

## **License**
  - Code and plotting scripts are released under the MIT License.
  - Data, meshes, and figures are released under Creative Commons Attribution 4.0 (CC BY 4.0) unless otherwise stated.

---
