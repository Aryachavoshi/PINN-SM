# PINN-SM: Physics-Informed Neural Networks for Soil Moisture Prediction

## Overview

This repository contains the code and data for the PINN-SM (Physics-Informed Neural Networks for Soil Moisture) model. PINN-SM is designed to predict root zone soil moisture profiles from the surface to a depth of 100cm.

## Model Description

PINN-SM leverages physics-informed neural networks to predict soil moisture content (m³/m³) based on various environmental and meteorological inputs. The model takes into account both current conditions and historical data to make accurate predictions.

### Inputs:
- Time
- Depth
- Near-surface air temperature (°C)
- Precipitation flux (mm/hr)
- Wind speed (m/s)
- Enhanced Vegetation Index (EVI)
- Cumulative rainfall values for the previous 10, 20, 30, ..., 100 time steps

### Output:
- Current soil moisture value (m³/m³) at the specified time and depth

## Repository Contents

1. `PINN-SM.ipynb`: Jupyter notebook containing the code for training and testing the PINN-SM model.
2. `training.csv`: Dataset used for training and testing the model, containing meteorological and soil-related variables.

## Data Source

The data used in this study was collected from a field laboratory located at the Brackenridge Laboratory of The University of Texas at Austin, Austin, Texas. This dataset provides a comprehensive set of environmental variables necessary for soil moisture prediction in a real-world setting.

## Usage

To use this model:

1. Clone the repository
2. Install the required dependencies (list of dependencies to be added)
3. Open the `PINN-SM.ipynb` notebook in Jupyter
4. Follow the instructions within the notebook to train and test the model

## Citation

If you use this model or dataset in your research, please cite our work (citation details to be added upon publication).

## License

(Add appropriate license information)

## Contact

For questions or collaborations, please contact (your contact information or preferred method of contact).
