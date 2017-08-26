# MIST101
Tutorials for MIST101 course

## Installing Dependencies

1. Install Anaconda (https://www.continuum.io/)
2. Open Anaconda Prompt

3. Install Tensorflow
```
conda create -n tensorflow python=3.5 
activate tensorflow
pip install --ignore-installed --upgrade tensorflow 
```

4. Install other dependencies inside the tensorflow virtual environment
```
conda install -c anaconda matplotlib
conda install -c anaconda jupyter
```

5. Run jupyter
```
jupyter notebook
```
