# DiPCell: Designing of promiscuous inhibitors against pancreatic cancer cell lines

**DiPCell** is a specialized computational platform designed to accelerate the drug discovery process for pancreatic cancer, one of the most devastating diseases with a very poor prognosis. Unlike tools focused on peptides,
this specific iteration of DiPCell is a web-bench for predicting and screening **promiscuous inhibitors**—small molecules capable of targeting multiple oncogenic pathways—to improve therapeutic outcomes in pancreatic cancer.

**Web Server:** https://webs.iiitd.edu.in/raghava/dipcell/

## Citation

Kumar, R., Chaudhary, K., Singla, D. et al. Designing of promiscuous inhibitors against pancreatic cancer cell lines.
Sci Rep 4, 4668 (2014). https://doi.org/10.1038/srep04668

This dataset can also be found on Zenodo at


## About the Research

The primary goal of this resource is to identify effective drug candidates by leveraging large-scale pharmacological data. The platform uses Quantitative Structure-Activity Relationship (QSAR) models to predict the efficacy of
compounds against various pancreatic cancer cell lines.

* **Model Performance:** The QSAR models achieved a maximum **Pearson correlation coefficient of 0.86** during 10-fold cross-validation, indicating high predictive reliability.


* **Validation:** The models successfully validated known drug-to-oncogene relationships, ensuring the computational predictions align with biological reality.


* **Experimental Testing:** The researchers used these models to screen FDA-approved drugs, which were subsequently tested *in vitro* to confirm their effectiveness.



## Key Features

### 1. Promiscuous Drug Screening

* **Small Molecule Focus:** Specifically designed to predict the inhibition potential of small chemical compounds rather than peptides.


* **FDA-Drug Repurposing:** Includes a module for screening existing FDA-approved drugs to identify new applications in treating pancreatic cancer.



### 2. Cell Line Sensitivity & Resistance

* **Efficacy Profiling:** The tool identifies the most and least effective drugs for specific pancreatic cancer cell lines.


* **Resistance Mapping:** Highlights resistant pancreatic cancer cell lines that require further investigation to uncover the underlying mechanisms of drug resistance.



### 3. Integrated Web-Bench

* **QSAR Prediction:** Allows users to input chemical structures to predict their inhibitory activity against pancreatic cancer models.


* **Design Module:** Facilitates the design of novel promiscuous drug molecules by analyzing how structural changes impact predicted efficacy.



## Applications

* **Accelerated Drug Discovery:** Reducing the time and cost of finding new leads by prioritizing high-potential candidates through virtual screening.


* **Precision Medicine:** Understanding which cell lines respond to specific inhibitors to help tailor potential treatments.


* **Resistance Research:** Providing a starting point for scientists to study why certain pancreatic cancers do not respond to standard therapies.



## Contact & Authors

**Prof. Gajendra P. S. Raghava** (Corresponding Author)

raghava@iiitd.ac.in

Department of Computational Biology, Indraprastha Institute of Information Technology (IIIT Delhi), New Delhi, India.


## Support

This study and the development of DiPCell were supported by the **Council of Scientific and Industrial Research (CSIR)** and the **Department of Biotechnology (DBT)**, Government of India.
