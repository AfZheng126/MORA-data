# MORA-data
Appendix Data for Mora Paper

Mora can be found and installed [here](https://github.com/AfZheng126/MORA).

# Use Case Instructions

Download the data and unzip the ecoli reference file by running 
```
git clone https://github.com/AfZheng126/MORA-data.git
cd MORA-data/ecoli_data
gunzip ecoli.fna.gz
```

Go to the configuration file for Mora make sure the directories are correct. If MORA-data was downloaded in the same directory where MORA was downlaoded, the config file shouldn't need to be changed. Then simply run Mora using the snakemake command. 


# Data from Mora Paper

The Appendix Tables XLSX file contains the tables containing the data of experiments done in the [Mora paper](link). The information in them are as follows:

| Sheet  | Information |
| ------------- | ------------- |
| A.1 Ecoli Short Reads  | Lists number of reads assigned to each E.coli strain by the different algorithms. |
| A.2 Ecoli References  | Lists the 30 ecoli genome assemblies obtained from NCBI. The three strains used to simulate short reads are listed at the botton with their accession numbers. |
| A.3 Time and Memory | Contains the wall clock time and different types of memeory usage by each algorithm. Maximum RAM usage is represetned by MAX_USS and is in units of Mb. |
| A.4 Simulated Data | Contains the true positives and false positive values. True negatives and false negatives are only shown for species/genus rank due to some of the REF-1 data not being in the NCBI taxonomy database. The F1, sensitivity, and precision scores are also listed here. |
| A.5 Abundance Comparisons | Lists the RMSE and RMLSE values between real abundances, estimated abundances, and assigned abundancies for Mora, Pathoscope2, and Agamemnon. |
| A.6 Real Short E.coli | Contains the number of reads assigned to each E.coli strain by the different algorithms and the resulting scores. |
| A.7 Mock Community Species | Contains the number of reads assigned to each species in the ATCC MSA-1003 mock community experiment. |
| A.8 Mock Community Genus | Contains the number of reads assigned to each species in the ATCC MSA-1003 mock community experiment. |
| A.9 Bracken Abundance | Contains the number of reads assigned to each species and genus in the ATCC MSA-1003 mock community experiment by Bracken.|
| A.10 Mock Community Analysis | Contains the F1 and l1 scores for the ATCC MSA-1003 mock community experiment. |
| A.11 Sevim Real Data | Contains an extra experiment that was not written into the paper. |

# Code for AugPatho2

The AugPatho2 folder has the code that has been augmented from the original Pathoscope2 code. It is the changed files from the pathoscope folder from when you install pathoscope2. 
