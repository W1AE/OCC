# One-Class Classification Using Hierarchical Subnetwork-based Structure
## Abstract:

The Multilayer one-class classification (OCC) algorithms have been widely used for outliers identification. Compared to the traditional models that simply classify the patterns with the input patterns, the multilayer models have advantages of higher robustness and better generalization performance. However, the multilayer OCC models search the latent space features with separate blocks, which result in loosely connected feature encoding. In this paper, two novel one-class classification algorithms, termed as OC-SNN and MCOC-SNN, is proposed to handle the above-mentioned issue. In particular, the robust learning strategy is used for the learning of OC-SNN. Instead of applying two separate learning machanism to search the optimal representations of the input patterns and to do the final stage classifications, a subnetwork-based one-class classification algorithm is proposed to learn the latent space data and the final recognition simoutinously. Then, the maximum correntropy criterion (MCC) is used for robust feature learning perpose.  Experiments on image classification and other real-world application domains with varying number of training samples show that the proposed feature representation network gets stronger testing performance compared with other multilayer one-class classification  frameworks.

## Contributions:
* I. Architecture side -  Two novel OCC algorithms called OC-SNN and MCOC-SNN are proposed. Specifically, i) to enhance the discriminitively of the latent space features, the MCC is used; ii) the subnetwork structure is used to develop the architectures; ii) the global-level representations of input pattern are generated through the proposed one-step learning strategy.

* II. Application side - The key contribution of this paper in terms of its application is the usage of OC-SNN and MCOC-SNN, which harnesses high-level abstract features to handle large-scale datasets with more than 500 K samples. Furthermore, the cross-domain validations verify the effectiveness of the proposed methods. 

## Learning Structure:

<img src="https://github.com/W1AE/OCC/blob/main/F.jpg" width="1050" height="430" />

## Related Work:

[1] Zhang, W. (2022). One-Class Classification Using Hierarchical Subnetwork-based Structure. IEEE Transactions on Cybernetics.

## Downloads:

#The source code will be made public soon.

### Rumor detection (Extended Domain)
* Rumor dataset (Data collected from three major news agencies): [RUMOR DATASET](https://github.com/W1AE/OCC/blob/main/BL.csv)

#The rumor dataset is our newly collected dataset, here we only show part of the dataset. After acceptance of the manuscript (if decided so), the whole dataset will be released.

## Dependancies
* Matlab version 2020a,
* A workstation with a 256GB memory and an E5-2650 processor.

## Reproduce the Experimental Results

Run script "Coding_OCSNN.m" for original OC-SNN algorithm, run script "Coding_MCOCSNN.m" for the improved MCOC-SNN algorithm.

