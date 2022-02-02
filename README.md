# transfer_entropy
Code and data used in a paper, Imaizumi et al., "Assessing transfer entropy from biochemical data", arXiv:2111.04931.

For reproduding Figures 6-9: 

* Open TE_by_Gaussian_Approximation.ipynb by Jupyter Notebook
* Assign 'wild' or 'mutant' to variable DIR in the first cell
* Carry out 'Run All'

Data files:

Time courses for protein translocations in single cells are recorded in csv format. “wild/sos_wt.csv” and “wild/raf_wt.csv” are the data for Figure 6. “mutant/sos_1131.csv” and “mutant/raf_1131.csv” are the data for Figure 7. In each file, the first column indicates times (min) of EGF stimulation. The second and after columns indicate signal intensities in single cells at the indicated time points. The first row shows the cell index, and the SOS and RAF responses with the same index were obtained simultaneously in the same cell. These data are licensed under [CC-BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.en).

