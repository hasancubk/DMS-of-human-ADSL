# DMS-of-human-ADSL
This repository serves as an archive for all datasets, analysis scripts, and Jupyter notebooks used in the deep mutational scanning (DMS) project of human ADSL (adenylosuccinate lyase). The goal is to support transparency, reproducibility, and reuse of all associated data and code.

**Project Overview**
This project characterizes the functional impact of coding variation in the human ADSL gene, which is associated with the autosomal recessive metabolic disorder ADSL deficiency. Using a comprehensive deep mutational scanning approach, thousands of missense, nonsense, and synonymous variants were measured for functional activity.
A yeast complementation assay in Saccharomyces cerevisiae was used to quantify variant effects. Human ADSL replaces the yeast homolog ADE13, and variant function is inferred by measuring growth fitness, which reflects enzymatic activity in vivo.

**Expression Conditions**
Variants were assayed under four conditions to capture a broad range of functional behavior:

    1. ADSL Low Expression (Dox+) – Low expression of human ADSL (clinically most informative)
    
    2. ADSL Low Expression (Dox–) – Low expression with co-expression of yeast ADE13.
    
    3. ADSL High Expression (Dox+) – High expression of human ADSL.
    
    4. ADSL High Expression (Dox–) – High expression with co-expression of yeast ADE13.
    

**Getting Started**
To run the analyses, the recommended workflow is:
1. Install Anaconda to manage Python environments.
2. Create a dedicated conda environment and install the required Python packages (e.g., pandas, numpy, matplotlib, seaborn, scipy, jupyterlab, etc.).
3. Launch either JupyterLab or Jupyter Notebook.
4. Open and run the analysis notebooks located in the /jupyter-lab/ directory, ensuring that the necessary datasets are available in their respective folders.

**Datasets and Folder Descriptions**

/counts/ Raw counts generated during the ADSL project.

/raw_scores/ Enrich2 outputs, including barcode-level scores.

/processed_scores/ Variant-level scores calculated from median-averaged barcode scores.

/other_data/ Additional datasets required for generating plots and analyses (e.g., clinical, structural data).

/jupyter-lab/ Jupyter notebooks used to analyze, process, and visualize ADSL data.


**Workflow Overview**
 ....
