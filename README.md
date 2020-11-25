# One-Class Classification Using Hierarchical Subnetwork-based Structure
## Abstract:

The Multilayer one-class classification (OCC) algorithms have been widely used for outliers identification. Compared to the traditional models that simply classify the patterns with the input patterns, the multilayer models have advantages of higher robustness and better generalization performance. However, the multilayer OCC models search the latent space features with separate blocks, which result in loosely connected feature encoding. In this paper, two novel one-class classification algorithms, termed as OC-SNN and MCOC-SNN, is proposed to handle the above-mentioned issue. In particular, the robust learning strategy is used for the learning of OC-SNN. Instead of applying two separate learning machanism to search the optimal representations of the input patterns and to do the final stage classifications, a subnetwork-based one-class classification algorithm is proposed to learn the latent space data and the final recognition simoutinously. Then, the maximum correntropy criterion (MCC) is used for robust feature learning perpose.  Experiments on image classification and other real-world application domains with varying number of training samples show that the proposed feature representation network gets stronger testing performance compared with other multilayer one-class classification  frameworks.

## Contributions:
* I. Architecture side -  Two novel OCC algorithms called OC-SNN and MCOC-SNN are proposed. Specifically, i) to enhance the discriminitively of the latent space features, the MCC is used; ii) the subnetwork structure is used to develop the architectures; ii) the global-level representations of input pattern are generated through the proposed one-step learning strategy.

* II. Application side - The key contribution of this paper in terms of its application is the usage of OC-SNN and MCOC-SNN, which harnesses high-level abstract features to handle large-scale datasets with more than 500 K samples. Furthermore, the cross-domain validations verify the effectiveness of the proposed methods. 

## Learning Structure:

<img src="https://github.com/wandongzhang/Wi-HSNN/blob/master/2.jpg" width="550" height="430" />

## Related Work:

[1] Zhang, W. (2020). One-Class Classification Using Hierarchical Subnetwork-based Structure. IEEE Transactions on Systems, Man, and Cybernetics: Systems.

## Downloads:
### MNIST-2 (Visual Image Classification Domain)
* MNIST dataset: [MNIST DATASET](http://yann.lecun.com/exdb/mnist/)
* MNIST-2 features: [Res50_S15](https://drive.google.com/open?id=1Jb_xdmA9StQLUme3LG_e3_EjlNIM3hiH)
* Source code for Scene-15: The file will be made public after acceptance of the manuscript (if decided so).
### NORB-2 (Visual Image Classification Domain)
* NORB dataset: [NORB DATASET](https://cs.nyu.edu/~ylclab/data/norb-v1.0-small/)
* NORB-2 features: [Res50_C101](https://drive.google.com/open?id=1F5BUPCQkzR1OmTlx2aID-E-Is6PrWHRZ)
* Source code for Caltech-101: The file will be made public after acceptance of the manuscript (if decided so).
### Place-D (Visual Image Classification Domain)
* Place-365 dataset: [PLACE DATASET](http://places2.csail.mit.edu/)
* Place-D features: [Res50_C256](https://drive.google.com/open?id=104hhcvC20s4sp0J7TYRRM6VK51a6d83v)
* Source code for Caltech-256: The file will be made public after acceptance of the manuscript (if decided so).
### Food identification (Extended Domain)
* Food-251 dataset: [FOOD DATASET](https://github.com/karansikka1/iFood_2019)
### Rumor detection (Extended Domain)
* Rumor dataset (Data collected from three major news agencies): [RUMOR DATASET](http://yann.lecun.com/exdb/mnist/)
#The rumor dataset is our newly collected dataset, here we only show part of the dataset. After acceptance of the manuscript (if decided so), the whole dataset will be made public.

## Dependancies
* Matlab version 2020a,
* A workstation with a 256GB memory and an E5-2650 processor.

## Reproduce the Experimental Results

In "Demo0.zip", run script "main_ResNet_ori.m" for original SGD optimization, "main_ResNet_ori_RL.m" for SGD plus random convolutional learning, "main_ResNet_FR.m" for Yang's retraining strategy, or "main_ResNet_FR_RL.m" for the proposed fast retraining algorithm (random SGD plus batch-by-batch MP).

#The code is released in content-obscured version (p files). After acceptance of the manuscript (if decided so), the source code will be made public.

