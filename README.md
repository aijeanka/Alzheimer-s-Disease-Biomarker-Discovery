# **Alzheimer’s Disease Biomarker Discovery**

## **Project Overview**

This repository contains the data, code, and results for a bioinformatics project focused on identifying molecular biomarkers and potential drug targets for Alzheimer’s Disease (AD). The study involved differential gene expression analysis and pathway enrichment to uncover biological insights from human brain tissue data across different stages of AD.

---

## **Highlights**

- **Packages Used**:  
  - `tidyverse` – Data manipulation and visualization  
  - `limma` – Differential gene expression analysis  
  - `EnrichR` – Pathway and gene ontology enrichment  
  - `ggplot2` – Data visualization  
  - `knitr` – Reproducible report generation  

- **Code**:  
  R Markdown scripts for differential gene expression and enrichment analysis.

- **Reproduced Figures**:  
  - Venn diagrams for meta-analysis results  
  - Pathway enrichment plots  

---

## **Repository Organization**

To ensure reproducibility and clarity, the repository is organized into the following structure:

```
Alzheimers_Biomarker_Analysis/
│
├── data/                          # Raw and processed data files
│   ├── Aizhan_incipient_control_DEGs.csv
│   ├── Aizhan_incipient_control_EnrichR.xlsx
│   ├── ShortListedPathways.txt
│   └── ShortListedGenes.txt
│
├── scripts/                       # R Markdown scripts and PDFs
│   ├── Aizhan_GroupCompAnalysis.Rmd
│   ├── Aizhan_GroupCompAnalysis.pdf
│   ├── Aizhan_EnrichAnalysis.Rmd
│   └── Aizhan_EnrichAnalysis.pdf
│
├── results/                       # Output and visualization files
│   └── venn_diagrams/             # Meta-analysis visualizations
│
├── docs/                          # Documentation and reports
│   └── Alzheimers_biomarker_summary.docx
│
└── LICENSE                        # License information
```

---

## **Methodology**

### **1. Differential Gene Expression Analysis**

Performed differential gene expression analysis using R to compare various stages of AD against normal controls.

**Key Output**:  
- `Aizhan_incipient_control_DEGs.csv`: List of differentially expressed genes (DEGs).

### **2. Pathway and Gene Ontology Enrichment**

Utilized **EnrichR** to perform pathway and gene ontology enrichment to interpret the biological implications of DEGs.

**Key Outputs**:  
- `Aizhan_incipient_control_EnrichR.xlsx`: Enrichment results.  
- `ShortListedPathways.txt` and `ShortListedGenes.txt`: Filtered lists of significant pathways and genes.

### **3. Meta-Analysis Across Teams**

Compared DEGs across multiple analyses to identify common biomarkers and pathways. Visualized overlaps using Venn diagrams.

### **4. Documentation and Reproducibility**

Detailed R Markdown files ensure reproducibility of the analysis workflow.

**Reproducible Analysis Files**:  
- `Aizhan_GroupCompAnalysis.Rmd` and corresponding PDF.  
- `Aizhan_EnrichAnalysis.Rmd` and corresponding PDF.

### **5. Summary Report**

A comprehensive report detailing the analysis, findings, and conclusions.

**Summary Document**:  
- `Alzheimers_biomarker_summary.docx`

---

## **Steps to Reproduce the Analysis**

1. **Set Up Environment**:  
   Install the necessary R packages:  
   ```r
   install.packages(c("tidyverse", "limma", "ggplot2", "knitr"))
   ```

2. **Clone the Repository**:  
   ```bash
   git clone https://github.com/yourusername/Alzheimers_Biomarker_Analysis.git
   cd Alzheimers_Biomarker_Analysis
   ```

3. **Prepare Data**:  
   Ensure all data files are in the `data/` directory.

4. **Run Scripts**:  
   - Execute `Aizhan_GroupCompAnalysis.Rmd` for differential gene expression.  
   - Execute `Aizhan_EnrichAnalysis.Rmd` for pathway enrichment analysis.

5. **View Reports**:  
   Check the compiled PDFs or HTML reports in the `scripts/` directory.

6. **Review Results**:  
   Outputs and visualizations are stored in the `results/` directory.

---

## **Skills Demonstrated**

- **Bioinformatics Analysis**: Differential gene expression, pathway enrichment, and meta-analysis.
- **Data Visualization**: Creating plots and Venn diagrams for comparative insights.
- **Reproducible Research**: Documenting workflows with R Markdown.
- **Collaboration**: Integrating and comparing results across teams.

---

## **Author**

**Aizhan Uteubayeva**  
*Collaborators: Names of contributors upon request.*

---

## **License**

This project is licensed under the **MIT License**. See the `LICENSE` file for details.
