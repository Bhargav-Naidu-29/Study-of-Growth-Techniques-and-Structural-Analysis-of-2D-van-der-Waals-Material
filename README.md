# Study-of-Growth-Techniques-and-Structural-Analysis-of-2D-van-der-Waals-Material

## 📘 Overview

This project explores the structural analysis of **two-dimensional (2D) van der Waals (vdW) materials**, with a specific focus on **PbTaSe₂**, a layered material known for its **noncentrosymmetric structure** and potential **topological superconductivity**. Due to limited access to synthesis infrastructure, the study focuses on the **characterization and refinement** of experimental X-ray diffraction (XRD) data using open-source crystallographic tools.

## 🧪 Objectives

- Understand and apply synthesis techniques used for single-crystal growth of vdW materials.
- Perform phase identification using **Match! software**.
- Refine XRD data using the **FullProf suite**, incorporating corrections for **texture, contamination**, and **instrumental artifacts**.
- Compare experimental results with reference datasets from the **Materials Project**.

## 🔧 Tools and Technologies

- 🧬 **FullProf Suite** (Rietveld refinement)
- 🔍 **Match!** (Phase identification)
- 📊 **Origin** (Data cleaning and preprocessing)
- 📚 **Crystallographic Open Database (COD)** and **Materials Project**
- 🧾 **LaTeX** (Report writing)
- 🖼️ Python, Canva, GitHub for documentation and sharing

## 🧱 Methodology

### 1. Sample Preparation
- Used Vanadium (standard) and PbTaSe₂ (target sample).
- Powdered samples using agate mortar and pestle for uniformity.

### 2. XRD Data Collection
- Data collected in the 2θ range of 10° to 90°, with a step size of 0.01°.

### 3. Phase Identification (Match!)
- Validated phase and space group using database comparisons.
  
![Phase Identification](figures/PhaseMatchPbTaSe2.png)

### 4. FullProf Refinement
- Applied Rietveld refinement to fit experimental patterns.
- Addressed:
  - **Preferred orientation** using March–Dollase correction.
  - **Ghost peaks** from Kβ radiation using Bragg’s condition filtering.
  - **Contamination peaks** (oil) removed using Origin.

| Parameter              | Experimental  | Reference (Materials Project) |
|------------------------|---------------|-------------------------------|
| Crystal System         | Trigonal      | Trigonal                      |
| Space Group            | P$\bar{3}$m1  | P$\bar{3}$m1                  |
| Lattice Parameter \(a\)| 3.44 Å        | 3.435 Å                       |
| Lattice Parameter \(c\)| 9.38 Å        | 9.365 Å                       |
| Refined χ² Value       | 18.3          | N/A                           |

### 🔬 Graphs

**Vanadium (Standard Reference):**

![Vanadium XRD](figures/VanadiumFullProf.png)

**PbTaSe₂ (Target Material):**

![PbTaSe2 XRD](figures/PbTaSe2FullProf.png)

**Texture Representation:**

![Texture Effect](figures/texture.png)

## 🧠 Key Learnings

- Gained hands-on expertise in **crystallographic analysis** using FullProf and Match!.
- Understood and resolved challenges in refinement due to **sample texturing**, **instrument limitations**, and **contaminants**.
- Demonstrated how refinement outcomes differ from standard values and the significance of phase validation.

## 📌 Conclusion

The project demonstrates the potential of **computational crystallography** in characterizing complex vdW materials in the absence of full synthesis setups. PbTaSe₂ was successfully refined with experimental values aligning closely to theoretical data, and issues such as texture and ghost peaks were resolved methodically.

---

> **Supervisor:** Dr. Ritu Gupta  
> **Course Code:** CP301  
> **Author:** Bhargav Naidu Palavalasa
