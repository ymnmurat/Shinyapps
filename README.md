# Shinyapps

Currently updated

Folder1: 'ExpressionData_PhenotypeCorrelations' allows comparing gene count data for the exposures of interest with their phenotypic scores. 
Using the shiny app functionalities, count data and phenotypic scores are interactively graphed from table that contains details (phenotype correlations, 
homologous genes to human) and clickable buttons to access gene specific info from NCBI and Ensembl databases
for the respective genes

Folder2: 'DrugLibraryPhenotypes_DrugSimilarities_PossibleTargets' allows holistic analyses for throughput frug library screening results. 
- Initially, for the whole drugs results are graphed in scatter plots and families of drug families are depicted in barplots. Functionalities: Scrollbar and user defined 
threshold values to explore results for candidate treatments. 
- Second tab utilizes 2D based similarity comparisons for the compounds of interest across the drug library results. Functionalities: tanimoto coefficient based
similarity scores, visulization by ggplot aesthetics, interactive table summaries and ChemmineR/fmcs based compound depictions
- Third and last tab is conditional and allows heatmap based graphs for target predictions. Target assessments are presented in an ordinal scale where the 
approved targets from Chembl Database and The Comparative Toxicogenomics Database (CTD) are presented in the highest scale. It also incorporates 
2D similarity based results from the previous tab and shows additional targets from the compounds that are most similar to the compounds of interest. 
Optional functionalities are also tested by retrieving 3D similarity info from PubChem and incorporating knockdown/overexpression studies from 
Broad Instiute tools (ConnectivityMap and iLINCS platforms)
