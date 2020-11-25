# One-Class Classification Using Hierarchical Subnetwork-based Structure
## Abstract:
Image-based food pattern classification poses new challenges for mainstream computer vision algorithms. Recent works on feature fusion technique have significantly boosted the generalization performances of food categorization tasks. However, the use of representation learning in the training process of feature fusion has rarely been explored. This study addresses the issue through a new supervised subnetwork-based feature encoding and pattern classification model, termed a wide hierarchical subnetwork-based neural network (Wi-HSNN). In particular, Wi-HSNN is a subnet-based iterative training process in which one pair of subnets is added to the framework in each iteration. Furthermore, instead of stacking two separate blocks to obtain the optimal feature for encoding and classifying the objects, the proposed framework searches the optimal latent space and classifies the input patterns simultaneously. In this way, the global-level representation space is generated. Extensive evaluations on eight benchmark datasets from food classification to scene image recognition demonstrated that the proposed solution i) has better representation learning capacity compared to existing encoding methods, and ii) achieves stronger performance than existing approaches for food image classification tasks.

## Contributions:
* I. Architecture side -  This research introduces a novel framework named wide hierarchical SNN (Wi-HSNN). The proposed structure is built with En-SNN and Ex-SNN models. First, the Wi-HSNN begins its network with one pair of subnetworks. After the initialization stage, the network itself is gradually be expanded with the add of new subnetwork nodes. In particular, the hidden space is gradually be enriched with the newly added subnets. 

* II. Application side - The key contribution of this paper in terms of its application is the usage of Wi-HSNN, which harnesses multiple high-level abstract features to classify food images. Here, the input concatenated feature is projected into the entrance feature space before being encoded completely to the next level of dimension-reduced latent space. Then, the final category and label of each food pattern is generated from the low-dimensional encoding space. The experimental results show that i) the super-state features with Wi-HSNN provide a stronger performance than single-modality features, and ii) the proposed method outperforms existing state-of-the-art algorithms consistently on almost all food image classification datasets. 

## Learning Structure:

<img src="https://github.com/wandongzhang/Wi-HSNN/blob/master/2.jpg" width="550" height="430" />

<img src="https://github.com/wandongzhang/Wi-HSNN/blob/master/1.jpg" width="1200" height="400" />

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
