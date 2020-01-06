code_rgam_natcom: .txt file with information information about:
-how to create in silico genomes for mapping Hi-C datasets for mutant clones
-code to obtain the percentage of valid-reads associated with a given viewpoint in wild-type of mutant clones (quantification of virtual-4C files)
-code to quantify number of Hi-C counts from ICE normalized matrices generated from HiC-Pro. 

sequences_used_for_in_silico_genome_generation: .txt file with fasta sequences corresponding to the wild-type 5' intergenic region of Notch or the intronic enhancer as well as the resulting mutant sequences from Sanger Sequencing. This file can be used to generate mutant specific sequences of the X chromosome. See code_rgam2019_natcom.txt for further information.  

virtual4c_input: this folder contains output files from the make_viewpoints.py script in the HiC-Pro suite. Each file corrrespond to an specific genotype and viewpoint. See code_rgam2019_natcom.txt for further information. 

public_software: .txt file with the name, version and link to the public software used to analyze data. See Methods section in the manuscript for further information about usage. 
