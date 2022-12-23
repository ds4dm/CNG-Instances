# CNG-Instances
This repository contains the synthetic instances and results for the Critical Node Game (Dragotto, Boukhtouta and Lodi, 2022).

## Results
The folder *results* contains the result files:
- *something_full.csv* contains the full results for something = real or syn
- *something_aggregate.csv* contains the aggregate results for something = real or syn


## Instances
The folder *synthetic_instances* contains the instances. Specifically, for each instance:
- The file *instance_n-k.csv* contains the instance parameters given *n* as the number of nodes and *k* as the instance number. Please, be aware you should only consider the _last two rows_
- The files *instance_n-k-nodes_costsA* and *instance_n-k-nodes_costsD.txt* contains the parameters $p^a$ and $p^d$, respectively.
- The files *instance_n-k-nodes_weightsA* and *instance_n-k-nodes_weightsD.txt* contains the parameters $a$ and $d$, respectively.
- The file *instance_n-k-nodes_traffic.txt* contains the traffic vector from which we generate the other parameters (e.g., $a$ and $p^a$). This is not necessarily useful for reproducibility.
