# MORA-data
Appendix Data for Mora Paper

Mora can be found and installed [here](https://github.com/ivlachos/agamemnon/wiki/Use-case) from the Agamemnon Wiki

# Use Case Instructions

Download the data and unzip the ecoli reference file by running 
```
git clone https://github.com/AfZheng126/MORA-data.git
cd MORA-data/ecoli_data
gunzip ecoli.fna.gz
```

Go to the configuration file for Mora make sure the directories are correct. If MORA-data was downloaded in the same directory where MORA was downlaoded, the config file shouldn't need to be changed. Then simply run Mora using the snakemake command. 


# Data from Mora Paper

The Appendix Tables XLSX file contains the tables containing the data of experiments done in the [Mora paper](link). The Ecoli References sheet list the 30 ecoli genome assemblies obtained from NCBI. The three strains used to simulate short reads are listed at the botton with their accession numbers. The Ecoli short reads sheet lists the number of bases assigned to each ecoli strain for Mora, Pathoscope2, and Pufferfish. This sheet contains the data to generate Figure 2a in the paper. The Sevim Real Data sheet contains the data used to generate Figure 2b. The Time and Memory sheet contains the wall clock time and different types of memeory usage by each algorithm. Maximum RAM usage is represetned by MAX_USS and is in units of Mb. Abundance Comparisons lists the RMSE and RMLSE values between real abundances, estimated abundances, and assigned abundancies for Mora and Pathoscope2. The Simulated Data sheet contains the true positives and false positive values. True negatives and false negatives are also shown for species/genus rank due to some of the REF-1 data not being in the NCBI taxonomy database. The F1, sensitivity, and precision scores are also listed here. 
