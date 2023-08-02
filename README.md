# A Bioconductor workflow for processing, evaluating, and interpreting expression proteomics data

This Github repository conatins the text, code and data for the workflow written by Hutchings et al. entitled "A Bioconductor workflow for processing, evaluating, and interpreting expression proteomics data", submitted to F1000Research, 29th June 2023.

Data:
- The raw mass spectrometry data and output data from Proteome Discoverer can be found on the PRIDE database under identifier [PXD041794](https://www.ebi.ac.uk/pride/archive/projects/PXD041794)
- The PSM and peptide level data output from Proteome Discoverer can also be found at (1) Zenodo at https://zenodo.org/record/7837375 and (2) in the top level of this directory
- The PSM-level TMT-labelled data is found in `cell_pellet_tmt_results_psms.txt` and the peptide-level label-free data is found in `supernatant_lfq_results_peptides.txt`. Please see the [workflow](https://github.com/CambridgeCentreForProteomics/f1000_expression_proteomics/blob/main/workflow_expressions.pdf) for details.

Manuscipt:
- The workflow is available in [R Markdown](https://github.com/CambridgeCentreForProteomics/f1000_expression_proteomics/blob/main/workflow_expressions.Rmd) and [PDF](https://github.com/CambridgeCentreForProteomics/f1000_expression_proteomics/blob/main/workflow_expressions.pdf) in the [main repo](https://github.com/CambridgeCentreForProteomics/f1000_expression_proteomics)
- The accomanying [appendix](https://github.com/CambridgeCentreForProteomics/f1000_expression_proteomics/blob/main/appendix.pdf) is also available
