
<div style="text-align:center; display:flex; justify-content:center; align-items:flex-start;">
  <img width="700" height="350" src="https://github.com/user-attachments/assets/35bd82ba-1950-4118-8d11-76e56acc288e" alt="text49030" />
</div>

# Deep Mutational Scanning of human ADSL gene
This repository is an archive for datasets, analysis scripts, and Jupyter notebooks used in the deep mutational scanning (DMS) of human ADSL (adenylosuccinate lyase) project. We provided to support transparency, reproducibility, and reuse of all associated data and code.

**Project Overview**
This project investigates the functional impact of coding variants including missense, stop-gain, and synonymous in the human ADSL gene, which is linked to the autosomal recessive metabolic disorder ADSL deficiency. Using a deep mutational scanning (DMS) approach, thousands of ADSL variants were quantitatively evaluated for functional activity. Variant effects were measured using a yeast complementation assay in Saccharomyces cerevisiae, where human ADSL replaces the yeast homolog ADE13. Functional activity was inferred from growth fitness.

**Expression Conditions**
Variants were assayed under two conditions to capture a broad range of functional behavior:

- ADSL Low Expression (Dox+) – Low expression of human ADSL (clinically most informative)
- ADSL Low Expression (Dox–) – Low expression with co-expression of yeast ADE13, control experiment.
- ADSL High Expression (Dox+) – High expression of human ADSL.
- ADSL High Expression (Dox–) – High expression with co-expression of yeast ADE13, control experiment.
    
**_Research Paper:_** Çubuk H, Plech M, Aslanzadeh V, Zikanova M, Skopova V, Kmoch S, Shen Y, Marsh JA, Kudla G. Mechanistic Modelling of Recessive Disease through Allelic Integration of Variant Effects. bioRxiv 2025.08.15.670494. doi: https://doi.org/10.1101/2025.08.15.670494
**_MaveDB:_** urn:mavedb:00001257-a 
**_SRA:_** xxx

**Getting Started**
To run the analyses, the recommended workflow is:
1. Install Anaconda to manage Python environments.
2. Create a dedicated conda environment and install the required Python packages (e.g., pandas, numpy, matplotlib, seaborn, scipy, jupyterlab, etc.).
3. Launch either JupyterLab or Jupyter Notebook.
4. Open and run the analysis notebooks located in the /jupyter-lab/ directory, ensuring that the necessary datasets are available in their respective folders.

## Folder Structure
- `data/` - Raw and processed datasets
- `notebooks/` - Jupyter notebooks for analysis and visualization
- `scripts/` - Standalone scripts for data processing
- `results/` - Figures, tables, and intermediate results
- `docs/` - Additional documentation

Please contact:
📧 hasan.cubk@hotmail.com
for any inquiries about the project or data.
