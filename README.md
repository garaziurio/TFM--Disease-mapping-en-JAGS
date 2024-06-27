# Trabajo de Fin de Máster: Una formulacíon alternativa para la distribución ICAR

En el siguiente repositorio encontrareis el código y los modelos utilizados en este trabajo. 

## Datos brutos

Los datos y las cartrografias utilizadas para los casos prácticos no están disponibles en este repositorio, debido a que unicamente se ha permitido el uso de estas bases de datos para la ejecución de este trabajo. La única base de datos dispoinible de forma pública es la nombrada como "Escocia". Se pueden abrir de la siguiente forma:

```{r}
library(SpatialEpi)
data(scotland)
```
## Código

El código es el documento `CODIGO TFM.rmd´ y se puede ejecutar en orden. Para ejecutar los modelos del código es necesario tener descargada, además de R, los software JAGS y WinBUGS. Además, se debe tener en cuenta que cada uno de los modelos tarda unos 5-7 minutos en ejecutar.

## Versión de R y paquetes empleados

```{r}
sessionInfo()
```

R version 4.3.0 (2023-04-21 ucrt)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows 10 x64 (build 19045)

Matrix products: default


locale:
[1] LC_COLLATE=Spanish_Spain.utf8 
[2] LC_CTYPE=Spanish_Spain.utf8   
[3] LC_MONETARY=Spanish_Spain.utf8
[4] LC_NUMERIC=C                  
[5] LC_TIME=Spanish_Spain.utf8    

time zone: Europe/Madrid
tzcode source: internal

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods  
[7] base     

other attached packages:
 [1] xtable_1.8-4       RColorBrewer_1.1-3 jagsUI_1.5.2      
 [4] dplyr_1.1.2        R2WinBUGS_2.1-21   boot_1.3-28.1     
 [7] coda_0.19-4        leaflet_2.2.1      spdep_1.2-8       
[10] sf_1.0-14          spData_2.3.0       SpatialEpi_1.2.8  
[13] sp_2.1-1          

loaded via a namespace (and not attached):
 [1] s2_1.1.4                utf8_1.2.3             
 [3] generics_0.1.3          class_7.3-21           
 [5] KernSmooth_2.23-20      lattice_0.21-8         
 [7] digest_0.6.31           magrittr_2.0.3         
 [9] evaluate_0.21           grid_4.3.0             
[11] fastmap_1.1.1           e1071_1.7-13           
[13] DBI_1.1.3               fansi_1.0.4            
[15] crosstalk_1.2.0         cli_3.6.1              
[17] rlang_1.1.1             units_0.8-2            
[19] yaml_2.3.7              tools_4.3.0            
[21] parallel_4.3.0          deldir_1.0-9           
[23] vctrs_0.6.2             R6_2.5.1               
[25] proxy_0.4-27            lifecycle_1.0.3        
[27] classInt_0.4-10         leaflet.providers_2.0.0
[29] htmlwidgets_1.6.2       MASS_7.3-58.4          
[31] pkgconfig_2.0.3         rjags_4-14             
[33] pillar_1.9.0            glue_1.6.2             
[35] Rcpp_1.0.10             xfun_0.39              
[37] tibble_3.2.1            tidyselect_1.2.0       
[39] rstudioapi_0.14         knitr_1.43             
[41] htmltools_0.5.5         rmarkdown_2.22         
[43] wk_0.9.0                compiler_4.3.0
