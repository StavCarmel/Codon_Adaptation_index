# Codon_Adaptation_index
Here is one of the functions I built for Bioinformatics and computational biology analysis - CAI

Functions:

calc_CAI_stav - This function returns the CAI (codon adaptation index) of the genome genes. (a CAI for every gene).

codon_bias_stav - this is the Matlab's function 'codon_bias' with a slight change, instead of having the value '0' when a certain codon doesn't appear then it will be 0.5 
(to mention that the codon appears less than once). 
This way the CAI value won't be demeged by the 0 that was supposed to be, and the CAI will get very low, but not zero.

