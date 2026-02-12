# Domain-Specific-pre-trained-ResNet18
This repository publishes a ResNet-18 model pretrained sequentially on ImageNet and then fine-tuned on the Medical Imaging Data Resource Center (MIDRC) dataset[1]. The model was trained on approximately 320 imaging studies (chest CT scans) from MIDRC, selected for its domain-specific relevance to pulmonary conditions. This sequential pretraining strategy yielded superior performance in downstream COVID-19 classification tasks, achieving an AUC-ROC of 0.9130 and accuracy of 85.94% on relevant benchmarks.
The encoder serves as a strong domain-adapted backbone for applications in explainable computer-aided diagnosis (CAD) of lung nodules, semantic deep neural networks, latent space reconstructions via VAEs, disease progression modeling (e.g., spiculation variations), and integration with Siamese networks for visual-semantic learning—aligning with goals to bridge perceptual/cognitive gaps in radiology and enhance trust in AI-assisted interpretation.

## SPIE Conference
SPIE Conference Abstract: https://spie.org/medical-imaging/presentation/Evaluating-ImageNet-and-domainspecific-pretraining-for-variational-autoencoder-reconstruction-of/13926-113

## Author(s):

### Presenter/Author
    
    Charmi Patel
    DePaul Univ. (United States)

### Author(s):
    
    Yiyang Wang
    Milwaukee School of Engineering (United States)

    Rohan Patil
    DePaul Univ. (United States)

    Roselyne Tchoua
    DePaul Univ. (United States)

    Jacob Furst
    DePaul Univ. (United States)

    Daniela Raicu
    DePaul Univ. (United States)

## Acknowledgement:
This work was supported by the National Institutes of Health (NIH) under the VS-EDGE: Visual-Semantic Explanations for Diagnostic Guidance grant, award number 1R15CA297521-01.

Reference:
[1] https://www.midrc.org
