# Toy_DataAssimilation



To run please follow these instructions: 


Download Anaconda: 
https://www.anaconda.com/distribution/

Create an anaconda environment (more on environments here: https://docs.conda.io/projects/conda/en/latest/user-guide/concepts/environments.html) 





#### ==================================================================================

## In Your Command line: 

#### step 1
conda create -n AdjLorenz python=2.7 numpy matplotlib ipykernel

#### step 2 

source activate AdjLorenz    

#### [if this command doesn't work try: "conda activate AdjLorenz"]

#### step 3 
python -m ipykernel install --user --name AdjLorenz --display-name "Python2.7 (AdjLorenz)"


# Then start jupyter

## command line: 
#### step 4
jupyter notebook 

#### ==================================================================================

This will open a browser window showing your computers file archetecture. Select "Adjoint Model for Data Assimilation.ipynb"

a notebook will open, and change the kernel to AdjLorenz [kernel > change kernel > Python2.7 (AdjLorenz)]
