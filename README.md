# Exoplanet Detection and Characterization: Kepler-10b
This project uses NASA Kepler light curve data and Python for the detection and characterization of the exoplanet Kepler-10b.
By analyzing the star’s brightness over multiple time intervals, we detect periodic dips (transits) and calculate the planet’s physical parameters.
---

# Objective
To analyze the light curve of Kepler-10 and detect a transiting exoplanet using:
1. Box Least Squares (BLS) algorithm for period detection
2. Light curve folding to confirm transit events
3. Transit depth-based radius estimation
4. Orbital mechanics to estimate semi-major axis and equilibrium temperature


# Tools & Technologies 
1. Python
2. Lightkurve (Kepler light curve data access)
3. NumPy, Pandas, Matplotlib
4. Google Colab / Jupyter Notebook

   
# Results
| Parameter                | Value               |
|--------------------------|---------------------|
| Orbital Period           | 0.33 days           |
| Transit Depth            | 0.35%               |
| Planet Radius            | 6.85 Earth radii    |
| Semi-Major Axis          | 0.0091 AU           |
| Equilibrium Temperature  | 2676 K              |

The planet appears to be a *hot Neptune-sized object*, orbiting extremely close to its star.

# Author
*Sarthak Singh*
Independent Student Researcher  
India | June 2025

# License
This project is licensed under the [MIT License](LICENSE).
