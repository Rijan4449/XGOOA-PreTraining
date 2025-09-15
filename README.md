# XGOOA-PreTraining
This repository contains pre-processing and cleaning scripts for the XGOOA dataset used for machine learning experiments.


  
### Repository Structure
XGOOA-PreTraining/  
│  
├── Drop_rows/            
├── Imputation/          
├── MinMax/              
├── Standardization/     
├── check_dataset.ipynb  
└── README.md            

**Description of Folders**

* Drop_rows: Contains dataset_v2 and its notebook showing rows dropped during cleaning.

* Imputation: Contains scripts for imputing missing values in datasets.

* MinMax: Contains datasets and scripts after applying Min-Max scaling.

* Standardization: Contains datasets and scripts after standardization.

  
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
