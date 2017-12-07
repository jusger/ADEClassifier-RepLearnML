# CbA-ESP
Classification-by-Analogy with Embeddings of Semantic Predications for a JAMIA submission

For installation (assuming \*nix and that you have the Anaconda Python distribution installed):
```
git clone https://github.com/neophytescientist/CbA-ESP
cd CbA-ESP
tar -xzvf cbaesp.tar.gz
conda env create -n [yournamehere] -f cbaesp.yml
source activate [yournamehere]
jupyter notebook
```

Alternatively, if you are using a different platform or the yml file doesn't work for some reason, you can just install the required packages:
* numpy 
* pandas 
* scikit-learn 
* matplotlib 
* bokeh 
* jupyter 
* bitarray 
* scipy

e.g.:

```
conda create -n [yournamehere]
source activate [yournamehere]
conda install numpy pandas scikit-learn matplotlib bokeh jupyter bitarray scipy
```

All work was done with Python version 3.6.1 on a CentOS machine. Additional testing (with identical results) was found on other architectures.
