# CNGUYEN_Bhlhe40

**Multi-omic Analysis for the published paper:**  
"Bhlhe40 Promotes CD4+ T Helper 1 Cell and Suppresses T Follicular Helper Cell Differentiation during Viral Infection"  
PMID: [38619295](https://pubmed.ncbi.nlm.nih.gov/38619295) | DOI: [10.4049/jimmunol.2300355](https://doi.org/10.4049/jimmunol.2300355)

---

## Overview
This repository contains a multi-omic analysis pipeline for studying the role of **Bhlhe40** in regulating the differentiation of CD4+ T Helper 1 (Th1) cells versus T Follicular Helper (Tfh) cells during viral infection. The analysis integrates multiple genomic and epigenomic datasets to uncover how Bhlhe40 binds to specific gene loci and influences transcriptional programs.

---

## Data Modalities
The following high-throughput sequencing modalities were used:

1. **Bulk RNA-Seq**
   - Transcriptome profiling of sorted CXCR6+ Th1 and CXCR5+ Tfh CD4 T cells on day 10 post-LCMV infection.

2. **ATAC-Seq**
   - Chromatin accessibility profiling to identify open chromatin regions in the same Th1 and Tfh cell populations.

3. **CUT&Tag-Seq**
   - Epigenomic profiling to map Bhlhe40 binding sites and histone modifications in Th1 and Tfh cells.

---

## Objectives
1. **Transcriptome Analysis:** Identify genes differentially expressed between Th1 and Tfh cells using Bulk RNA-Seq.
2. **Chromatin Accessibility Analysis:** Explore chromatin state differences between Th1 and Tfh cells using ATAC-Seq.
3. **Transcription Factor Binding and Epigenomic Profiling:** Use CUT&Tag to determine how Bhlhe40 regulates specific gene loci.
4. **Data Integration:**
   - Combine Bulk RNA-Seq with ATAC-Seq to correlate chromatin accessibility with gene expression.
   - Integrate ATAC-Seq with CUT&Tag-Seq to link Bhlhe40 binding sites to accessible chromatin regions and active gene transcription.

---

## Repository Structure
- **`scripts/`**: Custom analysis scripts for each data modality.
- **`data/`**: Processed and raw data (note: raw sequencing data are available in public repositories linked in the paper).
- **`results/`**: Final processed datasets, figures, and tables.
- **`docs/`**: Documentation and workflow descriptions.

---
