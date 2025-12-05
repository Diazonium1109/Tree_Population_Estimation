# Estimating the Tree Population of ISI Bangalore

**A Statistical Sampling Project using Stratified Random Sampling & Geospatial Mapping**

![Status](https://img.shields.io/badge/Status-Completed-success)
![Method](https://img.shields.io/badge/Method-Stratified_Sampling-blue)
![Location](https://img.shields.io/badge/Location-ISI_Bangalore-red)

## 📌 Project Overview
This project presents a statistically rigorous estimate of the tree population within the **Indian Statistical Institute (ISI), Bangalore** campus. 

Instead of a simple census (counting every tree), which is resource-intensive, we employed **Stratified Random Sampling** to derive a precise estimate with calculated confidence. The study integrates **Google Earth Pro** for geospatial mapping with physical ground-truth surveys to account for the heterogeneous distribution of foliage across the campus.

## 📄 Full Report
The complete methodology, calculations, and results are detailed in the project report:
👉 **[Read the Full Report (PDF)](./Trees-2.pdf)**

## 🔍 Methodology
The estimation process involved a multi-stage statistical design:

1.  **Digital Mapping:** Used Google Earth Pro to acquire campus boundaries and generate a KML map.
2.  **Stratification:** The campus was segmented into two distinct strata based on foliage density to minimize variance:
    * **High-Density (HD) Stratum:** Continuous forest cover.
    * **Low-Density (LD) Stratum:** Clearings and sparse clusters.
3.  **Grid System:** A $10m \times 10m$ grid overlay was applied to the entire area, creating discrete sampling units.
4.  **Sampling & Estimation:** Random grids were selected from each stratum for physical counting. The final population was estimated using the stratified mean expansion formula.

## 📊 Key Results
* **Total Campus Area Analyzed:** ~8.6 hectares ($86,724 m^2$)
* **High-Density Area:** $76,963 m^2$
* **Low-Density Area:** $9,761 m^2$
* **Final Estimated Population:** **~4,723 Trees**

## 👥 Authors
**Indian Statistical Institute, Bangalore** (Oct 2025)

* **Utkarsh Bharadwaj** (BSD-BG-2521)
* Gagan Krishna S (BSD-BG-2506)
* Saurav Kumar (BSD-BG-2517)

---
*This repository contains the official report submitted for the sampling project coursework.*
