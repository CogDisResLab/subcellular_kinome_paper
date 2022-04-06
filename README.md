# Subcellular Active Kinome

Data and analytic scripts for the manuscript "Subcellular partitioning of kinase activity revealed by functional kinome profiling"

## Repositroy structure: 

raw_data: contains raw Pamstation12 images, sample annotation, and PamChip layout  

processed_data: contains processed data (global: global phosphorylation data files processed by the KRSA R Package, comparisons: two-group comparison files)  

script: contains Rmardown scripts  



### sessionInfo()
R version 4.0.3 (2020-10-10)
Platform: x86_64-apple-darwin17.0 (64-bit)
Running under: macOS Big Sur 12.0.1

Matrix products: default
LAPACK: /Library/Frameworks/R.framework/Versions/4.0/Resources/lib/libRlapack.dylib

locale:
[1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] furrr_0.2.1           future_1.22.1         knitr_1.30            KRSA_0.9.44          
 [5] forcats_0.5.0         stringr_1.4.0         dplyr_1.0.4           purrr_0.3.4          
 [9] readr_1.4.0           tidyr_1.1.2           tibble_3.1.2          ggplot2_3.3.3        
[13] tidyverse_1.3.0       creedenzymatic_0.1.31

loaded via a namespace (and not attached):
 [1] tidyselect_1.1.0  xfun_0.24         listenv_0.8.0     haven_2.3.1      
 [5] colorspace_2.0-0  vctrs_0.3.8       generics_0.1.0    htmltools_0.5.2  
 [9] yaml_2.2.1        utf8_1.1.4        rlang_0.4.12      pillar_1.6.1     
[13] withr_2.4.2       glue_1.4.2        DBI_1.1.1         dbplyr_2.1.1     
[17] modelr_0.1.8      readxl_1.3.1      lifecycle_1.0.1   munsell_0.5.0    
[21] gtable_0.3.0      cellranger_1.1.0  rvest_0.3.6       codetools_0.2-18 
[25] evaluate_0.14     fastmap_1.1.0     parallel_4.0.3    fansi_0.4.2      
[29] broom_0.7.3       Rcpp_1.0.7        scales_1.1.1      backports_1.2.1  
[33] jsonlite_1.7.2    parallelly_1.28.1 fs_1.5.0          hms_1.0.0        
[37] digest_0.6.28     stringi_1.5.3     grid_4.0.3        cli_3.0.1        
[41] tools_4.0.3       magrittr_2.0.1    crayon_1.4.2      pkgconfig_2.0.3  
[45] ellipsis_0.3.2    xml2_1.3.2        reprex_0.3.0      lubridate_1.7.9.2
[49] assertthat_0.2.1  rmarkdown_2.11    httr_1.4.2        rstudioapi_0.13  
[53] globals_0.14.0    R6_2.5.1          compiler_4.0.3   
