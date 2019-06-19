---
title: "Regularized Cross-validation Method for Text Data Sets (in Chinese)"
collection: publications
permalink: /publication/2019-05-Text-CV-JCIP
excerpt: ''
date: 2019-05-01
venue: 'Journal of Chinese Information Processing'
paperurl: 'http://jcip.cipsc.org.cn/CN/abstract/abstract2765.shtml'
citation: 'Ruibo Wang, Yu Wang, Jihong Li. (2019). &quot; Regularized Cross-validation Method for Text Data Sets.&quot; <i>Journal of Chinese Information Processing</i> , 33(5): 54-65. (in Chinese)'
---
When building models on text data sets, cross-validation is a commonly used method in the tasks of feature selection and model comparison. Many studies have revealed that the estimation of performance of models on text data sets is sensitive to the data partitioning used in a cross-validation method. Unreasonable partitioning would lead to a less reliable estimation of the performance, as well as experimental results not repeatable by other researchers. This paper aims to improve the estimation and comparison of the performances by constructing a regularized m×2 cross-validation method (abbreviated as m×2 BCV). The method performs m times of two-fold cross-validation partitioning, and simultaneously introduces the constraints of divergence of distributions of training set and validation set into the partitioning. Specifically, the chi-square statistic is employed to measure the divergence of difference of distributions of the training set and the validation set. Then, the measurement is used to construct regularization conditions for data partitioning. Furthermore, by aiming to maximize signal-to-noise ratio of the estimation of the performance, the data partitioning of m×2 BCV is constructed through filtering out the partitions that satisfy all the preset regularization conditions. In experiments, models in semantic role labeling tasks of Chinese Framenet are investigated to compare different cross-validation methods. All experimental results validate the effectiveness of the proposed m×2 BCV method.

[Download paper here](http://jcip.cipsc.org.cn/CN/abstract/abstract2765.shtml)

Recommended citation: Ruibo Wang, Yu Wang, Jihong Li. (2019). "Regularized Cross-validation Method for Text Data Sets." <i>Journal of Chinese Information Processing</i> , 33(5): 54-65. (in Chinese)