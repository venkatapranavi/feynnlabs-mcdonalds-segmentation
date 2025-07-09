# McDonald’s Brand Segmentation – Feynn Labs Study Task

###  Repository Name: `feynnlabs-mcdonalds-segmentation`  
###  Submitted by: Venkata Pranavi  
###  Organization: Feynn Labs  
###  Submission Date: 05-07-2025  
###  Task Type: Individual Practice Report (Market Segmentation Study)

---

##  Objective

This repository is part of a data science study under **Feynn Labs**, aimed at applying **market segmentation techniques** using real-world brand perception data.  
The project simulates part of a segmentation pipeline using McDonald’s as a case brand and **KMeans clustering** based on consumer perceptions.

---

##  Methodology

1. ** Dataset Creation**
   - A **mock dataset** was created using binary YES/NO responses (converted to 1/0) for brand attributes:
     - `YUMMY`, `GREASY`, `CHEAP`, `HEALTHY`, `DISGUSTING`
   
2. ** Data Preprocessing**
   - Binary conversion of categorical responses
   - Feature scaling for clustering consistency

3. ** Clustering Model**
   - Applied **KMeans clustering** (`scikit-learn`)
   - Visualized clusters using `matplotlib` and `seaborn`
   - Explored different values of `k` to assess segment separation

4. ** Interpretation**
   - Cluster 0: Respondents with **positive brand image**
   - Cluster 1: Respondents with **negative associations** (e.g., greasy, disgusting)
   - Used clustering results to understand potential **targeting opportunities**

---

##  Repository Contents

| File Name                    | Description                                      |
|-----------------------------|--------------------------------------------------|
| `segmentation_mcdonalds.ipynb` | Jupyter notebook implementing the segmentation model |
| `mock_data.csv`             | Simulated brand perception data                  |
| `Team-Pranavi.pdf`          | Market segmentation report (PDF)                 |
| `README.md`                 | Project documentation (this file)                |

---

##  Tools & Libraries

- Python 3.10+
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

---

##  Learning Outcomes

- Practical application of **unsupervised learning** via KMeans
- Use of PCA for dimensionality visualization (optional extension)
- Hands-on experience in consumer segmentation using real marketing logic
- Prepares for applying similar methods to **real-world industry domains** (e.g., tourism, retail, agriculture)

---

##  Next Steps (Optional)

- Add decision tree classification to profile segments by age/gender
- Use actual McDonald’s dataset (if available) to improve realism
- Try hierarchical clustering or DBSCAN for comparison

---

##  Useful References

- Dolnicar, Grün & Leisch (2012–2016) brand perception studies
- Market Segmentation Analysis by Sara Dolnicar (MSA Book)

---

> *This project is part of a personal learning task and not affiliated with McDonald's Corporation.*
