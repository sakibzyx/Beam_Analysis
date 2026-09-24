# Beam Analysis and Deflection Calculation Using Python

A Python-based structural analysis project for calculating and visualizing support reactions, SFD, BMD, beam deflection, and slope profiles for various beam configurations using `NumPy`, `SciPy`, `SymPy`, and `Matplotlib`.

---

## Features

- **Reaction Calculations:** Evaluates support reactions using static equilibrium equations ($\sum F_x = 0$, $\sum F_y = 0$, $\sum M = 0$).
- **Shear Force & Bending Moment Analysis:** Computes Shear Force and Bending Moment using `NumPy`.
- **Shear Force & Bending Moment Diagrams (SFD & BMD):** High-resolution visual diagrams with filled areas and clear baseline indicators via `matplotlib`.
- **Governing Differential Equation Solvers:** Computes elastic curve deflection and slope using `scipy.integrate.odeint` and boundary value solvers.
- **Support for Varied Loading & Boundaries:**
  - Cantilever and Simply Supported Beams
  - Point Loads (Concentrated Loads)
  - Uniformly Distributed Loads (UDL)
  - Variedly Distributed Loads (VDL)
  - Concentrated Moments / Couplings

---

## Project Structure

```text
beam_analysis/
│
├── beam1.ipynb             # Support reactions, SFD, and BMD under combined UDL & point loads
├── beam2.ipynb             # Multi-segment beam analysis with discrete distributed loads
├── beam3.ipynb             # Overhanging/supported beam with UDL and applied concentrated moment
├── deflection1.ipynb       # Numerical deflection profile for a cantilever beam under UDL
├── deflection2.ipynb       # ODE integration for simply supported beam deflection
├── deflection3.ipynb       # Deflection analysis under concentrated load conditions
├── deflection4.ipynb       # Combined dual-plot of Deflection profile ($y$) and Slope/Rotation profile ($\theta$)
├── simple_point_load.ipynb # Single point load benchmark test case
├── simple_udl.ipynb        # Standard full-span UDL benchmark test case
└── README.md               # Project documentation

```

---

## Author

**Md Sakibul Hasan**  
BSc in Civil Engineering, Dhaka University of Engineering & Technology (DUET)  

📨 **Email:** [sakib.zyx@gmail.com](mailto:sakib.zyx@gmail.com)
