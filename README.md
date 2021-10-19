# CELLECT-MAGMA-ANALYSIS
Repository for hosting the web application I developed during my Master's thesis at Lundbeck.  

## Explanation of the Application's Purpose
The application has been developed to investigate the output of another computational toolkit named [**CELLECT**](https://github.com/perslab/CELLECT). In short, CELLECT takes as input GWAS data (e.g. for a particular disease of interest) and integrates it with gene expression specificity data (generated by another related toolkit, [**CELLEX**](https://github.com/perslab/CELLEX)) to identify and prioritize likely cell types involved in the etiology of the disease in question. CELLECT can achieve this prioritization of likely disease-related cell types by using one of two genetic prioritization models. One of these models, **MAGMA**, is the basis of the output generated to be used with the web application in this repository.  

The application was developed in R, using the Shiny framework.  

## Running the Application  
_Will be updated asap_

**FYI:** As described above, this application was designed to be run locally, however it is also possible to host the application online. Some of the more direct solutions are the following:
- [Shinyapps.io](https://www.shinyapps.io/) - easy deployment in a few minutes, easily shareable with others, and with free tiers available, however limited in terms of scaling.
- [Shiny Server](https://www.rstudio.com/products/shiny/shiny-server/) - open source, however requires you to use your own server for hosting.
- [RStudio Connect](https://www.rstudio.com/products/connect/) - easy deployment, easily shareable with others, good for collaboration, and supports other programming languages and database systems, however is pricy and mostly intended for organizations.
