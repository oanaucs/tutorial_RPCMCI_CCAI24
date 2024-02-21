# Tutorial for the Climate Change AI Workshop at ICLR24 on Using Regime Causal Discovery for Understanding Anomalous Events, with Application to the Soil Moisture Problem

## Required python packages

Python version >=3.9

| Name    | Version | License | Purpose |
| -------- | ------- | ------- | ------- |
| ipykernel | 6.29.0  | BSD License | |                                                     
| ipython | 8.15.0 | BSD License | |                                                                                 
| jupyterlab | 4.0.12 | BSD License | |
| pandas  | 2.2.0    | BSD License | data manipulation |
| scikit-learn | 1.4.0    | BSD License | prediction methods |
| scipy    | 1.12.0  | BSD License | |
| numba    | 0.56.4  | BSD License | |
| numpy    | 1.23.5  | BSD License | |
| matplotlib    | 3.8.2 | BSD License | plotting |
| networkx    | 3.2.1 | BSD License | plotting |
| seaborn    | 0.13.2 | BSD License | plotting |
| ortools  | 9.8.3296 | Apache Software License | optimization algorithms required for RPCMCI |                                      
| tigramite | 5.2.5.0 | GNU General Public License v3 or later (GPLv3+) | causal inference methods |


## Authors and acknowledgment
*   Oana-Iuliana Popescu, [1], oana.iuliana.popescu@gmail.com
*   Wiebke Günther, [1], [2], wiebke.guenther@dlr.de
*   Raed Hamed, [3], raed.hamed@vu.nl
*   Martin Rabel, [1], martin.rabel@dlr.de 
*   Dim Coumou, [3], d.coumou@vu.nl
*   Jakob Runge, [2], [1], Jakob.Runge@dlr.de 

[1] German Aerospace Center (DLR), Institute of Data Science, 07745 Jena, Germany\
[2] Technische Universität Berlin, 10623 Berlin, Germany\
[3] Institute for Environmental Studies, Vrije Universiteit Amsterdam, Amsterdam, Netherlands

We thank the XAIDA Project and Martin Hirschi and Dominik Schumacher for making the soil moisture dataset publicly available at https://xaida.eu/reports-datasets/. 


## License
The code for RPCMCI (rpcmc.py) was adapted from Tigramite (original authors: Elena Saggioro, Sagar Simha, Matthias Bruhns, Jakob Runge).
We included functionality for missing data (Authors: Oana Popescu, Wiebke Günther).
This adapted code for RPCMCI is published under the GNU General Public License v3.0.

The tutorial code (notebook) is published under the MIT license.


## Running the tutorial from Colab

The tutorial can be found at the following link: https://colab.research.google.com/drive/1I0ZVaJeSqCQLRhZZUyoGaLrSbPI0N-8j?usp=sharing. 


## Running the tutorial using Jupyter Notebook 

Install the requirements from the ``requirements.txt`` file, then run the ``tutorial.ipynb`` notebook. 
