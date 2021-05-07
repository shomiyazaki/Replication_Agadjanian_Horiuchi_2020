# Title
Replication package of "Gov52 Replication Project: "Has Trump Damaged U.S. Imaged Abroad?(Agadjanian and Horiuchi 2020) with the Extended Analysis Using `polr` Ordered Multinomial Logistic Regression Model.   

# Author  
## Name  
Sho Miyzaki
## Affiliation  
Harvard College  

# Acknowledgement 
I would sincerely thank Professor Yusaku Horiuchi and Alexander Agadjanian for making the data and codes publicly available. I also thank Professor Horiuchi for willingly consent my replication.

I would also sincerely thank Professor Jefferson Gill, Le Bao (Teaching Fellow), Miroslav Bergam (Course Assistant), and Yao Yu (Course Assistant) for superb teaching and supports in this class, Gov52 Models. 

# Description  
This is the replication report of the work by Agadjanian and Horiuchi (2020), which finds that "foreign citizens rely more on policy content in transnational opinion formation --- an aspect that past research in this area has overlooked(p.2)." 

After successfully replicating the models and results, this report extends the analysis to examine the validity of the models used in the original work. The `polr` ordered multinomial logistic regression models are applied, and visualized graphically with the confidence intervals, instead of p-value tests. Ultimately, I reach the same conclusion with @paper, while pointing out the concerns for the modeling. 
  
 This paper serves as one of the validation analyses of Agadjanian and Horiuchi (2020). 

# Files included in this compressed replication package  

## Files by Replicator (Miyazaki)  

### README.md  
This file  

### Replication Code.Rmd  
The all code for replication and extension.
The replication part refers step1 to step3 of the codes by Agadjanian and Horiuchi (2020). 

### Replication Report.Rmd  
The Rmd. for the pdf output report  

### Replicarion Report.pdf  
The replication report  

## Files from Authors (Agadjanian and Horiuchi)
### [folder] data - census   
This folder contains original and modified Japanese Census data, as well as a ReadMe file (in Japanese).

### [folder] data - PEW  
This folder contains screenshots and data download from Pew Global Attitudes Surveys.  

### [folder] data - sample  
This folder contains the survey data downloaded from Qualtrics and the codebook. IP address and its geocoded location are removed.

# Programs used to verify replication  

## Computational Environment  
- R version 4.0.3 (2020-10-10)
- Platform: x86_64-apple-darwin17.0 (64-bit)
- Running under: macOS Big Sur 10.16
- IDE: RStudio 1.4.1103  

## Packages  
- bookdown_0.21  
- knitr_1.31  
- sjPlot_2.8.7  
- MASS_7.3-53.1   
- cowplot_1.1.1   
- broom_0.7.3    
- ebal_0.1-6      
- stargazer_5.2.2  
- readxl_1.3.1    
- ggthemes_4.2.4  
- forcats_0.5.0   
- stringr_1.4.0   
- dplyr_1.0.3     
- purrr_0.3.4    
- readr_1.4.0     
- tidyr_1.1.2     
- tibble_3.1.0    
- ggplot2_3.3.3  
- tidyverse_1.3.0  

# Process of replication  

(1) Download and uncompress ReplicationPackage file  
(2) Install additional packages necessary for this project  
(3) Set the working directory  
(4) Run the Replication Code.Rmd  
(5) Knit Replication Code.Rmd to HTML  

# Notes  

- All data are de-identified. (Agadjanian and Horiuchi)  

# Most recent date of successful replication  
May 7, 2021  