# AI and FEA Based Design & Analysis of Efficient EV Motors

## Project Overview
This project focuses on the optimization of synchronous reluctance motor rotors for Electric Vehicles (EVs). By combining Finite Element Analysis (FEA) data with Machine Learning techniques, this project aims to predict and optimize average torque and torque ripple, improving overall motor efficiency.

## Technologies & Tools Used
* **Languages:** Python
* **Machine Learning:** Scikit-learn (Random Forest Regressor)
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib
* **Domain:** Electrical Engineering, Finite Element Analysis (FEA)

##  Repository Contents
* `Finalyear_project.ipynb`: The core Jupyter Notebook containing the machine learning pipeline. It processes rotor design parameters (H, W, R, Rb, B0) and trains a Random Forest model to predict average torque and torque ripple, outputting an optimized rotor design.


##  Key Results
* Successfully trained a regression model to predict motor performance based on physical geometry parameters.
* Generated an optimized rotor design profile (Detailed in the notebook output) that balances maximum average torque with minimal torque ripple.
