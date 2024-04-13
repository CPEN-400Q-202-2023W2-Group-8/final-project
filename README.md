# CPEN-400Q-2020-2023W2-Group-8 final-project

This Jupyter notebook (QCBM_Final.ipynb) demonstrates the implementation of a Quantum Circuit Born Machine (QCBM) using the PennyLane library. The project focuses on replicating various data distributions and training QCBMs with different numbers of qubits.

To run the code make sure that you have the following dependencies installed.

```python
import pennylane as qml
from pennylane import numpy as np
import matplotlib.pyplot as plt
from tqdm.notebook import tqdm
import json
import pandas as pd
```

The best way to run this file is in google collab, where one can run all in a CPU runtime to make everything work.

For more details on the usage and implementation, refer to the comments and examples provided in the QCBM_Final.ipynb notebook.

## Notable Files

The repository contains several important files that contribute to the project:

- **CPEN400Q.Companion report.pdf**: This document is the Companion report to the paper https://arxiv.org/abs/2307.03292v2.

- **MidtermCheckpoint.pdf**: This is the midterm report which summarizes the paper we wanted to emulate.

- **QCBM_Final.ipynb**: A Jupyter Notebook that contains the implementation of the QCBM, including code for generating data distributions, defining the quantum circuit ansatz, and training the model.

- **generated_data_for_figures.json**: This JSON file contains the data used to generate figures for the project's report. This can be used to replicate FIG 2-6 using the helper functions listed in the notebook.

## Contributions
Shashi [@shashi981](https://github.com/shashi981): Wrote the code for modified optimizer functions and associated helper functions, Implemented the code to plot FIG 2 for 300 iterations, Implemented the code to plot FIG 7-8, Documented certain sections of the code, wrote the Reproducibility section of the report. 

So [@sonozaki7](https://github.com/sonozaki7): wrote all target distribution code, wrote the report theory, and result section.

Ore [@oreade16](https://github.com/oreade16): wrote all the ansatze functions, and the framework section. Also helped to review the report

Akshat [@DentedGem](https://github.com/DentedGem): Wrote the code for the qcbm, loss, optimizer, figure_creator functions and the associated helper functions. Implemented code for FIG 2-6 and Table 2, Documented the code base and formatted the code base. Wrote the opinion piece of the code as well as helped review the report.
