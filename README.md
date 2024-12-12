# Exploring the Relation Between Sense of Direction and Spatial Anxiety in Everyday Mobile Map App Use

This repository supports the analysis for the short paper presented at the **16th International Conference on Spatial Information Theory (COSIT 2024)**.

**Publication Details:**
- **Authors**: Donatella Zingaro, Tumasch Reichenbacher, Mona Bartling, and Sara Irina Fabrikant
- **License**: Creative Commons License CC-BY 4.0
- **Conference**: COSIT 2024
  - **Editors**: Benjamin Adams, Amy Griffin, Simon Scheider, and Grant McKenzie
  - **Article No.**: 15
  - **Pages**: 15:1–15:8
  - **Series**: Leibniz International Proceedings in Informatics (LIPIcs)
  - **Publisher**: Schloss Dagstuhl – Leibniz-Zentrum für Informatik, Dagstuhl Publishing, Germany

## Repository Overview

This repository includes the analysis scripts and resources used in the study. The analysis explores the relationship between Sense of Direction (SBSOD scores) and Spatial Anxiety (SA scores) in the context of everyday mobile map app usage. Due to the sensitive nature of the raw data, the datasets are not provided directly. Contact the authors for access to anonymized versions of the data.

### Files Included:

#### Jupyter Notebooks
1. **`COSIT_24_Preprocessing_DZ.ipynb`**
   - Processes the raw data to extract interactions strictly related to navigation using mobile map apps.
   - Focuses on identifying and isolating data points relevant to the study such as app transitioning and duration.

2. **`COSIT_24_Analysis_DZ.ipynb`**
   - Combines spatial behavior data with participant demographics (e.g., scores, gender, age).
   - Performs correlation analyses between SBSOD scores, SA scores, and interaction variables.
   - **Note**: Datasets are not included in this repository due to privacy concerns. Contact the authors for access to anonymized data.

#### Supplementary Materials
Available at: [https://osf.io/kb5m8/](https://osf.io/kb5m8/)

- **Supplementary Tables:**
  1. **Table 1**: Selected Mobile Map Applications
     - Lists the mobile map applications related to navigation and travel planning.
  2. **Table 2**: Overall Correlation Coefficients
     - Shows correlations between SBSOD scores, SA scores, and interaction variables.
     - Significant correlations are highlighted (bold and asterisks for p-value thresholds).
  3. **Table 3**: Male Dataframe Correlations (Age 24-35)
     - Correlations between SBSOD scores, SA scores, and interaction variables for males aged 24-35.
     - Highlights significant correlations.
  4. **Table 4**: Female Dataframe Correlations (Age 24-35)
     - Similar to Table 3, for females aged 24-35.
     - Highlights significant correlations.

## Usage Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repository-link.git
