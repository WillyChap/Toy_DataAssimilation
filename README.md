# Toy_DataAssimilation



To run please follow these instructions: 


Download Anaconda: 
https://www.anaconda.com/distribution/

Create this anaconda environment (more on environments here: https://docs.conda.io/projects/conda/en/latest/user-guide/concepts/environments.html) 






## In Your Command line: 

conda create -n AdjLorenz python=2.7 numpy matplotlib ipykernel

source activate AdjLorenz    ####[if this command doesn't work try: "conda activate AdjLorenz"]

python -m ipykernel install --user --name AdjLorenz --display-name "Python2.7 (AdjLorenz)"




# Then start jupyter

## command line: 

jupyter notebook 

This will open a browser window showing your computers file archetecture. Select "Adjoint Model for Data Assimilation.ipynb"

a notebook will open, and change the kernel to AdjLorenz [kernel > change kernel > Python2.7 (AdjLorenz)]
