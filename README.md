# Awesome machine learning/deep learning updates in quantum chemistry, molecular dynamics, and Ab initio MD.


### potentials and reatcion pathways

[Pattanaik, John Ingraham, Colin Grambow, William H. Green, Getting Transition States of Isomerization Reactions with Deep Learning, ChemRxiv, 2020](https://doi.org/10.26434/chemrxiv.12302084.v2)

Graph Neural Network was used to predict the transition states geometries out of the coordinates of reactants and products. 


[Unsleber and Reiher, The Exploration of Chemical Reaction Networks, Annu. Rev. Phys. Chem. 2020. 71:121–42](https://www.annualreviews.org/doi/10.1146/annurev-physchem-071119-040123) 

Review article about modern computational chemistry methods to explore the chemical reactions. It adopts a meta-conceptual perspective aimed at the definition of common general concepts and requirements, such as categorizing mechanistic strategies, and identification of elementary reaction steps and hardly touch upon the natural extension and combination with subsequent kinetic modeling.


 [Smith, Lubbers, et. al, Less is more: Sampling chemical space with active learning,J. Chem. Phys. 148, 241733 (2018)](https://aip.scitation.org/doi/abs/10.1063/1.5023802)
 
 Paper presents an automated approach for the generation of the data set with the target to train a machine learning potentials. The algorithm begins with the reduction of an existing dataset to remove redundant data without loss of accuracy. Then uses the active learning algorithm based on Query by Committee (QBC). 
 
 [Parkhill et at., The many-body expansion combined with neural networks, J. Chem. Phys. 146, 014106 (2017)](https://doi.org/10.1063/1.4973380)
 
The many-body expansion (MBE) is a common formalism to express many-body energy as a sum of E(one-body), E(two-body), and so on up to E(n-body) energy contributions. In this paper, the MBE was used for methanol clusters using DC-GAN. The descriptors that were used are, the Coulomb Matrix and newly discovered depth map (D-map), which is a depth of field image of a ball-and-stick structure. Using DC-GAN they were able to create a neural network and calculate the energies of the clusters. As the results showed, this method is faster than MP2-MBE. The error of NN-MBE is similar to MP2-MBE. 

 [Kammeraad, Goetz, Walker, Tewari, and Zimmerman, What Does the Machine Learn? Knowledge Representations of Chemical Reactivity, J. Chem. Inf. Model. 2020, 60, 3, 1290–1301](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.9b00721)
 
In this paper, the performance of two machine learning models NN and SVM were compared with the non-machine-learning model of the Evans-Polanyi relationship. (EP model observes that the difference in activation energy between two reactions of the same family is proportional to the differences of their enthalpy of reaction.)<bn>
The NN and SVM models show a good correlation between quantum chemical activation energy and machine-learning estimates, Both show similar prediction accuracy. However, ML views reactions categorically rather than by deeper physical relationship. Both are unable to generalize their predictions beyond the specific reaction types that appeared in the input vector. <bn>
The authors show that replacing ML models by the Evans-Polanyi model slightly outperformed the nonlinear machine-learning models (by about 5% RMSE).



### ab initio nanoreactors
[Martínez et al., Discovering chemistry with an ab initio nanoreactor, Nature Chemistry 2014](https://www.nature.com/articles/nchem.2099)

Nanoreactors use ab initio molecular dynamic (AIMD) exploring reaction pathways by taking an intermediate stance between physically realistic simulation and rule-based enumeration approaches. <bn>
The pathways that result from energy refinement are applicable to any thermodynamic setting by providing reaction parameters (for example, concentration, temperature) as input variables to a kinetic model. The article demonstrates two ab initio nanoreactor simulations. The acetylene nanoreactor simulation undergoes the polymerization, while the Urey-Miller simulation generates a complex network of reactions. This presents a nanoreactor as a purely discovery-based method to generate new chemical insight into the reactions

### transition metals

[Kulik et al. Accurate Multiobjective Design in a Space of Millions of Transition Metal Complexes with Neural-Network-Driven Efficient Global Optimization, ACS Cent. Sci. 2020, 6, 513−524](https://pubs.acs.org/action/showCitFormats?doi=10.1021/acscentsci.0c00026&ref=pdf) 

This work present ML- and DFT-driven multiobjective transition metal complex design workflow and apply it to redox flow battery (RFB) redox couple discovery. They constructed a 2.8 M compound space of 700k candidate bulky ligands that are expected to form stable complexes with four open-shell transition metal ions; implemented efficient global optimization (EGO) with a two-dimensional expected improvement (EI) criterion to balance exploration and exploitation at the Pareto front. A multitask ANN with latent-distance-based uncertainty quantification (UQ) metrics generalizes better than a Gaussian process. 

### materials

[Xie and Grosmann, Crystal Graph Convolutional Neural Networks for an Accurate and Interpretable Prediction of Material Properties,PHYSICAL REVIEW LETTERS 120, 145301 (2018) Crystal](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.120.145301)

The article presents a generalized crystal graph convolutional neural networks (CGCNN) framework for representing periodic crystal systems that provide both material property prediction with density functional theory (DFT) accuracy and atomic level chemical insights.



### Protein-ligand interactions and chemical space for drug discovery

[SSnet - Secondary Structure based End-to-End Learning model for Protein-Ligand Interaction Prediction](https://www.biorxiv.org/content/10.1101/2019.12.20.884841v1.abstract)



[Predicting Potential SARS-COV-2 Drugs - In Depth Drug Database Screening Using Deep Neural Network Framework SSnet, Classical
Virtual Screening and Docking](https://www.researchgate.net/profile/Niraj_Verma8/publication/341647942_Predicting_Potential_SARS-COV-2_Drugs_-_In_Depth_Drug_Database_Screening_Using_Deep_Neural_Network_Framework_SSnet_Classical_Virtual_Screening_and_Docking/links/5ecd0aa04585158592bc093a/Predicting-Potential-SARS-COV-2-Drugs-In-Depth-Drug-Database-Screening-Using-Deep-Neural-Network-Framework-SSnet-Classical-Virtual-Screening-and-Docking.pdf)



