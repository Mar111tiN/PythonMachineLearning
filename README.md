## This is the accompanying jupyter notebook for the book Python Machine Learning by Sebastian Raschka

### SETUP

#### External Data
I have outsourced the data to a dropbox repo so you have to download that folder and install in the repo folder as data. For that, move into your repo root and do this:

`$ curl -L https://www.dropbox.com/s/xb04yz495bzcbje/PythonMachineLearningData.tar.gz?dl=1 > data.tar.gz && tar -xzf data.tar.gz && mv PythonMachineLearningData data && rm data.tar.gz`

#### CONDA environment
For the notebooks to work, you need to setup the appropriate conda environment, which differs between M1 ARM-Macs and Intel-based Macs
The conda environments are placed in the env folder and can be used to re-create the conda environment. 
+ Install conda environment like this (from root folder, shown for Intel-based env-file):
`$ conda env install -f env/PDS-env.yml -n PDS-env'
+ Then, you can enter that environment and start the jupyter notebook server:
+ `$ conda activate PDS-env`
+ `$ jupyter notebook`
