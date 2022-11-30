[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=9284979&assignment_repo_type=AssignmentRepo)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/27410-group-assigment-group-13-glucosamine-in-e-coli/main)

# 27410 - Group assignment - Group 13 - Glucosamine in e. coli

## Project summary
In this project, we seek to create an Escherichia coli strain capable of producing high amounts of glucosamine and N-acetyl glucosamine. Using a paper by Deng et. al. (2005) as a reference, we picked out and modified an E. coli model called iML1515, to increase the production of glucosamine. The missing reactions to produce glucosamine were added, after which the same 6 knockouts were conducted as in the Deng et. al. paper.

We picked out another 4 knockouts to optimize N-acetyl glucosamine production. The productivity of the cells were investigated by comparing different media types, where it was found that addition of ribose increased glucosamine production. Phenotypic phase planes were used to compare the production of N-acetyl glucosamine at different levels of biomass and oxygen uptake, and find the optimal levels of each. 

A dynamic flux balance analysis was used to simulate the model in a fed-batch setting, to replicate the experiments made by Deng et. al., in which we managed to replicate the same results as in the paper. 

Using the flux scanning based on enforced objective flux (FSEOF) algorithm, we identified 10 genes of interest for up- or downregulation, which could lead to higher product fluxes.
Finally, optGene was used to identify three genes, which when knocked out will lead to higher glucosamine flux. When the model was tested with these knockouts, an increase in both maximum and minimum glucosamine flux was observed.

We finally conducted a flux variability analysis of glucosamine in our model, to look at how different genes found through the FSEOF would vary in flux depending on glucosamine production.

Through this project we created a model that is theoretically capable of above 510 mmol/l of N-acetyl glucosamine, which is higher than what was reported by Deng et. al. of 498 mmol/l.



## Project overview
* All models used (iML1515, it’s modified version and other E. coli models used for comparison) can be found in the models folder
* The report is located in the Report.ipynb file
* An overview of the designs can be seen in the design_overview.xlsx file


