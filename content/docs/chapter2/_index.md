---
# Title, summary, and page position.
linktitle: Evaluation and Comparison 
summary: Evaluation and comparison of state-of-the-art tracking methods on UAMT100 benchmark.
weight: 2
icon: book
icon_pack: fas

# Page metadata.
title: Evaluation and Comparison 
date: "2021-09-15T00:00:00Z"
type: book  # Do not modify.
---

## Evaluation metrics
The evaluation complies with the classic standard of one-pass evaluation (OPE) [1], including success rate and precision. Success rate reflects intersection over union (IoU) score, and area under the curve (AUC) of success plot is used to rank the trackers in the experiment. As for precision, it is concerned with the center location error (CLE) between the estimated bounding box and ground truth. Since application of UAM tracking methods confronts severe scale variation, IoU is more important to demonstrate tracking robustness and more accounted in comparison.

<font size=2>[1] Y. Wu, J. Lim, and M.-H. Yang, “Online Object Tracking: A Benchmark,” in Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2013, pp. 2411–2418.</font>

## Results

### 1. Overall performance

![](/images/results.jpg)

Overall performance evaluation on UAMT100 benchmark. 

### 2. Attribute-based performance

| Attribute     | ARC       | BC        | LI        | OB        | OV        | POC       | SV        | SOB       | UAM-A     | VC        | WD        |
| ------------- | --------- | --------- | --------- | --------- | --------- | --------- | --------- | --------- | --------- | --------- | --------- |
| DaSiamRPN [2] | 0.362     | 0.376     | 0.360     | 0.414     | 0.351     | 0.483     | 0.407     | 0.387     | 0.479     | 0.394     | 0.449     |
| SiamFC++ [3]  | 0.470     | 0.451     | 0.444     | 0.518     | 0.447     | **0.629** | 0.501     | 0.484     | 0.627     | 0.502     | 0.445     |
| SiamRPN++ [4] | 0.430     | 0.463     | 0.441     | 0.484     | 0.442     | 0.565     | 0.481     | 0.470     | 0.608     | 0.466     | 0.483     |
| SiamAPN [5]   | 0.454     | 0.421     | 0.397     | 0.506     | 0.414     | 0.597     | 0.476     | 0.467     | 0.663     | 0.455     | 0.417     |
| SiamSA (ours) | **0.527** | **0.508** | **0.486** | **0.550** | **0.472** | 0.615     | **0.533** | **0.524** | **0.709** | **0.519** | **0.500** |

Attributed-based performance on UAMT100. Based on AUC score, the best performance is denoted by **bold** font.

<font size=2>[2] Z. Zhu, Q. Wang, B. Li, W. Wu, J. Yan, and W. Hu, “Distractor-Aware Siamese Networks for Visual Object Tracking,” in Proceedings of the European Conference on Computer Vision (ECCV), 2018, pp. 101–117.</font>

<font size =2>[3] Y. Xu, Z. Wang, Z. Li, Y. Yuan, and G. Yu, “SiamFC++: Towards Robust and Accurate Visual Tracking with Target Estimation Guidelines,” in Proceedings of the AAAI Conference on Artificial Intelligence (AAAI), vol. 34, no. 07, 2020, pp. 12 549–12 556.</font>

<font size =2>[4] B. Li, W. Wu, Q. Wang, F. Zhang, J. Xing, and J. Yan, “SiamRPN++: Evolution of Siamese Visual Tracking with Very Deep Networks,” in Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2019, pp. 4282–4291.</font>

<font size =2>[5] C. Fu, Z. Cao, Y. Li, J. Ye, and C. Feng, “Siamese Anchor Proposal Network for High-Speed Aerial Tracking,” in Proceedings of the IEEE International Conference on Robotics and Automation (ICRA), 2021, pp. 510–516.</font>

