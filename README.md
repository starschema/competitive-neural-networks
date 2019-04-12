# Competitive neural networks: a gentle introduction

This set of notebooks is a companion material to my series of articles on the [Starschema blog](https://medium.com/starschema-blog) discussing competitive neural networks. Unlike error-correction neural networks, to which the feedforward backpropagation neural nets you know and love belong, competitive neural networks have an entirely different idea of what neurons do, and indeed model different brain processes (associative or Hebbian learning versus the ventral stream's gradually more complex and semantic process of understanding). While these blog posts are far from giving you the complete lowdown, they're a fun introduction to the subject.

![](https://github.com/chrisvoncsefalvay/competitive-neural-networks/blob/master/assets/vq_principle.png)

## Table of contents

|   | Blog post                                       | Companion notebook  |
|---|-------------------------------------------------|---------------------|
| 1 | [Funderstanding competitive neural networks](https://medium.com/starschema-blog/funderstanding-competitive-neural-networks-f4dae1cb3c1f)      | [notebook](01_Funderstanding_competitive_neural_networks.ipynb) | nbviewer |
| 2 | [Self-Organising Feature Maps for fun and profit](https://medium.com/starschema-blog/self-organising-feature-maps-for-fun-and-profit-d1f62930e3b9) | [notebook](Kohonen_SOFMs.ipynb) | nbviewer |
| 3 | [Growing Neural Gas models: theory and practice](https://medium.com/starschema-blog/growing-neural-gas-models-theory-and-practice-b63e5bbe058d)  | [notebook](03_Detecting_retinopathy_with_GNG.ipynb) | nbviewer |




### References

* Foody, Giles M. "Applications of the self-organising feature map neural network in community data analysis." _Ecological Modelling_ 120.2-3 (1999): 97-107.

* Kohonen, Teuvo. "Exploration of very large databases by self-organizing maps." _Proceedings of International Conference on Neural Networks (ICNN'97)._ Vol. 1. IEEE, 1997.

* Kohonen, Teuvo. "The self-organizing map." _Proceedings of the IEEE_ 78.9 (1990): 1464-1480.

* Nasrabadi, Nasser M., and Yushu Feng. "Vector quantization of images based upon the Kohonen self-organizing feature maps." _Proc. IEEE Int. Conf. Neural Networks._ Vol. 1. 1988.

* AT&T Laboratories Cambridge. _Olivetti Faces Dataset_. Cambridge, MA, 1994.

* Van der Walt, Stefan, et al. "scikit-image: image processing in Python." _PeerJ_ 2 (2014): e453.

* Kälviäinen, R. V. J. P. H., and H. Uusitalo. "DIARETDB1 diabetic retinopathy database and evaluation protocol." _Medical Image Understanding and Analysis._ Vol. 2007. 2007.

* Sinthanayothin, Chanjira, et al. "Automated detection of diabetic retinopathy on digital fundus images." _Diabetic Medicine_ 19.2 (2002): 105-112.

* Buhmann, Joachim, and Hans Kühnel. "Complexity optimized data clustering by competitive neural networks." _Neural Computation_ 5.1 (1993): 75-88.

* Carpenter, Gail A. "Neural network models for pattern recognition and associative memory." _Neural Networks_ 2.4 (1989): 243-257.

* Fritzke, Bernd. "A growing neural gas network learns topologies." _Advances in Neural Information Processing Systems._ 1995.

* Prudent, Yann, and Abdellatif Ennaji. "An incremental growing neural gas learns topologies." _Proceedings of the 2005 IEEE International Joint Conference on Neural Networks_, Vol. 2. IEEE, 2005.

* Daszykowski, Michael, Beata Walczak, and Desire L. Massart. "On the optimal partitioning of data with k-means, growing k-means, neural gas, and growing neural gas." _Journal of Chemical Information and Computer Sciences_ 42.6 (2002): 1378-1389.

* Holdstein, Yaron, and Anath Fischer. "Three-dimensional surface reconstruction using meshing growing neural gas (MGNG)." _The Visual Computer_ 24.4 (2008): 295-302.


### Acknowledgments

The author wishes to thank [Starschema](https://www.starschema.net) for their generous research time allowance that has made the work on these posts and notebooks possible in the first place. I'd also like to thank my wife [Katie]() for putting up with me while I was working on this (it's been a busy few weeks)
