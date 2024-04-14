# Alzheimer’s Disease Study - Midterm Project

## Project Overview
This repository contains the results and documentation for a bioinformatics project focused on the discovery of new molecular biomarkers and potential drug targets for Alzheimer's disease (AD). This work was conducted by interdisciplinary teams as part of HIDS-7003_2023 Midterm Project.

## Introduction
As part of an interdisciplinary team embedded into a neuro-biology lab, this project involves analyzing gene expression data from human brain tissue samples at various stages of Alzheimer's disease, ranging from normal controls to severely affected subjects.

## Teams and Collaboration
- **Team 1**: Joan, Gazie, Aditya, Aizhan
- **Team 2**: Han-shen, Prachi, Shania, Subha
- **Team 3**: Yukhta, Youngmin, Frankie, Sydney

Each team member independently conducted parts of the analysis and then collaborated to verify and validate results.

## Project Steps and Outputs
### Step 1: Differential Gene Expression Analysis
- Each team performed a differential gene expression analysis comparing different stages of AD with normal controls using R.
- Outputs:
  - `Name_ComparisonGroupName_BaselinegroupName_TTest.csv`
  - `Name_ComparisonGroupName_BaselinegroupName_DEGs.csv`

### Step 2: Systems Biology Level Analysis
- Analysis of DEGs using enrichR for pathway and gene ontology enrichment to interpret biological implications.
- Outputs:
  - `Name_ComparisonGroupName_BaselinegroupName_EnrichR.xlsx`
  - `Name_ComparisonGroupName_BaselinegroupName_ShortListedPathways.txt`
  - `Name_ComparisonGroupName_BaselinegroupName_ShortListedGenes.txt`

### Step 3: Meta-analysis
- Comparison across all teams to identify commonalities and differences in DEGs at various stages of AD.
- Utilization of Venn diagrams to find overlaps between DEG lists from different stages.

### Step 4: Team Presentation
- Each team prepared a PowerPoint presentation summarizing the findings.
- Presentation files named `Team#_presentation.pptx`.

### Documentation and Reporting
- Each student submitted a summary Word document detailing the analysis steps, results, and conclusions.
- R Markdown files for detailed reproducibility:
  - `Name_GroupCompAnalysis.Rmd` and `Name_GroupCompAnalysis.PDF/HTML`
  - `Name_EnrichAnalysis.Rmd` and `Name_EnrichAnalysis.PDF/HTML`
- `Name_MidtermSummary.docx`: A concise document summarizing the project.

## Repository Structure
This repository is structured to include all files as described in the outputs section for each step of the project. It serves as a comprehensive archive of all analytical processes and results.

## How to Use This Repository
Review the `Name_MidtermSummary.docx` for an overview of the project and analysis. Detailed analysis procedures and results can be accessed through the R Markdown files and their respective outputs.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Author
- Aizhan Uteubayeva (and team members as per the respective teams listed)

## Additional Notes
This project is an open-ended exploration into genomic data. Members are encouraged to pursue further inquiries beyond the course scope to potentially uncover new biological insights.
