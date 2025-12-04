
<p align="center">
  <img width="500" height="250" alt="text49030" src="https://github.com/user-attachments/assets/35bd82ba-1950-4118-8d11-76e56acc288e" />
</p>


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
    /other_data/ Additional datasets required for generating plots and analyses (e.g., clinical, structural and modelling data).
    /jupyter-lab/ Jupyter notebooks used to analyze, process, and visualize ADSL data.
    
**Workflow Overview**
 ....
