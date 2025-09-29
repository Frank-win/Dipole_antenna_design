*DIPOLE ANTENNA*
(Frequency 3.3GHz) 

Project Overview

The repository contains the design and simulation files for a dipole antenna operating at 3.3 GHz, the geometry design, solver setup and performance analysis details can be found in this repository.

🛠 Softwares Used
Excel - for results processing 
ANSYS HFSS -  for design and simulation of performance analysis of the software

📂 Repository Contents

hfss_project folder -- containing zipped file of full design setup

dipole-hfss folder containing models and results of the simulation

dipole_antenna.aedt --- HFSS project file

dipole_geometry.step --- exported 3D geometry (STEP format)

dipole_geometry.sat --- exported 3D geometry (SAT  format)

dipole_geometry.iges --- exported 3D geometry (IGES  format)

solver_settings.txt --- solver setup (frequency range, boundary conditions, mesh, etc.)

s11_plot.png --- return loss plot (S11 vs frequency)

s11_data.csv --- exported S11 data

vswr_plot.png --- 

vswr_data.csv -- exported VSWR data

results_plots -- folder with plots

dipole_antenna.png --- dipole_antenna image 

simulation settings text 

README.md → project documentation


📈 Results

The antenna was designed for 3.3 GHz operation.

Simulation results include return loss (S11) and radiation patterns.

Geometry and settings are provided so others can reproduce the design.

📝 Notes

The Results from the far firled radiation pattern and the gain value indicates it is omni-directional

Results may vary depending on mesh settings and boundary conditions.

Contributions and suggestions are welcome.