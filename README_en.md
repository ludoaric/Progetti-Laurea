# Aerospace Engineering Projects Portfolio

Welcome to my portfolio of academic projects and elaborated works, developed during my Master's Degree in Aerospace Engineering at the University of Campania "Luigi Vanvitelli." This repository showcases my technical and analytical skills in various key areas of aerospace engineering, with a particular focus on flight dynamics, control systems, astrodynamics, and numerical analysis.

---

## Key Competencies Acquired:

* **Advanced Control Systems:** Design, tuning, and validation of controllers (PID, LQR, LQI, MPC), attitude estimation and navigation (Linear Kalman Filters), stability, and robustness analysis.
* **Flight Dynamics & Aerodynamics:** Analysis of longitudinal and lateral-directional dynamic stability, modeling of characteristic modes (Phugoid, Short Period, Roll, Spiral, Dutch Roll), Mach critical analysis, preliminary aircraft design, airfoil and finite wing studies, stall phenomena, and corrective solutions (twist, taper ratio).
* **Astrodynamics & Space Systems:** Satellite mission analysis (e.g., Sun-Synchronous orbits, orbital propagation with J2 effects), Ground Track evaluation, and analysis of SAR radar modules (Swath, Doppler effect, integration time).
* **Atmospheric Re-entry & Hypersonic Aerothermodynamics:** Analysis of re-entry corridors and trajectories (ballistic and lifting), evaluation of thermal and structural loads, application of Newtonian theory, and CFD simulations (Ansys Fluent, ICEM CFD).
* **Data Analysis & Statistics:** Descriptive statistics, independence testing, confidence intervals, and multiple regression for predictive modeling.
* **Numerical Modeling & Simulation:** Extensive experience with **MATLAB/Simulink** (advanced), Ansys Fluent (intermediate, CFD), XFoil (intermediate), AVL (intermediate), Abaqus (basic, FEA).
* **Programming:** MATLAB (advanced), basic knowledge of Python and C++.

---

## Detailed Projects:

### **Aerodynamics**

This section includes detailed reports and analyses on the aerodynamic behavior of airfoils and complete aircraft, exploring both theoretical foundations and practical applications.

* **[Hypersonic Aerodynamics (AEIP) Report](AERODINAMICA/elaborato%20AEIP.pdf)**
    * **Content:** Feasibility analysis of a hypothetical space re-entry mission with the Orion capsule. Study of the **re-entry corridor** (thermal limits, dynamic pressure, and aerodynamic limits), and **re-entry trajectories** (ballistic and lifting) using isothermal and standard atmospheric models. Evaluation of thermal fluxes, accelerations, and flight times. Also includes a hypersonic aerodynamic analysis of the **Space Shuttle Orbiter**, comparing results obtained through **Newtonian Theory (Hyper software)** and **CFD simulations (Ansys Fluent, ICEM CFD)**.
    * **Skills:** Hypersonic aerodynamics, atmospheric re-entry, thermodynamics, CFD, numerical analysis, atmospheric modeling, MATLAB.

* **[Aircraft Aerodynamics Report](AERODINAMICA/elaborato_arico_ludovico.pdf)**
    * **Content:** Study of the aerodynamic polars of **NACA 2412 and NACA 632415 airfoils** using **xFoil**, analyzing the effects of Reynolds number, flap and slat deflection. Comparison of results with experimental data (Abbott's tables). Calculation of the **lower critical Mach number** for various airfoils. Application of **Prandtl's lifting line theory (AVL software)** for finite wing analysis (lift distribution, lift loading, induced angle of attack). Evaluation of the **stall path** and corrective solutions (twist, taper ratio). Includes an **Eulerian CFD analysis** of an N2A aircraft.
    * **Skills:** Subsonic and transonic aerodynamics, stall, wing design, airfoil analysis, MATLAB, xFoil, AVL, Ansys Fluent (CFD), mesh generation (ICEM CFD).

### **Flight Control**

Projects focused on the design and simulation of aircraft control systems, including mathematical models and automatic piloting strategies.

* **[Flight Control Systems 2 (SCV2) Project](CONTROLLO%20DI%20VOLO/Progetto_SCV2.pdf)**
    * **Content:** Design and implementation of **LQR (Linear Quadratic Regulator)** and **LQI (Linear Quadratic Integral) controllers** for aircraft stabilization and reference tracking (velocity, pitch angle). Analysis of the system's temporal response to perturbed initial conditions and step inputs. Verification of controller robustness on **nonlinear models** including noise. Details on the selection and impact of `Q` and `R` weighting matrices.
    * **Implementation:** Extensive use of **MATLAB/Simulink** for modeling and simulation.
    * **Skills:** Optimal control (LQR, LQI), dynamic systems, modeling and simulation (Simulink), robustness analysis, stability, dynamic response.

### **Aircraft Dynamics and Design**

Reports exploring dynamic stability analysis, flight modes, and aircraft flight quality, including sensitivity studies and perturbation analyses.

* **[Aircraft Dynamics and General Design (DPGV) Report](DINAMICA%20E%20PROGETTO%20DI%20VELIVOLI/Elaborato_DPGV_Arico.pdf)**
    * **Content:** Detailed analysis of the **longitudinal and lateral-directional dynamics** of an aircraft (McDonnell Douglas F-4) using stability derivatives and state-space models. Study of **characteristic modes** (Phugoid, Short Period, Roll, Spiral, Dutch Roll) in terms of damping, natural frequency, and phasor representation. Analysis of **flight quality** according to standards (e.g., MIL-STD levels). Study of the **root locus** with varying static margin. In-depth analysis of **rapid roll maneuvers** and inertial coupling (Philips diagram), and response to **atmospheric turbulence** (instantaneous and 1-cos gusts, Wind Shear).
    * **Skills:** Flight dynamics, stability and control, flight mode analysis, flight quality, sensitivity analysis, dynamic simulation.

### **Probability and Statistics for Engineering**

This project demonstrates the application of statistical and data analysis methodologies, fundamental skills for engineering, particularly in contexts where uncertainty management and predictive modeling are crucial.

* **[Probability and Statistics Exam Project](PROBABILITA'%20E%20STATISTICA/progetto_1_2.pdf)**
    * **Content:** Statistical analysis of a dataset (real estate data) through:
        * **Descriptive Statistics:** Description of variables, analysis of distributions (e.g., number of floors, bathrooms, fireplaces), calculation of central tendency and dispersion measures (minimum, maximum, mean, standard deviation).
        * **Hypothesis Testing:** Conducting independence tests between variables (e.g., bathrooms and fireplaces) and hypothesis tests on the mean between two populations (based on ZIP codes).
        * **Confidence Intervals:** Calculation and interpretation of confidence intervals to estimate population parameters.
        * **Multiple Regression:** Construction and evaluation of a multiple regression model to predict the total value of a property, analyzing variable significance (p-value) and model fit (R-squared).
    * **Technologies:** All analyses and graphical visualizations (histograms, boxplots, scatter plots) implemented using **MATLAB**.
    * **Relevance to Aerospace:** The skills demonstrated in this project (data analysis, inferential statistics, predictive modeling) are directly applicable in aerospace for telemetry data management, parameter estimation (e.g., orbit determination), performance analysis, and uncertainty evaluation in complex systems.

### **Space Systems**

This section focuses on the design and analysis of space systems and vehicles, with particular attention to orbital dynamics and sensor operation.

* **[Aerospace Systems 2 (SAS2) Project](SISTEMI%20SPAZIALI/sas2_progetto.pdf)**
    * **Content:** Mission analysis of the **COSMO-SkyMed 1** satellite. Simulation of **orbital propagation** (Keplerian and with J2 effects), and evaluation of the **Ground Track**. Performance analysis of a **SAR radar module** on board the satellite, including calculation of **Swath** (Azimuth and Range), **Doppler effect** (with and without Yaw Steering), beam velocity, and **integration time**.
    * **Skills:** Astrodynamics, orbital mechanics, satellite systems, radar imaging, MATLAB.

---

**Contact:**

For any questions or further information regarding my projects, please feel free to contact me:

* **LinkedIn:** [linkedin.com/in/ludoaric](https://www.linkedin.com/in/ludoaric)
* **Email:** [ludovico.arico@gmail.com](mailto:ludovico.arico@gmail.com)
* **GitHub Profile:** [github.com/ludoaric](https://github.com/ludoaric) (Ensure your GitHub username is correct)