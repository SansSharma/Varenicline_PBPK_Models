# PBPK Modeling of Varenicline: Relating Pharmacokinetics to Genomics

This repository contains physiologically based pharmacokinetic (PBPK) models developed to study **varenicline pharmacokinetics** and explore its relationship with **genomic variability**.

## Main PBPK Models

The following models represent the **PBPK models** developed and used for validation in this project:

- **`trying_pKa`** — Mean PBPK model.
- **`Kwak_new`** — Validation model using observed pharmacokinetic data from *Kwak et al.*
- **`Xiao_new`** — Validation model using observed pharmacokinetic data from *Xiao et al.*
- **`Obach_new`** — Validation model using observed pharmacokinetic data from *Obach et al.*

### Subject-Specific Models

All **subject-specific PBPK models** are labeled with the suffix **`new_weight`**, indicating that the simulations incorporate **updated subject body weight parameters**.

Example model names:

- `subject1_new_weight`
- `subject2_new_weight`
- `subject3_new_weight`

## Developmental Models

All other models included in the shared dataset are **developmental models** generated during the model development process. These models were used for parameter exploration, testing modeling assumptions and optimization.   

These intermediate models supported the development and refinement of the final PBPK models listed above.

## Accessing the Models

All models can be accessed by **downloading the ZIP file available in this GitHub repository**.
