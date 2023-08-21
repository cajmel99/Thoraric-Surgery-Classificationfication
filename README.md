# Lung Cancer Classification Project

This project focuses on the classification of lung cancer patients based on various attributes collected at the Wroclaw Thoracic Surgery Centre. The dataset was gathered retrospectively from patients who underwent major lung resections for primary lung cancer between 2007 and 2011. The data provides valuable information for predicting the 1-year survival period of patients.

## Dataset Information

The data was collected as part of the National Lung Cancer Registry and is associated with the Department of Thoracic Surgery of the Medical University of Wroclaw and Lower-Silesian Centre for Pulmonary Diseases, Poland.

### Attribute Information

1. **DGN**: Diagnosis - specific combination of ICD-10 codes for primary and secondary tumors (nominal).
2. **PRE4**: Forced vital capacity (FVC) - numeric.
3. **PRE5**: Volume exhaled at the end of the first second of forced expiration (FEV1) - numeric.
4. **PRE6**: Performance status - Zubrod scale (nominal).
5. **PRE7**: Pain before surgery (boolean).
6. **PRE8**: Haemoptysis before surgery (boolean).
7. **PRE9**: Dyspnoea before surgery (boolean).
8. **PRE10**: Cough before surgery (boolean).
9. **PRE11**: Weakness before surgery (boolean).
10. **PRE14**: Size of the original tumor (ordinal).
11. **PRE17**: Type 2 DM - diabetes mellitus (boolean).
12. **PRE19**: MI up to 6 months (boolean).
13. **PRE25**: PAD - peripheral arterial diseases (boolean).
14. **PRE30**: Smoking (boolean).
15. **PRE32**: Asthma (boolean).
16. **AGE**: Age at surgery - numeric.
17. **Risk1Y (CLASS)**: 1-year survival period (boolean).

This repository contains code for preprocessing the dataset, building classification models, and evaluating their performance. The main code files include:

Feel free to contribute, open issues, and submit pull requests if you find any improvements or corrections.

