# XGOOA-PreTraining
This repository contains pre-processing and cleaning scripts for the XGOOA dataset used for machine learning experiments.


  
### Repository Structure
XGOOA-PreTraining/  
│  
├── Drop_rows/           # Scripts and datasets where rows were dropped for cleaning  
├── Imputation/          # Scripts and files for handling missing values  
├── MinMax/              # Min-Max normalization of datasets  
├── Standardization/     # Standardization of datasets  
├── check_dataset.ipynb  # Notebook for checking datasets  
└── README.md            # This file  


  
### How to Use

1. Clone the repository:

```
git clone https://github.com/your-username/XGOOA-PreTraining.git
```

2. Navigate to the desired folder and open the corresponding notebook to inspect or run the preprocessing steps.


3. Make sure you have required Python packages installed:

```
pip install -r requirements.txt  # if you have a requirements file
```
  
**Notes**

* Each folder contains the most recently finalized dataset for that preprocessing step.

* Use check_dataset.ipynb to explore datasets and verify the results of preprocessing.
