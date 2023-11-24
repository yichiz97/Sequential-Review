# Eliciting Honest Information From Authors Using Sequential

This is the Python implementation of the simulation results of the paper under the same title. 

## Guide of Usage
First, to run our codes, packages including NumPy, SciPy, Random, and Matplotlib are required for plotting. All of the experiments are implemented on JuPyter Notebook version 6.1.4. with Anaconda Navigator 1.10.0 and Python 3.8.5.

The roles of the Python files are:
* "**Gaussian_model.ipynb**" includes the code for generating the simulation results for the Gaussian review noise model discussed in Section 5.2;
* "**Real-data.ipynb**" contains the code for estimating the Softmax review noise model with the ICLR datasets and for generating the simulation results in Section 5.3.

The "**Numerical_results**" folder saves some intermediate results that may take hours to run. For those experiments, users could skip the codes that are used to generate these results.
