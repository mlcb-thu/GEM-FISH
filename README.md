GEM-FISH is a program that calculates 3D chromosome models through integrating both Hi-C and FISH data with the prior biophysical knowledge about 3D polymers.

Citation

Ahmed Abbas, Xuan He, Bin Zhou, Guangxiang Zhu, Zishan Ma, Jun-Tao Gao, Michael Q Zhang, and Jianyang Zeng. "Integrating Hi-C and FISH data for modeling 3D organizations of chromosomes". Submitted (April-2018)

Installation

1- Download the program and extract it to the folder "GEM-FISH-master" 

2- Extract the two zip files "GEM-FISH_TAD-conformations.zip" and "GEM-FISH_TAD-level-resolution.zip" in the folder GEM-FISH-master 

3- Add GEM-FISH-master to your Matlab path

Example for usage:

1- Calculate a TAD-level-resolution 3D model for the chromosome as follows:

a- Go into the folder GEM-FISH_TAD-level-resolution
    
b- Run the m-file 'run_chr21_rao.m'. This will calculate the TAD-level-resolution 3D structure for an example chromosome (Chr21).

2- Calculate the intra-TAD conformations of individual TADs as follows:

a- Go into the folder GEM-FISH_TAD-conformations
    
b- Run the m-file 'get_locals_chr21_Rao.m'. This will calculate the intra-TAD conformation of individual TADs of the example chromosome (Chr21).

3- Calculate the final 3D model of the chromosome

a- Go back to the parent folder GEM-FISH-master
    
b- Run the m-file 'final_model_chr21.m'. This will calculate the final 3D model of the chromosome investigated (Chr21 in our case)
    
c- The final 3D structure is written to './Chr21_modeling_results/final_model_chr21.txt'

=================================================================================

For any questions or bug-reporting, please contact: ahmedabbas@mail.tsinghua.edu.cn
