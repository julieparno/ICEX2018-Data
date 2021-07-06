# ICEX2018-Data
Data to accompany the manuscript "Observations of Stress-Strain in Drifting Sea Ice at Floe Scale"



## Model
A linear elastic finite element model is used in the manuscript to help assess if the ice was behaving in a linear elastic regime or not.  The jupyter notebook `model/LinearElasticSimulation.ipynb` implements this model and computes the Bayesian p-values reported in the paper.

### Dependency Installation
The model is implemented in implemented in Python with the [Fenics](https://fenicsproject.org/) finite element package.  An anaconda environment with all necessary dependencies can be created using the following commands:
```
conda create --name icex-model
conda activate icex-model
conda install -c conda-forge fenics scikit-learn mshr matplotlib
pip install jupyterlab
```
