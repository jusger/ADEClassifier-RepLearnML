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

If you are using a different platform, you may be able to just install the required packages:
* numpy 
* pandas 
* scikit-learn 
* matplotlib 
* bokeh 
* jupyter 
* bitarray 
* scipy

All work was done with Python version 3.6.1 on a CentOS machine. Additional testing (with identical results) was found on other architectures.
