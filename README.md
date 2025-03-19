# Mirror Objective with Lens Corrector

## Overview
This repository contains a course project on the design and optimization of a mirror objective with a lens corrector. Developed as part of the "Applied Optics" course at Moscow State Technical University of Bauman, the project involves detailed calculations and simulations to create an optical system that combines a two-mirror Cassagrain configuration with a dual-lens afocal corrector (Churilovsky corrector) and a Smith lens for field curvature correction.

## Project Description
The project is divided into several key sections:

1. **Cassagrain Telescope System Calculation**  
   - **Objective:** Calculate the geometrical parameters of a two-mirror (Cassagrain) system.
   - **Details:** Includes determining the primary mirror diameter, equivalent focal length, mirror separations, and other optical parameters necessary for the initial design.

2. **Churilovsky Corrector Calculation**  
   - **Objective:** Design a two-lens afocal corrector that compensates for coma without introducing chromatic aberrations.
   - **Details:** The corrector is based on equal but opposite optical powers, ensuring the system remains apochromatic.

3. **Smith Lens Calculation**  
   - **Objective:** Correct the curvature of the image surface using a single lens.
   - **Details:** The Smith lens not only corrects field curvature but, with proper surface rounding, can also reduce distortion.

4. **System Optimization**  
   - **Objective:** Optimize the overall optical design using Zemax software.
   - **Details:** The design is fine-tuned by adjusting parameters to minimize aberrations (e.g., coma, field curvature) and ensure high image quality.

5. **References**  
   - The report cites classic texts and papers on optical system theory and design, forming the basis for the calculations and design methods used.

## Analysis Summary
This project provides a comprehensive analysis of an optical system that combines both reflective and refractive elements. The key aspects include:
- **Detailed Calculations:** The derivation of system parameters such as mirror diameters, focal lengths, and distances between optical elements.
- **Aberration Correction:** Implementation of the Churilovsky corrector and Smith lens to address common optical aberrations such as coma, chromatic aberration, and field curvature.
- **Optimization Techniques:** Use of Zemax to simulate and refine the design, ensuring that the final system meets stringent imaging performance criteria.

## Technologies and Tools
- **Optical Design Software:** Zemax for system simulation and optimization.
- **Calculation Tools:** Detailed manual computations based on optical theory.
- **Documentation:** The project report was prepared using Microsoft Word.

## Getting Started
To explore or modify this project:
1. **Clone the Repository:**  
   ```bash
   git clone https://github.com/yourusername/mirror-objective-with-lens-corrector.git
   ```
2. **Review Documentation:**  
   The project report (in PDF) provides a comprehensive explanation of the design and calculations.
3. **Run Simulations:**  
   Use Zemax or a comparable optical design tool to replicate the simulations and further optimize the system if desired.

## References
1. N.P. Zakaznov et al., *Theory of Optical Systems*.
2. N.N. Michelson, *Optics of Astronomical Telescopes and Their Calculation Methods*.
3. Yu.Yu. Kachurin, A.V. Kryukov, A.A. Karateeva, *Optical Layout Based on Calculations in ZEMAX*.
