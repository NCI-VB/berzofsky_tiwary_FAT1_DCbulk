### This repo contains the code and processed data to produce Figures 5 and 6 for Tiwary et al. 2024

- raw FASTQ files were processes via the [RENEE pipeline](https://github.com/CCBR/RENEE) from [CCBR](https://github.com/CCBR)

- input_data contains the raw counts matrix ("RSEM.genes.expected_count.all_samples.txt") and tpm normalized counts ("RSEM.genes.TPM.all_samples.txt") that are generated in working_directory/DEG_ALL when the pipeline completes
  
- ccrvb31_FAT1dc_bulkRNAseq_MS_KCG.Rmd contains the pipeline processing parameters, and code chunks to produce each panel in Figures 5 and 6
