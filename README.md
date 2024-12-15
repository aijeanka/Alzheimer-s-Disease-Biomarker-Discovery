# **Alzheimer’s Disease Biomarker Discovery**

## **Project Overview**
This repository contains the results and documentation of a bioinformatics project aimed at identifying molecular biomarkers and potential drug targets for Alzheimer’s Disease (AD). The study involved differential gene expression analysis and pathway enrichment to uncover biological insights from human brain tissue data.

## **Project Objectives**
- Discover potential biomarkers associated with different stages of Alzheimer's Disease.
- Identify pathways and gene networks disrupted in AD.
- Conduct a meta-analysis to find common patterns across datasets.

## **Methodology**
### **1. Differential Gene Expression Analysis**
Performed differential gene expression analysis using R to compare various stages of AD against normal controls.

**Key Outputs:**
- Differentially expressed gene (DEG) lists (e.g., `Aizhan_incipient_control_DEGs.csv`).

### **2. Pathway and Gene Ontology Enrichment**
Utilized EnrichR for pathway and gene ontology enrichment to interpret the biological implications of the DEGs.

**Key Outputs:**
- Enrichment results in Excel (`Aizhan_incipient_control_EnrichR.xlsx`).
- Shortlisted pathways and genes (`ShortListedPathways.txt`, `ShortListedGenes.txt`).

### **3. Meta-Analysis Across Teams**
Compared DEGs across multiple analyses to identify common biomarkers and pathways. Visualized overlaps using Venn diagrams.

### **4. Documentation and Reproducibility**
Provided detailed R Markdown files for reproducibility of the analyses.

**Reproducible Analysis Files:**
- `Aizhan_GroupCompAnalysis.Rmd` and corresponding PDF.
- `Aizhan_EnrichAnalysis.Rmd` and corresponding PDF.

### **5. Summary Report**
A comprehensive summary document detailing the analysis, findings, and conclusions (`Alzheimers_biomarker_summary.docx`).

## **Repository Structure**
```
├── Differential_Expression/
│   └── DEG_Results.csv
├── Enrichment_Analysis/
│   └── EnrichR_Results.xlsx
├── Meta_Analysis/
│   └── Venn_Diagrams/
├── Documentation/
│   ├── Summary_Report.docx
│   └── RMarkdown_Files/
└── LICENSE
```

## **Skills Demonstrated**
- **Bioinformatics Analysis**: Differential gene expression, pathway enrichment, and meta-analysis.
- **Data Visualization**: Generation of plots and Venn diagrams for comparative insights.
- **Reproducible Research**: Use of R Markdown for documenting analytical workflows.
- **Collaboration**: Effective teamwork and integration of results.

## **Author**
**Aizhan Uteubayeva**  
*Collaborators: Names of contributors upon request.*

## **License**
This project is licensed under the MIT License.
