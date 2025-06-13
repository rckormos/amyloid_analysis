# amyloid_analysis
Analyze structural similarity of overlapping residue windows between two 
amyloid structures.

### Using the repository
To use the notebook in this repository, you will need to have a Python 
environment with the `numpy`, `prody`, `matplotlib`, and `jupyter` 
libraries installed. It is recommended that you use 
[Anaconda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/macos.html)
to set up your Python environments, but this is not strictly necessary. 
After you have either activated a conda environment or decided to install to 
your default Python environment, use the following command to install the 
correct packages:

```bash
> pip install numpy prody matplotlib 
```

You may then open the Jupyter notebook with:

```bash
> jupyter notebook
```

Within the notebook, navigate to `amyloid_rmsd_analysis.ipynb` and select it 
to begin. Enter the paths to your PDB files under the "file entry" header and 
continue executing cells to analyze your structures.
