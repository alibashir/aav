# Deep diversification of an AAV capsid protein by machine learning
Drew H. Bryant*, Ali Bashir*, Sam Sinai*, Nina K. Jain, Pierce J. Ogden, Patrick F. Riley, George M. Church^, Lucy J. Colwell^, Eric D. Kelsic^. Nature Biotechnology (2020).

## Model and Dataset Analysis
### Data for reproducing results:
* AAV2 capsid sequences (allseqs_20191230.csv.zip)
  - Capsid packaging assay results for 297k capsid sequences
  - Model training and validation datasets
  - Baseline additive and random datasets
  - Model-designed sequences
  - Model-selected sequences
* Subsampled model-designed sequence partitions (subsampled.tar.gz)
  - Used to normalize sequence subset sizes prior to clustering
* Clustering of all (viable + non-viable) model-designed sequences (clusters.tar.gz)
* Clustering of viable-only model-designed sequences (viable_clusters.tar.gz)

* Data with model scores associated with each sequence in the validation chip (ValidationChipwithModelScores.csv.bz2)

#### Additional information can be found [here](https://github.com/churchlab/Deep_diversification_AAV).
