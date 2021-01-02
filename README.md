# Supplemental_Material
This is the official GitHub Repo for the Supplementary Material of the Masters Thesis. 
Plots and stats of unshown results are documented by the following structure. Mostly the remaining plots of the association testing methods for the unshown outcomes
Campesterol,Sitostabol, Sitosterol and Stigmasterol. Also training stats, the Bayesian Net (plus Bootstrapping net) and decoded features for all virtual patients cohorts. virtual SNP genotypes are shown for two representative subgraphs. Remaining ones can be compiled and uploaded if interested.

* #### GEMMA: 
    Results of standard approach for each outcome shown within a Manhattan plot.
  
* #### Gene-bases_Testing
    Summarized p-values of GenePy, Burden and SKAT-O based testing for all genes shown within a bar plots for each outcome.

* #### Polygenic_Risk_Score_Analysis
  * Genome-wide  
      Polygenic Risk Score stats and plots for all outcomes on genome-wide level including high resolution model fits for all p-values and model fit summary               stats (R-squared, nr. of snps included, empirical p-value etc.)
  * Mechanism-based Model 
       Polygenic Risk Score stats and plots or all outcomes on mechanism-based level. Model fit summary stats equivalent to genome-wide level stats.
* #### Synthetic_Patients
  Results of the synthetic patients generation with VAMBN. 
  * HI-VAE
    Training stats for modules including genotype matrices that were not due to large loss.
    Architectur of the Bayesian Network
  
  * Phenotype Data
   Violin plots of the decoded modules. Features distributions and correlation coefficient distributions for each cohort included.
    * Demographics
    * Phytosterols
    * Polygenic_Risk_Scores: Genome-wide and Mechanism-based
    * GenePy Scores
  
  * Genotype Data
    * Decoded genotype matrices (=SNPs distributions) of two choosen mechanisms and their correlations coefficient distributions: Interleukin signaling- and                Transport related subgraph. Results shown for VAMBN and sim1000G based simulations. Remaining subgraphs can be compiled by request.
    
