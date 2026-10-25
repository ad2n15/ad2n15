### Hi, I'm Ahmed Dawoud 👋

I'm a **Research Fellow in Computational Biology at the University of Southampton**. I trained in genetics
and bioinformatics, and before this role I was a senior bioinformatician at University Hospital
Southampton NHS Trust. I study how blood and immune cells change with age, using population-scale
genetics, single-cell genomics, and AI.

**What I work on**
- **Clonal haematopoiesis and somatic mosaicism:** age-related changes in blood cells, such as
  loss of chromosome Y, and how they link to blood cancers and other diseases.
- **Single-cell genomics:** cell fate, immune trajectories, and methods that make scRNA-seq
  analysis faster and easier to audit.
- **Statistical genetics:** biobank-scale analyses (UK Biobank, TOPMed), GWAS, and cancer
  predisposition.
- **AI for biology:** transformer and foundation models, and LLM agents that help with analysis
  under human oversight.

### 🛡️ Featured project: [CellWarden](https://github.com/cellwarden/cellwarden)

<a href="https://github.com/cellwarden/cellwarden"><img src="https://raw.githubusercontent.com/cellwarden/cellwarden/main/docs/logo/mark-512.png" width="72" align="left" alt="CellWarden logo"></a>

An open-source single-cell RNA-seq pipeline whose decisions are guarded. Rules set a baseline, LLM
agents propose changes, a reviewer agent checks them, and you approve. Every decision is logged.
Built on Seurat, with a fast Rust engine, Docker/Apptainer images, and HPC support. Co-created with
Mukesh Agrawal and David Williams.
[Example report](https://cellwarden.github.io/cellwarden/examples/pbmc3k/report.html) ·
[Get started](https://github.com/cellwarden/cellwarden/blob/main/docs/GETTING_STARTED.md)

<br clear="left">

### 🔬 Research projects

**Loss of chromosome Y across immune cell trajectories (OneK1K)**: [*Aging Cell* 2026](https://doi.org/10.1111/acel.70528) · [code](https://github.com/ad2n15/LOY_Onek1k) · [Shiny app code](https://github.com/ad2n15/LOY_OneK1K_Shiny)
- Called loss of Y at the single-cell level in PBMC scRNA-seq from 416 donors, finding 45,304 LOY cells (8.8%).
- Traced LOY along immune differentiation trajectories, e.g. classical → non-classical monocytes, with cell-type-specific differential expression.
- Found aberrant *XIST* expression and upregulation of genes that escape X-inactivation. Built an interactive Shiny app to explore the results.

**Clonal haematopoiesis in UK Biobank**: [*Leukemia* 2020](https://doi.org/10.1038/s41375-020-0896-8)
- Detected myeloid clonal haematopoiesis in 502,524 participants, combining mosaic chromosomal alterations from SNP arrays (n = 486,941) with somatic driver mutations from whole-exome sequencing (n = 49,956).
- Ran a GWAS that found two independent *TERT* signals and the *JAK2* 46/1 haplotype, plus association analyses with blood traits, clinical phenotypes and smoking (*ASXL1* mutations and current smoking).

**Loss of Y, sex hormones and clonal haematopoiesis**: [*Science Advances* 2023](https://doi.org/10.1126/sciadv.ade9746)
- Linked LOY in UK Biobank with serum biomarkers and found a strong association with sex hormone binding globulin (SHBG).
- Used bidirectional Mendelian randomisation to test causality: the evidence supports SHBG → LOY, not the reverse.
- Showed that *TET2*, *TP53* and *CBL* driver mutations are enriched in LOY cases, while *JAK2* V617F is depleted.

### 📄 More publications

- **Genome-wide analysis defines genetic determinants of MPN subtypes and identifies a sex-specific association at CDH22/CD40.**
  Tapper, Dawoud, Score, Cross. *Blood* (2025). [doi:10.1182/blood.2025028489](https://doi.org/10.1182/blood.2025028489)
- **Clonal myelopoiesis promotes adverse outcomes in chronic kidney disease.**
  Dawoud, Gilbert, Tapper, Cross. *Leukemia* (2022). [doi:10.1038/s41375-021-01382-3](https://doi.org/10.1038/s41375-021-01382-3)
- **PathPinpointR: predicting the progression of scRNA-seq samples through reference trajectories.**
  Nicholas et al. (2026, preprint). [doi:10.64898/2026.04.21.715327](https://doi.org/10.64898/2026.04.21.715327)

Full list: [ORCID 0000-0003-0164-7773](https://orcid.org/0000-0003-0164-7773)

### 🧰 Tools I use
R (Seurat, Bioconductor) · Python (scanpy, PyTorch) · Rust · Nextflow/Snakemake · Docker & Apptainer · Slurm/HPC · Git & GitHub Actions

### 🔗 Find me
[University of Southampton profile](https://www.southampton.ac.uk/people/5xjlmk/doctor-ahmed-dawoud) ·
[ORCID](https://orcid.org/0000-0003-0164-7773) ·
📫 A.Dawoud@soton.ac.uk

