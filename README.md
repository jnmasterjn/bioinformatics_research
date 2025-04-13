# bioinformatics_research

## Analysis of Pathogenic Mutations in the DMD Gene

This repository presents a personal research project that explores the mutation landscape of the *DMD* (Dystrophin) gene, which is associated with Duchenne Muscular Dystrophy (DMD). The study uses bioinformatics tools to analyze the type, frequency, and genomic distribution of mutations, with the goal of identifying patterns that may correlate with gene structure and function.

---

## Research Question

**Using ClinVar and UCSC Genome Browser as tools, how are pathogenic mutations distributed across the DMD gene based on genomic coordinates, and how do their frequencies
relate to their genomic locations (exonic vs. intronic) and mutation types (single nucleotide variants, deletions, duplications, and insertions)?**

---

## Tools & Technologies

- **Python**: For mutation classification, filtering, and basic data processing  
- **R**: For statistical visualization and frequency distribution plotting (`ggplot2`, `dplyr`, `tidyverse`)  
- **ClinVar**: Primary dataset source for clinically annotated DMD mutations  
- **UCSC Genome Browser**: For mapping mutation positions and identifying exon-intron boundaries  
- **Ensembl & NCBI**: For reference gene models and confirmation of functional regions

---

## Methodology

1. **Data Retrieval**
   - Extracted pathogenic and likely pathogenic *DMD* mutations from ClinVar
   - Filtered for relevant clinical significance and formatted genomic coordinates

2. **Annotation & Classification**
   - Separated mutations into exonic vs intronic regions
   - Categorized by mutation type: SNVs, insertions, deletions, and duplications

3. **Visualization**
   - Mapped mutation distributions across the gene using base-pair coordinates
   - Visualized type frequency and density using R-based plots

4. **Interpretation**
   - Investigated clusters of mutations in functional gene regions
   - Compared the mutation patterns in regulatory vs coding areas

## Citation

If you find this project useful, feel free to reference:
> **Janice Shih**  
> Personal Bioinformatics Research Project, 2025

---

## 🔐 License

This research is for exploratory purposes only. Not intended for clinical use.
