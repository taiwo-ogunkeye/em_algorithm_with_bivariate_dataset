# **EM Algorithm for Bivariate Normal Missing Data Imputation**  
**STAT 5310: Design and Inference | Winter 2025**  
**Instructor:** Dr. Jabed Tomal  
**Author:** Taiwo Ogunkeye  
**GitHub Repo:** https://github.com/taiwo-ogunkeye/em_algorithm_with_bivariate_dataset.git

---

## **Project Overview**  
This project implements the **Expectation-Maximization (EM) algorithm** to impute missing values in a bivariate normal dataset (`interexp.dat`), comparing reaction times for stimuli *A* and *B*. Key steps:  
1. Impute missing values using EM under bivariate normality.  
2. Compare pre- and post-imputation distributions.  
3. Conduct a paired *t*-test to assess mean differences.  

---

## **File Structure**  
project-root/
├── imputed_data.csv # Imputed dataset (output)
├── interexp.dat # Original datase
├── knitted_Rcode_taiwo_ogunkeye__design_inference_winter_project.pdf
├── taiwo_ogunkeye_design_inference_R_code_winter_project.pdf
└── README.md # This file


---

## **Dependencies**  
- **R Packages**:  
  - `mvtnorm` (for multivariate normal functions)  
  - `MASS` (for matrix operations)  
  - `ggplot2`, `dplyr` (for visualization and data wrangling)  
- **R Version**: ≥ 4.0.0  

Install packages via:  
```r
install.packages(c("mvtnorm", "MASS", "ggplot2", "dplyr"))
