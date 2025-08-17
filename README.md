# Using-SVD-to-Analyse-Spatio-temporal-Patterns-in-Atmospheric-Pressure.
# Singular Value Decomposition (SVD) Analysis of Pressure Field in Space and Time  

This repository contains a **Jupyter Notebook** that applies **Singular Value Decomposition (SVD)** to analyze pressure field data across both space and time. The objective of this project is to extract dominant modes, identify coherent structures, and study the temporal evolution of flow characteristics from simulation or experimental data.  

---

## 📌 Project Description  

Understanding the dynamics of pressure fields is crucial in many areas of computational fluid dynamics (CFD) and experimental flow analysis. Complex flow structures often exhibit dominant modes of oscillation or coherent patterns that can be effectively captured using **Singular Value Decomposition (SVD)**.  

This project demonstrates the use of SVD for **modal decomposition of pressure data**. Given spatiotemporal datasets (pressure recorded across spatial points over time), the notebook performs the following steps:  

1. **Data Preparation:** Organizes pressure data into a suitable space-time matrix.  
2. **Singular Value Decomposition (SVD):** Decomposes the data matrix into orthogonal modes, separating spatial and temporal contributions.  
3. **Energy Contribution:** Identifies the most energetic modes and quantifies their percentage contribution.  
4. **Mode Analysis:**  
   - **Spatial Modes (Left Singular Vectors):** Capture spatial distribution patterns of pressure fluctuations.  
   - **Temporal Modes (Right Singular Vectors):** Capture time-dependent evolution of the corresponding spatial modes.  
   - **Singular Values:** Indicate the relative strength/energy of each mode.  
5. **Visualization:**  
   - Plot of singular value spectra (to identify dominant modes).  
   - Spatial structures of key modes.  
   - Temporal evolution of selected modes.  

Through this approach, one can uncover underlying physics in flow fields, such as periodic vortex shedding, coherent structures, and transient pressure fluctuations.  

This method has strong applications in:  
- Reduced-order modeling of CFD simulations  
- Data-driven flow analysis  
- Feature extraction for turbulence research  
- Identifying dominant dynamics in unsteady flows  

By combining space and time decomposition, this notebook provides both **qualitative insights (patterns and modes)** and **quantitative measures (energy contribution of modes)** for pressure field analysis.  

---

## ⚙️ Features  
- Preprocessing of spatiotemporal pressure field data  
- SVD-based modal decomposition  
- Energy ranking of modes  
- Visualization of spatial and temporal modes  
- Useful for CFD post-processing and experimental analysis  

---

## 🔧 Requirements  
Make sure you have the following installed:  
```txt
numpy  
matplotlib  
scipy  
jupyter  

##Installations
git clone https://github.com/<your-username>/SVD-Pressure-Analysis.git
cd SVD-Pressure-Analysis

jupyter notebook SVD_Pressure_SpaceAndTime.ipynb

