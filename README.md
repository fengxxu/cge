# Counterexample-Guided Evaluation for Neural Network Verification

Paper: On the Soundness and Completeness of Neural Network Verification Tools

**Framework:**
<p align="center">
<img src="https://github.com/fengxxu/cge/blob/master/images/structure.png?raw=true" alt="Structure" width="600">
</p>

**Soundness and Completeness**
<p align="center">
<img src="https://github.com/fengxxu/cge/blob/master/images/sandc.png?raw=true" alt="Structure" width="600">
</p>
## How to run

**Firstly, clone the rep:**
```bash
git clone https://github.com/fengxxu/cge.git
cd cge
unzip benchmarks.zip
```
**Secondly, create a new environment, or skip to the next step:**

For example, using conda ([How to install](https://docs.conda.io/projects/miniconda/en/latest/))

```bash
conda create --name cge python=3.10
conda activate cge
```

**Thirdly, install the libraries:**

Choice 1: Please note the libraries in the requirements.txt file are used for running the verifiers and CGE, 
```bash
conda install --file requirements.txt
```
Choice 2: for CGE only, run the following commands.
```bash
conda install -c anaconda jupyter
conda install -c anaconda pandas
conda install -c conda-forge onnxruntime
conda install -c anaconda numpy
pip install z3-solver
```
**Lastly, open the main.ipynb, select the correct kernel for the notebook, following instructions in the notebook to replicate the experiment**

