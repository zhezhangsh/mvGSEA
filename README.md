# mvGSEA
Multiplevariate GSEA using logistic regression models

## TODOs 

### Code core functions

#### functions
- run.one.set(): run test on one gene set
 - input: indepedent variables (specify predictors vs. confounders), one gene list, background genes, ...
 - output: effect size (Odds ratio?), p value, overlapping genes, ...
- run.collection.of.set(): run a collection of gene sets and summarize statistical results
 - input: independent variable, list of gene sets, background genes (could be generated as the union of all gene sets)
 - output: statistical table with N, OR, p, FDR, genes, ...
 - performance: parallele computing, optimize code, ...

#### options
- adjustment statistics by gene set size (probably not in version 1)
- 1 or multiple independent variables (eg. differential gene expression + de novo coding mutation)
- 0 to multiple confounders (eg. baseline gene expression level, gene length, ...)
- min. and max. size of gene sets
- variable types (binomial, ordinal, categoral?, and continuous. 
- interaction of independent variables
- ...

### Develop an Awsomics-based Shiny APP

- Manual/Instruction
- Import/export
- Gene annotation
- Multiple species
- Plotting
- ...

### Collect gene sets

- BioSystems (GO, Reactome, BioCyc, etc.) - Done
- KEGG (pathway, module, reaction, etc.) - Done
- MSigDB (signature, pathway, hallmark, target, etc.) - Done
- OMIM - Done
- PubTator (PubMed) - Done
- Panther
- PFAM
- miRNA target databases
- Tissue specific expression (GTEx, SAGE, etc.)

### Test use cases

- disease vs. control in difference cell types (Jim)
- tumor vs. normal adjusted by normal tissue difference (Pichai)

### Write manuscript

- first draft 
- plotting
- submission, communication, response letter, etc. 
- revision 
