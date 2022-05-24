# transfer_entropy
Code and data used in a paper, Imaizumi et al., "Assessing transfer entropy from biochemical data", Phys. Rev. E. 105, 034403 (1-13) (2022).

For reproduding Figures 6-9: 

* Open TE_by_Gaussian_Approximation.ipynb by Jupyter Notebook
* Assign 'wild' or 'mutant' to variable DIR in the first cell
* Carry out 'Run All'

Data files:

Time courses for protein translocations in single cells are recorded in csv format. “[wild/sos_wt.csv](https://github.com/kabashiy/transfer_entropy/blob/main/wild/sos_wt.csv)” and “[wild/raf_wt.csv](https://github.com/kabashiy/transfer_entropy/blob/main/wild/raf_wt.csv)” are the data for Figure 6. “[mutant/sos_1131.csv](https://github.com/kabashiy/transfer_entropy/blob/main/mutant/sos_1131.csv)” and “[mutant/raf_1131.csv](https://github.com/kabashiy/transfer_entropy/blob/main/mutant/raf_1131.csv)” are the data for Figure 7. In each file, the first column indicates times (min) of EGF stimulation. The second and after columns indicate signal intensities in single cells at the indicated time points. The first row shows the cell index, and the SOS and RAF responses with the same index were obtained simultaneously in the same cell. These data are licensed under [CC-BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.en).

