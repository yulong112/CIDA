#### HongHuDA | ZiYuan-1 (02D) | HSI dataset
---
## HongHuDA Dataset for hyperspectral image (HSI) domain adaptation
---

#### WenCountyDA | Gaofen-5 | HSI dataset
---
## WenCountyDA Dataset for hyperspectral image (HSI) domain adaptation
---


## Introduction

A novel class-independent domain adaptation algorithm for hyperspectral image (HSI) classification. Our method first creates an independent subspace for each class and then aligns the corresponding single-class samples of the two domains in those subspaces. The posterior probabilities are learned independently through the aligned samples in each subspace. Then, the posterior probabilities obtained from multiple subspaces are fused to produce the final classification labels, aiming at increasing the confidence of results. Additionally, we use smoothed classification labels as pseudo labels for further iteration and incorporate a strategy for selecting representative samples to enhance subspace performance.

## Citation

If you use this dataset in your research, we would appreciate your citation to the following paper:

	@ARTICLE{yu2024dSPG,
	  author={Yu, Long and Li, Jun and He, Lin and Plaza, Antonio and Wang, Lizhe and Tang, Zhonghui and Zhuo, Li and Yuan, Yuchen},
	  journal={IEEE Transactions on Geoscience and Remote Sensing}, 
	  title={dSPG: A New Discriminant Superpixel Graph Regularizer and Convolutional Network for Hyperspectral Image Classification}, 
	  year={2024},
	  volume={62},
	  number={},
	  pages={1-18},
	  doi={10.1109/TGRS.2024.3439434}}

	@article{Yu2024CIDA,
	  title={Class-independent domain adaptation for hyperspectral image classification},
	  author={Yu, Long and Li, Jun and He, Lin and li, Yunfei},
	  journal={National Remote Sensing Bulletin},
	  volume={28},
	  number={3},
	  pages={610-623},
	  year={2024},
	  doi={10.11834/jrs.20232512}
	}

 中文引用：
* Long Yu，Jun Li*，Lin He and Yunfei Li. Class-independent domain adaptation for hyperspectral image classification. ***National Remote Sensing Bulletin***, 2024, 28(3):610-623. doi: 10.11834/jrs.20232512.（余龙，李军，贺霖，李云飞.2024.高光谱图像类别独立的域适应分类.遥感学报，28（3）： 610-623 DOI: 10.11834/jrs.20232512.）
* Long Yu, Jun Li*, Lin He, Antonio Plaza, Lizhe Wang, and Zhonghui Tang. dSPG: A New Discriminant Superpixel Graph Regularizer and Convolutional Network for Hyperspectral Image Classification, ***IEEE Transactions on Geoscience and Remote Sensing***, 2024, 62:1-18, 5526118. doi: 10.1109/TGRS.2024.3439434.
