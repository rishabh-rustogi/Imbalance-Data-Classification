# Swift Imbalance Data Classification using SMOTE and Extreme Learning Machine
Paper published in IEEE International Conference on Computational Intelligence in Data Science (ICCIDS), 2018. Link can be found [here](https://ieeexplore.ieee.org/abstract/document/8862112/citations?tabFilter=papers "Swift Imbalance Data Classification using SMOTE and Extreme Learning Machine").

## Abstract
Continuous expansion in the fields of science and technology has led to the immense availability and attainability of data in every field. Fundamentally understanding and analyzing this data is a critical job in the decision-making process. Although, great success has been achieved by the prevailing data engineering and mining techniques, the problem of swift classification of the imbalanced data still exists in academia and industry. A potential solution to the problem of skewness in data can be resolved by data upsampling or downsampling. There exists a few techniques that firstly remove skewness and then perform classification, however, these methods suffer from hurdles like abortive precision or slower learning rate. In this paper, a hybrid method to classify binary imbalanced data using Synthetic Minority Over-sampling Technique followed by Extreme Learning Machine is proposed. Our method along with swift learning rate is efficacious to predict the desired class. We verified our model using five standard imbalance dataset and obtained higher F-measure, G-mean and ROC score for all the dataset.

## Result
The proposed hybrid scheme of combining SMOTE for upsampling with Extreme Learning Machine (ELM) are compared against a combination of various other hybrid models. We have used Decision Tree Classifier (DTC), ELM, K-means and W-ELM as the training alogorithms along with the original dataset, upsampled dataset (by using SMOTE) and downsampled dataset (by using CNN+T-Link). For evaluation and validation purposes of our claim, we experimented the proposed scheme on 5 standard datasets (pima, vehicle, ecoli, segment and yeast).
