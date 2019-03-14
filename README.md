# truncated Gaussian-Mixutre Variational AutoEncoder
Code in keras

## Toy example on MNIST
	mnist.ipynb: A proof-of-concept example. tGM-VAE was applied to identify 3 clusters of images linked to 3 randomly selected digits. Images of the remaining 7 digits were randomly sampled as noise/minor-clusters.

## Synthetic experiments on rs-fMRI data
	aws_toy_truncated_GM-VAE.ipynb: tGM-VAE was applied to cluster dynamic correlation matrices derived from synthetic rs-fMRI signals using a sliding window approach.
	
## Reference

Q. Zhao, N. Honnorat, E. Adeli, K.M. Pohl, Truncated Gaussian-Mixture Variational AutoEncoder, arXiv:1902.03717

Q. Zhao, N. Honnonrat, E. Adeli, A. Pfefferbaum, E. Sullivan, K.M. Pohl, Variational Autoencoderwith Truncated Mixture of Gaussians for Functional Connectivity Analysis,Information Processingin Medical Imaging (IPMI) 2019

		
