# Calculate regional assessment scores

\*\* **Note: this page is under development**

It is at this point that it is possible to incorporate all of the decisions your team has made into the OHI framework:

* Goals:
    + which goals to include? 
    + how will the goals be weighted?
* Spatial scale:
    + what are the regions within the study area?
* Data:  
    + which data layers can be updated?
    + which data layers must be changed to develop new goal models?
* Goal models:
    + develop any goal models with the best available data
    
Understanding how the Toolbox is structured can help identify what must be modified for a regional assessemt, particularly with data and models.

## Overview

1.  Modifying data layers

2.  Registering the layers

3.  Updating goal models

4.  Register goal inputs 

5.  Check (and update when appropriate) pressures_matrix.csv and resilience_matrix.csv

## Modifying data layers
The default data layers to be modified for the regional assessment are located in the layers folder (as shown for the China assessment below), and each data layer is saved as a separate *.csv* file in the `layers` folder.

![alt text](zfig_layers_location_1.png)

New data layers will be added, and old layers modified directly in this folder. 

Suppose for instance that finer resolution data becomes available for the fisheries sub-goal during a regional evaluation; for example an improved B/Bmsy ratio for the 'Ablennes hians' species that was obtained through formal stock assessments and complex models developed for data-rich fisheries. The old ratios derived from the latest global assessment, say 1.03 in 2008 could then be replaced  with the new ratio, and the new score subsequently calculated.

![alt text](zfig_bmsy_layer_example_3.png)

## Registering data layers

![alt text](zfig_layers_csv.png) 

## Updating goal models

![alt text](zfig_funtions_r.png)

## Register goal inputs

![alt text](zfig_goals_csv.png)

## Check (and update when appropriate) pressures matrix and resilience matrix

![alt text](zfig_pressures_resilience_matrix.png)

- updated data layers
- new data layers

- update layers.csv

- [update goals.csv]()

- update pressures_matrix.csv

- [update resilience_matrix.csv]()
