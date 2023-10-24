#MVNN-HNHC

Title:
MVNN-HNHC:A Multi-View Neural Network for Identification of Crotonacylation sites in Human Non-Histone Protein

General content of work:Crotonylation on lysine sites in human non-histone proteins plays a crucial role in biology research. However, traditional experimental methods for crotonylation sites identification are time-consuming and labor-intensive, so the computational prediction methods are more and more popular in recent years. Compared with histone proteins, crotonylation prediction in non-histone proteins has received less attention despite its significance. In this study, we proposed a deep learning framework for identifying of non-histone crotonylation sites, named MVNN-HNHC. MVNN-HNHC integrated manual encoding features and adaptive encoding features through multi-view neural network to deeply learn about attribute differences between crotonylation sites and non-crotonylation sites from various aspects. In MVNN-HNHC, convolutional neural networks can obtain local information from these features,and bidirectional long short term memory networks were utilized to extract sequence information. Then, we employ the attention mechanism to fuse the outputs of various feature extraction modules. Finally, the fully connection network acted as the classifier to predict whether a lysine site was crotonylation site or non-crotonylation.

1. The file "test" trained model was tested on an independent test set

2. The file "train" trains it based on the method proposed in this paper

3. File "Data" and "Data 2" contain the training and testing data used in this study.

4. Version of the related software package. 
python=3.8
numpy                         1.23.1
torch                         1.10.0+cu113
tensorflow-gpu                2.6.0
epoch                         0.1.5



Note: Due to the randomness of the initial parameters of the neural network, the final model results will have small errors
