# Toy_DataAssimilation

#### ==================================================================================
This notebook is intended to give a really easy introduction into data assimilation using
the 4DVAR method, focusing on the fundamentals of forming an tangent linear model, using 
a forward Euler time stepping schem. It is performed first on the logisitic growth problem
then on a Lorenz '63 model. 

We use Jupyter notebooks to drive the python code. The instructions for a setting up a jupyter 
environment that will work for this project are below. Please contact me with any issues: 

wchapman@ucsd.edu

Big thanks to Aneesh Subramanian, and Bruce Cornuelle for some fundamental underpinnings of this project. 
#### ==================================================================================

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


# Then start a Jupyter Notebook

## command line: 
#### step 4
jupyter notebook 

#### ==================================================================================

#### step 5
This will open a browser window showing your computers file architecture. Select "Adjoint Model for Data Assimilation.ipynb"

a notebook will open, and change the kernel to AdjLorenz [kernel > change kernel > Python2.7 (AdjLorenz)]




Use 'shift + enter' to run each cell in the notebook.  



