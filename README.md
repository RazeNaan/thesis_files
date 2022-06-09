# thesis_files

## Arch
This directory conatins the the following three architectures:
* frac_1 - This archtiecture is provided by the VTR group. The change we provide here is that we remove the high delay between the output of the multiply slice to the output of the multiply block.
* frac_2 - This is a modified architecture to analyse the impact of grouping of H-blocks.
* scattered_clusters - This architecture is the proposed architecture.


## Code
The python workflows built around the VTR flow are contained in this file.
* crit_path_analysis.ipynb - This file analyses the critical path of each benchmark.
* routing_slack.ipynb - This file extracts the routing delay from the critical path delay.
