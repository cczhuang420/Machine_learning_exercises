## How to run and use this repo?
### Machine_learning_exercises
`1. conda create --prefix ./env numpy matplotlib pandas scikit-learn`
`2. conda activate ./env`

### Check the env list
`conda env list`

### Check all the tools 
`conda list`

## Steps of creating a Machine Learning (or Data Science) Project (Mac):
1. Download miniconda (or anaconda) and install it on the local computer. 
https://docs.conda.io/en/latest/miniconda.html#macos-installers
1. Test the installation in the terminal: $which conda
1. Create a project folder and run: $cd project folder
1. Create a custom environment within the project folder: (i.e.) $ conda create --prefix ./env numpy matplotlib pandas scikit-learn jupyter
1. Activate the new environment by running: $conda activate)
1. Load up a Jupiter Notebook and check the tool we need: $jupyter notebook
<br/>

![image](https://github.com/cczhuang420/Machine_learning_exercises/assets/55259980/2b9ed758-3e0d-4a58-bc72-1d51420ba729)

## Share environment (two ways):

1. share the entire project folder, including the environment folder containing all required packages.
   * Simply only need to activate the environment and run the code.
3. share a `.yml` file of the conda environment
   * first export the env: ` conda env export --prefix ./env > environment.yml`
   * others to create the same env based on this environment.yml file: `conda env create --file environment.yml --name env_from_file`

