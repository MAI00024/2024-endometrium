## Paper
**Prediction of final pathology depending on preoperative myometrial invasion and grade assessment in low-risk endometrial cancer patients**  
PLOS ONE (2024). https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0305360

# File Description
```
├── data
│   ├── train.csv
│   └── label.csv
├── 1_skcv5_model_only_g1_v8-NPM1.ipynb
└── 1_skcv5_model_only_g1_v10-NPM2.ipynb
```

### SOFTWARE (python packages are detailed separately in `requirements.txt`):
* Python 3.7.13 
* CUDA 12.1 
* nvidia drivers v.531.14 

# Setup
The code is tested for Python 3.7.13 and the packages listed in environment.yml. The basic requirements are Tensorflow. The easiest way to get going is to install the conda environment via
```
conda env create --file environment.yml
conda activate tf
```
Install the packages with the command below.
```
pip install -r requirements.txt
```

# Run
Run all cells at once for the notebooks below
* NPM1: 1_skcv5_model_only_g1_v8-NPM1.ipynb
* NPM2: 1_skcv5_model_only_g1_v10-NPM2.ipynb

