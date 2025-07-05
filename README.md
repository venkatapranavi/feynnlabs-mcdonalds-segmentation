# feynnlabs-mcdonalds-segmentation# McDonald’s Brand Segmentation – Feynn Labs Study Task

###  Repository Name: `feynnlabs-mcdonalds-segmentation`  
###  Submitted by: Venkata Pranavi  
###  Organization: Feynn Labs  
###  Submission Date: 05-07-2025  
###  Task Type: Individual Practice Report (Market Segmentation Study)

---

##  Objective

This repository is part of a study task under Feynn Labs, focused on applying market segmentation techniques using a case study of McDonald’s. The goal is to replicate part of the segmentation process through a simple KMeans clustering model based on consumer brand perceptions.

---

##  Methodology

1. **Dataset Creation**  
   A mock dataset was created using binary responses (YES/NO → 1/0) for the following attributes:  
   - YUMMY  
   - GREASY  
   - CHEAP  
   - HEALTHY  
   - DISGUSTING  

2. **Preprocessing**  
   - Converted YES/NO responses to numerical format  
   - Normalized input data for clustering

3. **Clustering Technique Used**  
   - `KMeans` from `scikit-learn`  
   - Tried different cluster sizes and visualized results using `matplotlib` and `seaborn`

4. **Interpretation**  
   - Identified clusters representing positive and negative perceptions of McDonald’s  
   - Analyzed how brand image varies among customer segments

---

##  Contents

| File Name                  | Description                                |
|---------------------------|--------------------------------------------|
| `segmentation_mcdonalds.ipynb` | Main notebook with clustering code         |
| `mock_data.csv`           | Dummy dataset based on McDonald’s attributes |
| `README.md`               | This file                                   |
| `Team-Pranavi.pdf`        | Optional: PDF report submitted              |

---

##  Tools Used

- Python 3.10+
- pandas
- matplotlib
- seaborn
- scikit-learn

---

##  Notes

This is a practice submission for the first study task. The main objective is to understand how to apply market segmentation to real-world brands using Python and clustering techniques. This knowledge will be extended to real market domains in the next phase of the project.

---

## References

- Dolnicar & Leisch (2012), Dolnicar & Grün (2014)  
- Grün & Dolnicar (2016) – Market Segmentation Analysis  
- Feynn Labs Study Task Guidelines
