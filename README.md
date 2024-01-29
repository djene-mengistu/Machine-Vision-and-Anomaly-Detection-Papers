# Machine-Vision-and-Anomaly-Detection-Papers

- [Machine-Vision-and-Anomaly-Detection-Papers](#Machine-Vision-and-Anomaly-Detection-Papers)
	- [1. Introduction and background ](#Introduction-and-background)
	- [2. Industrial anomaly detection ](#Industrial-anomaly-detection)
 	- [3. Classification, Detection and Segmentation Models](#Classification-Detection-and-Segmentation-Models)
	- [4. Semi-supervised and weakly-supervised learning](#Semisupervised-and-weakly-supervised-learning)


## Introduction-and-background

This repository consists of recent state-of-the-art deep learning networks for industrial machine vision application. 
The transformation of manufacturing system towards the intelligent manufacturing focuses on automation and the use of advanced technologies such as AI with robots and advanced machines for greater efficiency and precision. 
The AI system will allow for an optimized production process, smart decisions, real-time information, preventive maintenance, and self-prognosis of the production processes. With availability of big data and advanced computing equipment, and technologies, the deep learning application has been one of the highly researched areas in the scientific world in the past few years. 
Promoting this applications, this repositoty presents recent influential works related to deep learning applications on the area of anomaly detection, and other industrial machine vision applications.

## Industrial-anomaly-detection
Industrial anomaly detection is a critical component of modern industrial processes that involve the monitoring and analysis of data to identify abnormal behavior or deviations from expected patterns within industrial systems. Although various anomalies can be investigated, this repository presents deep learning application for surface anomaly detection for industrial products. Most of the methods presented uses image datasets to identify defective or anomolous parts of the product.

|Year|Title/Source|Journal/Conference|Code|
|---|:---|:--|---|
|2023|[FewSOME: One-Class Few Shot Anomaly Detection with Siamese Networks](https://openaccess.thecvf.com/content/CVPR2023W/VAND/papers/Belton_FewSOME_One-Class_Few_Shot_Anomaly_Detection_With_Siamese_Networks_CVPRW_2023_paper.pdf) |CVPR| [Pytorch](https://github.com/niamhbelton/FewSOME)|
|2022|[SimpleNet: A Simple Network for Image Anomaly Detection and Localization](https://openaccess.thecvf.com/content/CVPR2023/papers/Liu_SimpleNet_A_Simple_Network_for_Image_Anomaly_Detection_and_Localization_CVPR_2023_paper.pdf) |CVPR| [Pytorch](https://github.com/DonaldRR/SimpleNet)|
|2021|[Towards Total Recall in Industrial Anomaly Detection](https://openaccess.thecvf.com/content/CVPR2023W/VAND/papers/Belton_FewSOME_One-Class_Few_Shot_Anomaly_Detection_With_Siamese_Networks_CVPRW_2023_paper.pdf) |CVPR| [Pytorch](github.com/amazon-research/patchcore-inspection)|

**[⬆ back to top](#Machine-Vision-and-Anomaly-Detection-Papers)** 

## Classification-Detection-and-Segmentation-Models
Defect classification, detection, and segmentation are important tasks in various industries, particularly in manufacturing and quality control processes. These tasks involve identifying and categorizing defects in products or materials. Deep learning-based defect classification involves identifying types of defects in a product or simply identifying wether a product is defective or not. Detection involves localization and classification of defects, while defect segmetnation involves identification and localization of defects at a pixel-level. Recent state-of-the-art methods involving these taks are presented in this repository.

|Year|Title/Source|Journal/Conference|Code|
|---|:---|:--|---|
|2023|[Deep learning-based automated steel surface defect segmentation: a comparative experimental study](https://link.springer.com/article/10.1007/s11042-023-15307-y) |Multimedia Tools and Applications| <br>[Pytorch](https://github.com/djene-mengistu/dseg_models)|
|2023|[Deep CNN-based visual defect detection: Survey of current literature](https://www.sciencedirect.com/science/article/abs/pii/S0166361523000611) |Computers in Industry| <br>Not available|
|2023|[Process parameter effects estimation and surface quality prediction for selective laser melting empowered by Bayes optimized soft attention mechanism-enhanced transfer learning](https://www.sciencedirect.com/science/article/abs/pii/S0166361523002166) |Computers in Industry| <br>Not available|
|2023|[WaferSegClassNet - A light-weight network for classification and segmentation of semiconductor wafer defects](https://www.sciencedirect.com/science/article/abs/pii/S0166361522001178) |Computers in Industry| <br>Not available|
|2023|[Automatic Defect Classification Using Semi-Supervised Learning With Defect Localization](https://ieeexplore.ieee.org/document/10129970) |IEEE Transactions on Semiconductor Manufacturing| <br>Not available|
|2023|[Spatial Attention Enhanced Wafer Defect Classification Algorithm for Tiny Defects](https://ieeexplore.ieee.org/document/10367417) |IEEE ICAIT| <br>Not available|
|2022|[Deep Adversarial Data Augmentation for Fabric Defect Classification With Scarce Defect Data](https://ieeexplore.ieee.org/document/9805666) |IEEE Transactions on Instrumentation and Measurement| <br>Not available|
|2022|[Fabric defect classification using prototypical network of few-shot learning algorithm](https://www.sciencedirect.com/science/article/abs/pii/S0166361522000239) |Computers in Industry| <br>Not available|
|2022|[A systemic comparison between using augmented data and synthetic data as means of enhancing wafermap defect classification](https://www.sciencedirect.com/science/article/abs/pii/S0166361522002056) |Computers in Industry| <br>Not available|
|2021|[Improvement of Multi-Lines Bridge Defect Classification by Hierarchical Architecture in Artificial Intelligence Automatic Defect Classification]( https://ieeexplore.ieee.org/document/9419865) |IEEE Transactions on Semiconductor Manufacturing | <br>Not available|
|2021|[Improvement of Multi-Lines Bridge Defect Classification by Hierarchical Architecture in Artificial Intelligence Automatic Defect Classification]( https://ieeexplore.ieee.org/document/9419865) |IEEE Transactions on Semiconductor Manufacturing | <br>Not available|

**[⬆ back to top](#Machine-Vision-and-Anomaly-Detection-Papers)**

## Semi-supervised-and-weakly-supervised-learning
Semi-supervised learning and weakly supervised learning are two approaches to machine learning that address scenarios where obtaining fully labeled training data is challenging or expensive. Hence, this repository presents state-of-the-art semi-supervised and weakly-supervised methods proposed for the task of intelligent industrial inspection.

|Year|Title/Source|Journal/Conference|Code|
|---|:---|:--|---|
|2023|[Uncertainty-aware and dynamically-mixed pseudo-labels for semi-supervised defect segmentation](https://www.sciencedirect.com/science/article/abs/pii/S0166361523001458) |Computers in Industry| <br>[Pytorch](https://github.com/djene-mengistu/UAPS)|
|2022|[Semisupervised Defect Segmentation With Pairwise Similarity Map Consistency and Ensemble-Based Cross Pseudolabels](https://ieeexplore.ieee.org/document/9994033) |IEEE TII| <br>[Pytorch](https://github.com/djene-mengistu/simEps)|
|2019|[Unsupervised weld defect classification in radiographic images using multivariate generalized Gaussian mixture model with exact computation of mean and shape parameters](https://www.sciencedirect.com/science/article/abs/pii/S0166361518305967) |Computers in Industry| <br>Not available|

**[⬆ back to top](#Machine-Vision-and-Anomaly-Detection-Papers)**
