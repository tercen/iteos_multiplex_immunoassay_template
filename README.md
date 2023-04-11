# iTeos multiplex immunoassay template workflow

The template workflow provided contains the following steps:
* A QC step to ensure zero or one data point per well per plate
* Calculation of a ratio between the antibody treated sample and a selected control per well per plate, and
* Calculation of the median concentration across experimental replicates (within) plate, and 
* Min-max scaling of the concentrations across major sample groups, and
* Calculation of the ratio for a donor within a plate, and
* Calculation of the median ratio across donors and plates, and 
* Plotting of a median ratio barplot along with error bars and a median ratio heatmap, and
* Data export at various steps of the workflow:
    - raw data after joining
    - ratios per well per plate
    - ratios per donor within plates
    - median ratios across donors and plates

