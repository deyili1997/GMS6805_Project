# GMS6805_Project
The code of this project consists of 3 parts:
1. "Preprocessing_clustering_selecting.ipynb" is the preprocessing notebook, which reads and preprocesses the spatial transcriptomics data, performs Leiden clustering and select spots of interest(such as boundary spots), saves the AnnData File "Patient1_T.h5ad", "Patient1_L.h5ad" for part 2 analysis.
2. "Spatial_DEG_analysis.ipynb" is a DEG analysis notebook, which reads the AnnData from the part 1 and performs DEG analysis between different tumor sub-regions as well as bordering spots.
3. "Cell_Compostion_X.ipynb" deconvoluted the cell composition of each spot with the reference of the scRNA data of the same tissue type.
