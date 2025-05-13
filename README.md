# EcoliMetabolism

<p align="center">
  <img src="./imgs/360_F_1072678929_GDtHyPEMnaJsPkAOSFAh21pRLe8OFOpu.jpg" alt="alt text" width="1100px" align="middle"/>
</p>

This is a project in collaboration with Aniruddha Chatturaj and Eugene Shakhnovich based on the work by Alexander Kroll.  

It takes a SMILES encoding of a substrate and an encoding of an enzyme and returns a Kcat and Km prediction. Please run the wrapper.ipynb with your desired substrate and enzyme (and encoding) for the Kcat and Km result.  


## Installation 
Requirements for running the code in this GitHub repository.
```
python 3.7.7
tensorflow 2.3.1
jupyter
pandas 1.3.0
torch 1.7.1
numpy 1.21.2
rdkit 2020.09.1
fair-esm 0.3.1
py-xgboost 1.3.1
matplotlib 3.4.1
hyperopt 0.25
sklearn 0.22.1
pickle
Bio 1.78
re 2.2.1
drfp 0.3.6
zeep 4.2.1
```

The listed packaged can be installed using conda and anaconda and pip:

```
pip install torch
pip install numpy
pip install tensorflow
pip install fair-esm
pip install jupyter
pip install matplotlib
pip install hyperopt
pip install pickle
pip install biopython
pip instal drfp
pip install zeep
conda install pandas=1.3.0
conda install -c conda-forge py-xgboost=1.3.3
conda install -c rdkit rdkit
```

Alternatively, you can install all of these packages with the yaml file:

```
pip install kinetics.yaml
```

