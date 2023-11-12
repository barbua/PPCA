# PPCA
Supporting code for our paper:

B. Wang, A. Barbu. Scalable Learning with Incremental Probabilistic PCA. 
IEEE International Conference on Big Data, Special Session on Machine Learning for Big Data, 2022
https://ani.stat.fsu.edu/~abarbu/papers/2022-Wang-Incremental_PPCA-BigData.pdf

- PPCA.ipynb trains and evaluates the PPCA model on the CLIP features. Also generates the CLIP features and the PPCA model data.
- A PPCA model file for ILSVRC2016 can be downloaded from: https://ani.stat.fsu.edu/~abarbu/pca640_288_Imagenet.pth
- FC.ipynb trains and evaluates a fully connected layer (linear projection head) on the CLIP features
