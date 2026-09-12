# Medulloblastoma Clinical and Molecular Exploratory Data Analysis (EDA) 🧬🧠

This repository contains an Exploratory Data Analysis (EDA) pipeline focused on the clinical and molecular profiling of Medulloblastoma (the most common malignant brain tumor in children) based on the DKFZ (Nature 2017) dataset of 491 patients.

## 🧬 Biological Background & Objectives
Addresses fundamental questions regarding age at diagnosis vs. molecular subgroups (**WNT**, **SHH**, **Group 3**, **Group 4**), tumor mutational burden, sex distribution, and sequencing quality control (WGS vs. WES).

## 📊 Dataset Availability & Download
Available on [cBioPortal (DKFZ, Nature 2017)](https://cbioportal.org). Download the clinical TSV file and name it `mbl_dkfz_2017_clinical_data.tsv`.

## 🛠️ Prerequisites & Installation
Requires Python 3.8+. Clone the repository, install dependencies via `pip install -r requirements.txt`, and run `jupyter notebook medulloblastoma_eda.ipynb`.

## 📉 Key Insights & Results
1. **Age Distribution:** SHH is bimodal (infants and adults); Groups 3 and 4 are strictly pediatric.
   <img width="632" height="435" alt="image" src="https://github.com/user-attachments/assets/3cf3f20d-a10b-4050-8a1b-66f30730643f" />

2. **Mutations & Ploidy:** SHH/WNT have higher baseline mutation counts.
   <img width="631" height="431" alt="image" src="https://github.com/user-attachments/assets/6fa57c0d-3e27-4b82-8fe4-8471bf275429" />

3. **Sex Disparity:** Male predominance in Groups 3 and 4.
   <img width="631" height="426" alt="image" src="https://github.com/user-attachments/assets/3e366b84-f8fc-4684-b6fe-f88936311224" />

4. **Sequencing Benchmarking:** WGS targets ~30x-50x coverage; WES reaches deeper depths (70x-190x).
   <img width="630" height="430" alt="image" src="https://github.com/user-attachments/assets/86e2b2c0-27b4-41f2-8997-28fb138fbf36" />


## 💻 Code & Implementation
Follows Open Science guidelines with robust numeric conversion and explicit biological question/insight comments.

## 📚 References
* Northcott, P.A. et al. *Nature* 547, 311–317 (2017). DOI: [10.1038/nature22973](https://doi.org)
* cBioPortal citations (Cerami et al., 2012; Gao et al., 2013).

## 📄 License
MIT License.
