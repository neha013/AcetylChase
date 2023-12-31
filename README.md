# AcetylChase


**Project Overview:**
Bioinformatics-driven Drug Discovery for Alzheimer's Disease Targeting Acetylcholinesterase. We are predicting standard pIC50 values for the compound. A standard IC50 value represents the concentration of a compound required to inhibit a specific biological activity by 50%. A value of 0 indicates that the compound did not reach the threshold required to achieve a 50% inhibition of the target activity at the tested concentration. This can happen due to various reasons, such as the compound being inactive against the target, the concentration tested being too low, or the target not being sensitive to the compound. To allow IC50 data to be more uniformly distributed, we will convert IC50 to the negative logarithmic scale which is essentially -log10(IC50) i.e. pIC50

**Dataset:**

The [ChEMBL](https://www.ebi.ac.uk/chembl/) Database is a curated database of bioactive molecules with drug-like properties, integrating chemical, bioactivity, and genomic data. With over 2 million compounds, it compiles information from more than 88,000 documents, 1.6 million assays, and encompasses 15,000 targets, 2,000 cells, and 45,000 indications. It serves as a valuable resource for researchers, aiding in the translation of genomic information into effective new drugs by providing comprehensive bioactivity data and facilitating the exploration of chemical structures and their biological activities.

**Results:**

Our project has yielded promising results, as highlighted in the table below. We have evaluated our model based on various metrics to assess its performance and effectiveness.

| Regressor | MSE | R2 Score |
|--------|--------|--------|
| Random Forest Regressor | 1.3779 | 0.5715 |
| Decision Tree Regressor | 1.9579 | 0.3912 |
| KNeighbors Regressor | 1.5433 | 0.5201 |
| Bagging Regressor| 1.5366 | 0.5222 |
| Support Vector Regressor | 1.6548 | 0.4854 |

![download](https://github.com/neha013/AcetylChase/assets/41139808/d16154d4-54f0-471a-b32c-c0a09aae006a)


