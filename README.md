# Mohamed Elsaid

Bioinformatics Analyst / Computational Biologist, bringing three plus years of regulated pharma lab experience (Pfizer, Catalent) into computational biology. M.S. Bioinformatics, Johns Hopkins University (completed May 2026). B.S. Biochemistry, Manhattan College.

Portfolio site: [mohamedelsaid-bit.github.io/Portfolio-](https://mohamedelsaid-bit.github.io/Portfolio-/)
Email: [melsaid2017@gmail.com](mailto:melsaid2017@gmail.com)
LinkedIn: [mohamed-elsaid-0a0b56231](https://www.linkedin.com/in/mohamed-elsaid-0a0b56231/)

## The differentiator

GMP and GLP lab discipline (ALCOA+ data integrity, 21 CFR Part 11, validation, SOP rigor) applied to computational biology. Every repo below documents its dataset honestly, reports results that did not go as expected rather than hiding them, and pins its environment so it actually reproduces.

## Projects

| Project | What it does | Result |
|---|---|---|
| [RNA-seq Differential Expression](https://github.com/MohamedElsaid-bit/rna-seq-differential-expression-pipeline) | STAR, DESeq2, and Snakemake, run end to end on real airway dexamethasone data (GEO GSE52778) | 108 differentially expressed genes; known dexamethasone response genes (DUSP1, PER1, FKBP5) correctly induced |
| [Germline Variant Calling](https://github.com/MohamedElsaid-bit/variant-calling-pipeline) | GATK4 best practices (BWA-MEM through HaplotypeCaller and hard filtering), orchestrated with Snakemake | 71 PASS variants from 89 raw candidates; simulated read artifacts (Ti/Tv, dbSNP concordance) reported and explained, not hidden |
| [Biomedical ML Classification](https://github.com/MohamedElsaid-bit/biomedical-ml-classification) | Two part scikit-learn benchmark: a tutorial dataset, then a real TCGA pan-cancer RNA-seq deepening | 98.3% test accuracy (Wisconsin); 99.4% test accuracy classifying 5 real cancer types from 20,531 genes, with an honest explanation of why that accuracy is achievable |
| [Portfolio Analytics (SQL)](https://github.com/MohamedElsaid-bit/bioinformatics-analytics-sql) | A LIMS style SQLite schema loaded from the real, already committed outputs of the two pipelines above | 8 SQL queries (joins, window functions, conditional aggregation) and a reporting layer, zero external dependencies |
| [Gut Microbiome Diversity Analysis](https://github.com/MohamedElsaid-bit/gut-microbiome-diversity-analysis) | DADA2 ASV inference and phyloseq diversity analysis on real mouse fecal 16S data | Significant shift in community composition (PERMANOVA, p = 0.001) despite no significant change in alpha diversity; 9 genera differentially abundant by ANCOM-BC2 |
| [Multi-Omics Integration Capstone](https://github.com/MohamedElsaid-bit/multi-omics-integration-capstone) | DIABLO integration (mixOmics) of matched mRNA, miRNA, and protein data from the same real TCGA patients | Reports honestly that the single best omics layer (mRNA, 98.6%) outperformed the 3 block integrated model (94.3%) on this dataset, rather than reframing a negative result as a win |

## Toolbox

Bioinformatics: GATK4, Snakemake, BWA-MEM, samtools, bcftools, FastQC, Trimmomatic, STAR, DESeq2, DADA2, phyloseq, mixOmics
ML and data: Python, scikit-learn, pandas, R, SQL, SQLite
Infrastructure: Git, GitHub, Conda, Docker, Linux, Bash
