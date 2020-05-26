# snpnet-Cox-paper
This GitHub repository contains the snpnet-Cox results decribed in "Fast Lasso Method for Large-scale and Ultrahigh-dimensional Cox Model withApplications to UK Biobank"

See [results](./results) for the results obtained from snpnet runs on 330 time-to-event phenotypes. 

The file [snpnetCox.map.tsv](./results/snpnetCox.map.tsv) contains the UK Biobank code, the number of cases, the number of controls, a description and the ICD 10 of the phenotypes.

The other files have the name (ukbcode).coefficients.tsv, which contains the variants selected by snpnet-Cox for that phenotype, as well as the corresponding coefficients.

Our web app can be found [here](https://biobankengine.stanford.edu/snpnetcox)
