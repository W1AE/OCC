# One-Class Classification Using Hierarchical Subnetwork-based Structure
## Abstract:

The Multilayer one-class classification (OCC) algorithms have been widely used for outliers identification. Compared to the traditional models that simply classify the patterns with the input patterns, the multilayer models have advantages of higher robustness and better generalization performance. However, the multilayer OCC models search the latent space features with separate blocks, which result in loosely connected feature encoding. In this paper, two novel one-class classification algorithms, termed as OC-SNN and MCOC-SNN, is proposed to handle the above-mentioned issue. In particular, the robust learning strategy is used for the learning of OC-SNN. Instead of applying two separate learning machanism to search the optimal representations of the input patterns and to do the final stage classifications, a subnetwork-based one-class classification algorithm is proposed to learn the latent space data and the final recognition simoutinously. Then, the maximum correntropy criterion (MCC) is used for robust feature learning perpose.  Experiments on image classification and other real-world application domains with varying number of training samples show that the proposed feature representation network gets stronger testing performance compared with other multilayer one-class classification  frameworks.

## Contributions:
* I. Architecture side -  Two novel OCC algorithms called OC-SNN and MCOC-SNN are proposed. Specifically, i) to enhance the discriminitively of the latent space features, the MCC is used; ii) the subnetwork structure is used to develop the architectures; ii) the global-level representations of input pattern are generated through the proposed one-step learning strategy.

* II. Application side - The key contribution of this paper in terms of its application is the usage of OC-SNN and MCOC-SNN, which harnesses high-level abstract features to handle large-scale datasets with more than 500 K samples. Furthermore, the cross-domain validations verify the effectiveness of the proposed methods. 

## Learning Structure:

<img src="https://github.com/wandongzhang/Wi-HSNN/blob/master/2.jpg" width="550" height="430" />

## Related Work:

[1] Zhang, W., Wu, J., & Yang, Y. (2020). Wi-HSNN: A Subnetwork-based Encoding Structure for Dimension Reduction and Food Classification via Harnessing Multi-CNN Model High-level Features. Neurocomputing.

## Downloads:
### Scene-15
* Fine-tuned ResNet-50 features: [Res50_S15](https://drive.google.com/open?id=1Jb_xdmA9StQLUme3LG_e3_EjlNIM3hiH)
* Fine-tuned InceptionNet-v3 features: [Incv3_S15](https://drive.google.com/open?id=1ku7huEzJ8I99qYKT5gtCG803puMz9kxe)
* Source code for Scene-15: The file will be made public after acceptance of the manuscript (if decided so).
### Caltech-101
* Caltech-101 dataset: [Caltech-101](http://www.vision.caltech.edu/Image_Datasets/Caltech101/#Download)
* Fine-tuned ResNet-50 features: [Res50_C101](https://drive.google.com/open?id=1F5BUPCQkzR1OmTlx2aID-E-Is6PrWHRZ)
* Fine-tuned InceptionNet-v3 features: [Incv3_C101](https://drive.google.com/open?id=1pFeL9kC8vs9ljmB4JYOxTznSj0MxM6DF)
* Source code for Caltech-101: The file will be made public after acceptance of the manuscript (if decided so).
### Caltech-256
* Caltech-256 dataset: [Caltech-256](http://www.vision.caltech.edu/Image_Datasets/Caltech256/)
* Fine-tuned ResNet-50 features: [Res50_C256](https://drive.google.com/open?id=104hhcvC20s4sp0J7TYRRM6VK51a6d83v)
* Fine-tuned InceptionNet-v3 features: [Incv3_C256](https://drive.google.com/open?id=1XIHncWSHRH97TDtxCj2-QvR2KjubMXNh)
* Source code for Caltech-256: The file will be made public after acceptance of the manuscript (if decided so).
