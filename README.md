# OCGLab_STORM-Analysis

Code for analysis of STORM data, as used in Medeiros, et al 2023.

If you have `conda` (e.g. with the Anaconda python distribution), install dependencies from a terminal via
```shell
conda create -f environment.yml
```

A second environment file, `environment_minimal.yml`, contains just the required packages without version numbers, in case 
you would like to try to run with the most recent packages. The notebook has been tested in the environment from the full 
file on MacOS.

Then you can run the notebook using Jupyter Lab, or in a classic Jupyter notebook GUI
```shell
jupyter notebook
```

Expects to find data files `20220526_L1_NMJ1_A2R67_DBSCAN_v2.xlsx` and `MAX_20220526_CacHalo_JF646_L1_A2R67_000.nd2 - 
C=0.png` in the current directory where the code is being run.

All code is provided as is, with no warranties of any kind. Use at your own risk.
