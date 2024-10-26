# PINN-SM: Physics-Informed Neural Networks for Soil Moisture Prediction
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXXX)
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

## Requirements

- Python 3.x

## Usage

To use this model:

1. Clone the repository
2. Install the required dependencies (list of dependencies shown in the first block of code)
3. Open the `PINN-SM.ipynb` notebook in Jupyter
4. Follow the instructions within the notebook to train and test the model

## Citation

If you use this model or dataset in your research, please cite our work (citation details to be added upon publication).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) [2024] [Arya Chavoshi]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Contact

For questions or collaborations, please contact (arya.chavoshi@utexas.edu).
