#TranScape VR
in cooperation with Anda Iosip, Center for Computational Biology, Julius-Maximilians University Würzburg)

Nowadays RNA-seq is the norm for investigating transcriptome-wide gene expression. These data cover the expression of thousands of genes over many different tissues and conditions. Finding the biological story hidden in this massive amount of data is challenging and standard data analysis methods using 2D, non-interactive visualization are limiting and daunting. To upgrade to state-of-the-art technology, we developed TranScape VR, a new tool for visualizing transcriptomic landscapes in an immersive, explorative, holistic and entertaining Virtual Reality (VR) space.

Data: We use publicly available data of seven different organs and tissues of the Venus flytrap (Dionaea muscipula), a deadly carnivorous plant (see Iosip AL, Böhm J, Scherzer S, Al-Rasheid KAS, Dreyer I, Schultz J, et al. 2020: PLoS Biol 18(12), doi:10.1371/journal.pbio.3000964)

# Concept
In search for special plant carnivory-related genes, we represent transcriptomic data as an interactive network, mapping genes to each tissue core-node, forming gene clusters. Biological parameters (e.g, gene expression level, tissue specificity) are mapped to visual parameters such as colour, size, distance, and gene position within the 3D space. The visualization offers different modes which depict different properties of the data set. All modes can be interactively explored in order to form and test hypothesis in real-time.

Genes are represented by points in 3D space. Positions are defined by the sum of each tissue vector that hosts the gene, weighted by the inverse of the specificity. The tissue specificity of a gene is determined using the Shannon Entropy method (see Iosip et al 2020 or Schug J. et al. 2005). It is measured by the Q-value. A very small Q-value indicates a very high specificity level and vice versa.

