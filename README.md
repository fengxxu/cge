# Counterexample-Guided  Evaluation for NN verification

Paper: On the Soundness and Completeness of Neural Network Verification Tools


## How to run

**First clone the rep:**
```bash
git clone https://github.com/fengxxu/cge.git
cd cge
unzip benchmarks.zip
```
**Secondly, create a new environment, or skip to next step:**

For example, using conda

```bash
conda create --name cge python=3.10
conda activate cge
```

**Thirdly, install the libraries:**

choice 1: please note the libraries in the requirements.txt file are used for running the verifiers and CGE, 
```bash
conda install --file requirements.txt
```
choice 2: for CGE only, run the following code.
```bash
conda install -c anaconda jupyter
conda install -c anaconda pandas
conda install -c conda-forge onnxruntime
conda install -c anaconda numpy
pip install z3-solver
```
**Lastly, open the main.ipynb, select the correct kernal for the notebook, following instructions in the notebook to replicate the experiment**

