---
title: "A novel deep transfer learning method based on explainable feature extraction and domain reconstruction"
collection: publications
permalink: /publication/xdtl-method 
excerpt: 'Although deep transfer learning has made significant progress, its “black-box” nature and unstable feature adaptation remain key obstacles. This study proposes a multi-stage deep transfer learning method, called XDTL, which combines explainable feature extraction and domain reconstruction to enhance the performance of target models. Specifically, the study first divides features into key and regular features through cross-validation and explainability analysis, then reconstructs the target domain using a seed replacement method based on key target samples, ultimately achieving deep transfer. Experimental results show that, compared to other methods, XDTL achieves an average improvement of 27.43 % in effectiveness, demonstrating superior performance and stronger explainability. This method offers new insights into addressing the explainability challenges in transfer learning and highlights its potential for broader applications across various tasks.'
date: 2025-03-15
venue: 'May 15'
paperurl: 'https://doi.org/10.1016/j.neunet.2025.107401'
citation: 'L. Wang, L. Zhang, L. Feng, T. Chen, H. Qin. (2025). A novel deep transfer learning method based on explainable feature extraction and domain reconstruction, <i>Neural Networks</i>. 187, 107401. https://doi.org/10.1016/j.neunet.2025.107401'
---

### Contribution
<div style="text-align: justify;">
This research’s primary contributions are delineated as follows:<br>
  (1)This study proposes XDTL, a multi-stage transfer method that combines explainable feature analysis with deep transfer learning. Unlike existing methods that focus solely on performance, XDTL quantifies feature-level transfer differences through <i>ProLIME</i>, enabling targeted domain adaptation optimization;  <br>
  (2)<i>ProLIME</i> introduces Bayesian priors and kernel width optimization to LIME, resolving its instability in nonlinear scenarios. This method interprets the decision-making process of deep transfer learning models through key feature extraction, thereby partially alleviating the “black-box” issue in deep transfer learning; <br>
  (3)This study reconstructs target domain data using a seed replacement method for key target samples, enabling the transfer task to concentrate on the features most influential to prediction outcomes while reducing data dimensionality;  <br>
  (4)A dynamic adaptive factor is used to quantitatively adjust the alignment between marginal and conditional distributions. By utilizing the Maximum Mean Discrepancy (MMD) to measure the distributional differences, this factor dynamically adjusts the alignment of the two distributions during training, thereby improving the performance and adaptability of transfer learning.  <br>
These contributions indicate that this study aims to advance deep transfer learning and respond to the growing demand for XAI models.  <br>
</div>

### Graphic Abstracts

The graphic abstract is shown below  

![图形摘要1](..\images\Paper1GA.png)
