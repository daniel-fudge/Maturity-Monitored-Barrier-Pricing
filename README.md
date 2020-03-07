# Maturity-Monitored-Barrier-Pricing
This repo prices the _"NBC Auto Callable Contingent Memory Income Note"_ described in this [link](https://nbcstructuredsolutions.ca/detailProduit.aspx?lequel=5317#documents).

## Motivation
The motivation for this project was the valuation project of the _"FINE6800X:  Options, Futures and Other Derivative 
Securities"_ course as part of the Schulich MBA and concurrent Financial Engineering Graduate Diploma described [here](https://schulich.yorku.ca/specializations/financial-engineering/). 

## Viewing the Notebook
All of the execution of this repo is in `pricing.ipynb` Jupyter Notebook found [here](pricing.ipynb).  This can be 
viewed directly in GitHub or you can run it by following the instructions below. 

## Running The Notebook
The following instructions are written for a Windows environment but should be extremely similar for Linux or OS X.

1. Clone repo to PC.  If you don't have git installed, you can get it [here](https://git-scm.com/).
```shell script
git clone https://github.com/daniel-fudge/Maturity-Monitored-Barrier-Pricing.git
```

1. [OPTIONAL] Install [Anaconda3](https://www.anaconda.com/distribution/).

1. [OPTIONAL] Create a virtual environment.  Please see this [site](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) for more conda environment information
```shell script
conda update conda
conda create -n mmbp 
conda activate mmbp
conda install ipykernel
conda install jupyter
conda install matplotlib
conda install pandas
conda install seaborn
ipython kernel install --name=mmbp
```
   
1. [OPTIONAL] Activate the virtual environment if not already activated.  Note the above steps only need to be executed 
once.  After initial setup you can start at this step.
```shell script
conda activate mmbp
```

1. Launch Jupyter.
```shell script
cd Maturity-Monitored-Barrier-Pricing
jupyter notebook
```

1. Open the desired notebook.

1. Read and/or run the cells at your leisure!!  :)

## License
This code is copyright under the [MIT License](LICENSE).

## Contributions
Please feel free to raise issues against this repo if you have any questions or suggestions for improvement.
