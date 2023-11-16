# PPCA
Supporting code for our papers:

- B. Wang, A. Barbu. Scalable Learning with Incremental Probabilistic PCA. 
IEEE International Conference on Big Data, Special Session on Machine Learning for Big Data, 2022
https://ani.stat.fsu.edu/~abarbu/papers/2022-Wang-Incremental_PPCA-BigData.pdf
- B. Wang, A. Barbu. Hierarchical Classification for Large-Scale Learning. Electronics 12 No. 22, 4646, 2023
https://www.mdpi.com/2079-9292/12/22/4646

- PPCA.ipynb trains and evaluates the PPCA model on the CLIP features. Also generates the CLIP features and the PPCA model data.
- A PPCA model file for ILSVRC2016 can be downloaded from: https://ani.stat.fsu.edu/~abarbu/pca640_288_Imagenet.pth
- HPPCA.ipynb trains and evaluates the Hierarchical PPCA model on the CLIP features.
- FC.ipynb trains and evaluates a fully connected layer (linear projection head) on the CLIP features
