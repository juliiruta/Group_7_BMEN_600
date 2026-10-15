# Group_7_BMEN_600
BMEN 600 Term Project
Team 7
Julii Ruta, Ashley Pehar, Sophia Hall, and Madalyn Arsenault

Biomedical Problem: Affect of hormonal birth control on gene expression related to maintenance of extracellular matrix (ECM).

Potential Research Question: Does hormonal contraceptive use alter expression of extracellular matrix (ECM) genes in endometrial tissue compared with a non-hormonal control subset?

Open Data Set: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE137765&utm

Biggest Uncertainty: This data set is relatively small, therefore it may have limited detection of subtler differences.

Probe ID Numbers to Gene Codes/Names: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GPL6244 (Data table at bottom of page) 

Project Decision: 
GO - We are proceeding with this research question and dataset.

Project Plan: 

<img width="590" height="707" alt="Screenshot 2026-10-02 at 1 58 52 PM" src="https://github.com/user-attachments/assets/a0ba5616-9589-4445-a20b-f5b115deb665" />


<img width="591" height="614" alt="Screenshot 2026-10-02 at 1 59 24 PM" src="https://github.com/user-attachments/assets/4529ec08-f531-4bf7-bef9-31d5e21a7ef7" />


**Repository Structure**

The repository contains the following files:

```
Group_7_BMEN_600/
├── Project_README.md
├── Notebooks/
│   ├── BMEN_600_Table_Data.ipynb
│   └── README.md*
└── References/
    ├── Gene Symbol to Gene Names.pdf
    └── README.md*
```

1. Project_README.md — Project overview, research question, dataset sources, and project progress.

2. Notebooks Folder  --> BMEN_600_Table_Data.ipynb — Python notebook containing the current data-processing and analysis workflow.

3. References Folder --> Gene Symbol to Gene Names.pdf — Supporting reference for gene symbol and gene name identification.

*README.md files in folders supply folder descriptions only

**Dataset Access**

The gene expression dataset is available through the NCBI Gene Expression Omnibus (GEO):

Gene expression dataset: GSE137765

Probe annotation platform: GPL6244

The required data files can be accessed through these resources. Large data matrices and probe ID files are not included in the repository because they exceed the permitted upload size. The notebook documents the work performed using these files.

**Software and Requirements**

The analysis is conducted using Python in a Jupyter Notebook environment through Google Colab.

Required Python packages depend on the operations performed in the notebook and may include:

- NumPy for numerical operations.

- Pandas for data manipulation and analysis.

- Matplotlib for data visualization, if used.
  
- Additional packages as required by the analysis.

**How to Run the Current Progress Check**

1. Open BMEN_600_Table_Data.ipynb from the repository.

2. Open the notebook in Google Colab or a compatible Jupyter Notebook environment.

3. Obtain the required gene expression data and probe annotation files using the dataset links above.

4. Upload or connect the required files to the notebook environment and update file paths as needed.

5. Run the notebook cells in order to reproduce the completed data-processing steps and available outputs.

**Current Progress**

The repository documents the selected research question, dataset sources, and current Python-based analysis. The notebook provides a record of the work completed to date, including data processing and any generated tables, figures, or quality checks.

