# Data from heart AngII single-cell RNA-Seq study (McLellan and Skelly et al. 2020 Circulation)

This repo is for data from 
McLellan and Skelly et al. (2020) Circulation [doi: 10.1161/CIRCULATIONAHA.119.045115](https://doi.org/10.1161/CIRCULATIONAHA.119.045115).
Raw data are available at ArrayExpress [E-MTAB-8810](https://www.ebi.ac.uk/arrayexpress/experiments/E-MTAB-8810/).

`full_count_matrix.tsv` is the read count matrix 
with 17,170 rows (genes) and 29,615 columns (cells).

The file `wild_type_cluster_labels.tsv` gives cell cluster labels for the wild type
untreated cells (cluster labels as presented in Fig. 1B).

The file `alldata_subcluster_labels.tsv` gives cell cluster labels for all 
cells (subcluster labels as presented in Fig. 2D).

The file `alldata_batch_info.tsv` gives information on batch/treatment for each
cell.

