# my_project

# ABSTRACT
Breast cancer is a major worldwide health issue that requires accurate and timely
detection in order to increase survival rates. In order to distinguish between benign
and malignant breast masses in mammograms, this study makes use of sophisticated
deep learning algorithms. Three publicly accessible datasets—MIAS, INbreast, and
DDSM—were combined to produce a complete dataset that included 13,710 malig-
nant and 10,766 benign samples. To ensure model robustness, extensive prepro-
cessing was used to improve data quality and correct class imbalance, including
normalisation and data augmentation. The main goal was to create a trustworthy
computer-aided diagnostic (CAD) system that could help radiologists identify breast
cancer.
Advanced convolutional neural networks (CNNs), like VGG16, is refined and
used for tasks involving binary classification and feature extraction. Numerous tests
showed that VGG16 performed better than alternative topologies, exhibiting higher
accuracy, precision-recall metrics and area under the curve (AUC). Advanced evalu-
ation techniques, such as ROC and precision-recall curves, confirmed that the model
could successfully distinguish between benign and malignant tumours. Metrics such
as confusion matrices further demonstrated the model’s capacity to manage unequal
data distribution, enhancing its relevance in practical situations.
The incorporation of deep learning models into the clinical workflow for mam-
mography analysis is demonstrated by this experiment. The created approach im-
proves the precision and effectiveness of breast cancer screening programs while
also lessening the diagnostic strain for radiologists. The suggested method provides
a scalable solution that could enhance patient care and results in early breast cancer
identification by bridging the gap between clinical needs and technology improve-
ments.
Keywords:Binary Classification, Breast Cancer Detection, Clinical Workflow
Integration, Computer-Aided Diagnostic (CAD) Systems, Confusion Matrix,
Convolutional Neural Networks (CNNs), Data Augmentation, Diagnostic Ac-
curacy, DDSM Dataset, Deep Learning, Early Detection, Feature Extraction,
INbreast Dataset, MIAS Dataset, Mammography Analysis, Normalization, Pa-
tient Care Improvement, Precision-Recall Metrics.

# Introduction
A considerable percentage of cancer-related deaths among women are caused by
breast cancer, which continues to be one of the most common and deadly illnesses in
the world. Improved survival rates and successful treatment depend on an early and
precise diagnosis. Mammograms are universally acknowledged as the gold standard
for early detection; yet, because of the inherent complexity of breast tissue structures,
the subtlety of some breast cancer indications, and the variation in radiologists’ skill,
reading mammograms can be difficult. These difficulties show how sophisticated
computer-aided diagnostic (CAD) technologies are required to help radiologists pro-
duce more accurate and consistent results.
Convolutional neural networks (CNNs), one type of deep learning approach, have
become a potent tool for medical image processing in recent years. These models
are excellent at automatically identifying pertinent characteristics in photos and have
demonstrated exceptional performance in tasks like classification and object detec-
tion. Enhancing the identification of benign and malignant breast masses through
the integration of these models into mammography analysis can lower diagnostic
mistakes and improve patient outcomes.

# Aim of the project
The main goal of this research is to create a computer-aided diagnostic (CAD)
system that uses deep learning to classify benign and malignant breast masses in
mammograms. The goal of this project is to support radiologists in clinical decision-
making, increase early detection skills, and improve diagnostic accuracy by utilising
cutting-edge CNN architectures including VGG16, . Furthermore, the study intends
to incorporate and make use of an extensive dataset that combines DDSM, INbreast,
and MIAS in order to guarantee model efficiency and generalisability across various
imaging circumstances.

# Research Question
How does the performance of a custom convolutional neural network (CNN) com-
pare to a pre-trained VGG16 model in classifying benign and malignant breast masses
across different datasets (MIAS, INbreast, and combined) in terms of accuracy, AUC,
and precision-recall metrics?”



