# STA207FinalProject
Repository for the Final Project of STA 207, WQ 2022, UC Davis.

This report tends to analysis the influence of government intervention, measured by SI, and the comprehensive society background, measured by HDI, on the fatality due to COVID-19 in 2021.

The _finalProject.rmd_ is the .rmd file that include all necessary codes and analysis.

In _datasets.zip_, _WHO-COVID-19-global-data.csv_ is the mandatory dataset required by Shizhe Chen. The _owid-covid-data.csv_ is the supplemantary dataset that from _Our World in Data_ including death toll, population, HDI and SI. The _2ndData.csv_ is the dataset with variables needed for analysis from _owid-covid-data.csv_.

The code is based on local dataset which is opt to better performance. However, it is feasible to use the most up-to-date dataset, which is directly fetched through the internet with commented lines.

The code has been performed on Windows 22000.556 and the session info is as follows:

R version 4.1.1 (2021-08-10)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows 10 x64 (build 22000)

Matrix products: default

locale:
[1] LC_COLLATE=English_United States.1252 
[2] LC_CTYPE=English_United States.1252   
[3] LC_MONETARY=English_United States.1252
[4] LC_NUMERIC=C                          
[5] LC_TIME=English_United States.1252    
system code page: 936

attached base packages:
[1] stats     graphics  grDevices utils    
[5] datasets  methods   base     

other attached packages:
 [1] multcomp_1.4-18       
 [2] TH.data_1.1-0         
 [3] MASS_7.3-54           
 [4] survival_3.2-11       
 [5] mvtnorm_1.1-3         
 [6] easyGgplot2_1.0.0.9000
 [7] lme4_1.1-27.1         
 [8] Matrix_1.3-4          
 [9] reshape2_1.4.4        
[10] car_3.0-11            
[11] carData_3.0-4         
[12] factoextra_1.0.7      
[13] cluster_2.1.2         
[14] countrycode_1.3.1     
[15] forcats_0.5.1         
[16] stringr_1.4.0         
[17] dplyr_1.0.7           
[18] purrr_0.3.4           
[19] readr_2.0.2           
[20] tidyr_1.1.4           
[21] tibble_3.1.5          
[22] ggplot2_3.3.5         
[23] tidyverse_1.3.1       

loaded via a namespace (and not attached):
 [1] nlme_3.1-152      fs_1.5.2         
 [3] lubridate_1.8.0   httr_1.4.2       
 [5] tools_4.1.1       backports_1.2.1  
 [7] utf8_1.2.2        R6_2.5.1         
 [9] DBI_1.1.1         colorspace_2.0-2 
[11] withr_2.4.3       tidyselect_1.1.1 
[13] curl_4.3.2        compiler_4.1.1   
[15] cli_3.1.1         rvest_1.0.2      
[17] xml2_1.3.2        sandwich_3.0-1   
[19] labeling_0.4.2    scales_1.1.1     
[21] digest_0.6.28     foreign_0.8-82   
[23] minqa_1.2.4       rmarkdown_2.11   
[25] rio_0.5.27        pkgconfig_2.0.3  
[27] htmltools_0.5.2   dbplyr_2.1.1     
[29] fastmap_1.1.0     rlang_0.4.11     
[31] readxl_1.3.1      rstudioapi_0.13  
[33] farver_2.1.0      generics_0.1.0   
[35] zoo_1.8-9         jsonlite_1.7.2   
[37] zip_2.2.0         magrittr_2.0.1   
[39] Rcpp_1.0.7        munsell_0.5.0    
[41] fansi_0.5.0       abind_1.4-5      
[43] lifecycle_1.0.1   stringi_1.7.5    
[45] yaml_2.2.1        plyr_1.8.6       
[47] grid_4.1.1        ggrepel_0.9.1    
[49] crayon_1.4.1      lattice_0.20-45  
[51] haven_2.4.3       splines_4.1.1    
[53] hms_1.1.1         knitr_1.37       
[55] pillar_1.6.3      ggpubr_0.4.0     
[57] boot_1.3-28       ggsignif_0.6.3   
[59] codetools_0.2-18  reprex_2.0.1     
[61] glue_1.4.2        evaluate_0.14    
[63] data.table_1.14.2 modelr_0.1.8     
[65] vctrs_0.3.8       nloptr_1.2.2.2   
[67] tzdb_0.1.2        cellranger_1.1.0 
[69] gtable_0.3.0      assertthat_0.2.1 
[71] xfun_0.29         openxlsx_4.2.4   
[73] broom_0.7.11      rstatix_0.7.0    
[75] ellipsis_0.3.2   
