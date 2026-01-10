---
title: "Calibrating Deep Neural Networks Using Explicit Regularisation and Dynamic Data Pruning"
collection: publications
permalink: /publication/Calibrating_Deep_Neural_Networks_Using_Explicit_Regularisation_and_Dynamic_Data_Pruning
date: 2023-12-15
venue: 'Winter Applications of Computer Vision Conference'
paperurl: 'https://openaccess.thecvf.com/content/WACV2023/html/Patra_Calibrating_Deep_Neural_Networks_Using_Explicit_Regularisation_and_Dynamic_Data_WACV_2023_paper.html'
citation: 'Patra, R., Hebbalaguppe, R., Dash, T., Shroff, G., & Vig, L. (2023). Calibrating deep neural networks using explicit regularisation and dynamic data pruning. In Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (pp. 1541-1549).'
authors: 'Patra, Rishabh, Hebbalaguppe, Ramya, Dash, Tirtharaj, Shroff, Gautam, and Vig, Lovkesh'
---

*Abstract*:  
Deep neural networks are prone to miscalibrated predictions, often exhibiting a mismatch between the target output and the generated sample confidence scores. Contemporary model calibration techniques mitigate the problem of overconfident predictions by pushing down the confidence of the winning class while increasing the confidence of the remaining classes across all test samples. However, from a deployment perspective, an ideal model would (i) generate well-calibrated predictions for high-confidence samples (say, Prob > 0.95) and (ii) generate a higher proportion of legitimate high-confidence samples. To this end, we propose a novel regularization technique that can be used with classification losses, leading to state-of-the-art calibrated predictions at test time; From a deployment standpoint in safety-critical applications, only high-confidence samples from a well-calibrated model are of interest, as the remaining samples have to undergo manual inspection. Predictive confidence reduction of these potentially "high-confidence samples" is a downside of existing calibration approaches. To mitigate this, we propose a dynamic train-time data pruning strategy which prunes low confidence samples every few epochs, providing an increase in confident yet calibrated samples. We demonstrate state-of-the-art calibration performance across image classification benchmarks, reducing training time without much compromise in accuracy. We provide insights into our dynamic pruning strategy showing that pruning low-confidence training samples lead to an increase in high-confidence samples at test time. 

[Download paper here](https://openaccess.thecvf.com/content/WACV2023/html/Patra_Calibrating_Deep_Neural_Networks_Using_Explicit_Regularisation_and_Dynamic_Data_WACV_2023_paper.html)