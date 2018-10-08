# Awesome Person Re-identification (Person Re-ID) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

---

## Table of Contents

- [0. Statistics](#statistics)
- [1. Survey](#survey)
- [2. Unsupervised Person Re-ID (+ Transfer / Semi-supervised learning)](#unsupervised-person-re-id)
- [3. Supervised Person Re-ID](#supervised-person-re-id)
- [4. Person search](#person-search)
- [5. Others](#others)
- [6. Datasets](#datasets)

---

## Statistics


| Conference  | Link | #Total | Unsupervised reID | Supervised reID | Person search | Others | Datasets |
|---           |---   |---|---|---|---|---|---|
| ECCV2018 | [Click](http://openaccess.thecvf.com/ECCV2018.py)  | 19 | 4 | 8 | 4 | 3 | 0 |
| CVPR2018 | [Click](http://openaccess.thecvf.com/CVPR2018.py)  | 31 | 5 | 23 | 0 | 2 | 1 |
| ICCV2017 | [Click](http://openaccess.thecvf.com/ICCV2017.py)  | 16 | 7 | 6 | 1 | 2 | 0 |
| CVPR2017 | [Click](http://openaccess.thecvf.com/CVPR2017.py)  | 16 | 2 | 9 | 1 | 3 | 1 |

---

## Survey

#### [arXiv2016] *"Person Re-identification: Past, Present and Future"* [[paper](https://arxiv.org/pdf/1610.02984.pdf)]

---


## Unsupervised Person Re-ID 
### (+Transfer learning)
### (+Semi-supervised learning)

### [ECCV2018]

#### *"Domain Adaptation through Synthesis for Unsupervised Person Re-identification"* 
- [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Slawomir_Bak_Domain_Adaptation_through_ECCV_2018_paper.pdf)]
- Rank-1 (Market1501) : 65.7
- Single query

#### *"Unsupervised Person Re-identification by Deep Learning Tracklet Association"* 
- [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Minxian_Li_Unsupervised_Person_Re-identification_ECCV_2018_paper.pdf)]
- Rank-1 (Market1501) : 63.7
- ResNet-50. Images resized to 256x128.

#### *"Generalizing A Person Retrieval Model Hetero- and Homogeneously"* 
- [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Zhun_Zhong_Generalizing_A_Person_ECCV_2018_paper.pdf)] [[Github](https://github.com/zhunzhong07/HHL)]
- Rank-1 (Market1501) : 62.2(source domain : DukeMTMC) / 56.8(source domain : CUHK03)
- Single query

#### *"Robust Anchor Embedding for Unsupervised Video Person Re-Identification in the Wild"* 
- [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Mang_YE_Robust_Anchor_Embedding_ECCV_2018_paper.pdf)]

### [CVPR2018]

#### *"Unsupervised Cross-dataset Person Re-identification by Transfer Learning of Spatial-Temporal Patterns"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Lv_Unsupervised_Cross-Dataset_Person_CVPR_2018_paper.pdf)] [[Github](https://github.com/ahangchen/TFusion)]
- Rank-1 (Market1501) : 60.7(source domain : CUHK01) / 59.2(source domain : VIPeR) / 58.2(source domain : GRID)

#### *"Transferable Joint Attribute-Identity Deep Learning for Unsupervised Person Re-Identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Transferable_Joint_Attribute-Identity_CVPR_2018_paper.pdf)]
- Rank-1 (Market1501) : 58.2(source domain : DukeMTMC)

#### *"Image-Image Domain Adaptation with Preserved Self-Similarity and Domain-Dissimilarity for Person Re-identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Deng_Image-Image_Domain_Adaptation_CVPR_2018_paper.pdf)] [[Github](https://github.com/Simon4Yan/Learning-via-Translation)]
- Rank-1 (Market1501) : 58.1

#### *"Disentangled Person Image Generation"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Ma_Disentangled_Person_Image_CVPR_2018_paper.pdf)]
- Rank-1 (Market1501) : 35.5

#### *"Exploit the Unknown Gradually: One-Shot Video-Based Person Re-Identification by Stepwise Learning"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wu_Exploit_the_Unknown_CVPR_2018_paper.pdf)] [[Github](https://github.com/Yu-Wu/Exploit-Unknown-Gradually)] [[Homepage](https://yu-wu.net/publication/cvpr2018-oneshot-reid/)]


### [ICCV2017]

#### *"Cross-view Asymmetric Metric Learning for Unsupervised Person Re-identification"* 
- [[paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Yu_Cross-View_Asymmetric_Metric_ICCV_2017_paper.pdf)] [[Github](https://github.com/KovenYu/CAMEL)]
- Rank-1 (Market1501) : 54.5
- Multiple query

#### *"Efficient Online Local Metric Adaptation via Negative Samples for Person Re-Identification"* 
- [[paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Zhou_Efficient_Online_Local_ICCV_2017_paper.pdf)]
- Rank-1 (Market1501) : 51.5(Multiple query) / 40.9(Single query)

#### *"SHaPE: A Novel Graph Theoretic Algorithm for Making Consensus-based Decisions in Person Re-identification Systems"* 
- [[paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Barman_SHaPE_A_Novel_ICCV_2017_paper.pdf)]

#### *"Stepwise Metric Promotion for Unsupervised Video Person Re-identification"* 
- [[paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Liu_Stepwise_Metric_Promotion_ICCV_2017_paper.pdf)]

#### *"Group Re-Identification via Unsupervised Transfer of Sparse Features Encoding"* 
- [[paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Lisanti_Group_Re-Identification_via_ICCV_2017_paper.pdf)]

#### *"Unlabeled Samples Generated by GAN Improve the Person Re-identification Baseline in vitro"* 
- [[paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Zheng_Unlabeled_Samples_Generated_ICCV_2017_paper.pdf)] [[Github](https://github.com/layumi/Person-reID_GAN)]

#### *"Dynamic Label Graph Matching for Unsupervised Video Re-Identification"* 
- [[paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Ye_Dynamic_Label_Graph_ICCV_2017_paper.pdf)] [[Github](https://github.com/mangye16/dgm_re-id)]


### [CVPR2017]

#### *"One-Shot Metric Learning for Person Re-Identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Bak_One-Shot_Metric_Learning_CVPR_2017_paper.pdf)]

#### *"Unsupervised Adaptive Re-Identification in Open World Dynamic Camera Networks"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Panda_Unsupervised_Adaptive_Re-Identification_CVPR_2017_paper.pdf)]


### [arXiv]

#### *"Unsupervised Person Re-identification: Clustering and Fine-tuning"* 
- [[paper](https://arxiv.org/pdf/1705.10444.pdf)] [[Github](https://github.com/hehefan/Unsupervised-Person-Re-identification-Clustering-and-Fine-tuning)]
- Rank-1 (Market1501) : 41.9 (source domain : CUHK03)
- Single query



---

## Supervised Person Re-ID

### [ECCV2018] 

#### *"Maximum Margin Metric Learning Over Discriminative Nullspace for Person Re-identification"* 
- [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/T_M_Feroz_Ali_Maximum_Margin_Metric_ECCV_2018_paper.pdf)]

#### *"Person Re-identification with Deep Similarity-Guided Graph Neural Network"* 
- [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yantao_Shen_Person_Re-identification_with_ECCV_2018_paper.pdf)]

#### *"Pose-Normalized Image Generation for Person Re-identification"* 
- [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Xuelin_Qian_Pose-Normalized_Image_Generation_ECCV_2018_paper.pdf)]

#### *"Improving Deep Visual Representation for Person Re-identification by Global and Local Image-language Association"* 
- [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Dapeng_Chen_Improving_Deep_Visual_ECCV_2018_paper.pdf)]

#### *"Hard-Aware Point-to-Set Deep Metric for Person Re-identification"* 
- [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Rui_Yu_Hard-Aware_Point-to-Set_Deep_ECCV_2018_paper.pdf)]

#### *"Part-Aligned Bilinear Representations for Person Re-Identification"* 
- [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yumin_Suh_Part-Aligned_Bilinear_Representations_ECCV_2018_paper.pdf)]

#### *"Mancs: A Multi-task Attentional Network with Curriculum Sampling for Person Re-identification"* 
- [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Cheng_Wang_Mancs_A_Multi-task_ECCV_2018_paper.pdf)]

#### *"Beyond Part Models: Person Retrieval with Refined Part Pooling (and A Strong Convolutional Baseline)"* 
- [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yifan_Sun_Beyond_Part_Models_ECCV_2018_paper.pdf)]

### [CVPR2018]

#### *"Diversity Regularized Spatiotemporal Attention for Video-based Person Re-identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Li_Diversity_Regularized_Spatiotemporal_CVPR_2018_paper.pdf)]

#### *"A Pose-Sensitive Embedding for Person Re-Identification with Expanded Cross Neighborhood Re-Ranking"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Sarfraz_A_Pose-Sensitive_Embedding_CVPR_2018_paper.pdf)]

#### *"Human Semantic Parsing for Person Re-identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Kalayeh_Human_Semantic_Parsing_CVPR_2018_paper.pdf)]

#### *"Video Person Re-identification with Competitive Snippet-similarity Aggregation and Co-attentive Snippet Embedding"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_Video_Person_Re-Identification_CVPR_2018_paper.pdf)]

#### *"Mask-guided Contrastive Attention Model for Person Re-Identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Song_Mask-Guided_Contrastive_Attention_CVPR_2018_paper.pdf)]

#### *"Person Re-identification with Cascaded Pairwise Convolutions"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Person_Re-Identification_With_CVPR_2018_paper.pdf)]

#### *"Multi-Level Factorisation Net for Person Re-Identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chang_Multi-Level_Factorisation_Net_CVPR_2018_paper.pdf)]

#### *"Attention-Aware Compositional Network for Person Re-identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Xu_Attention-Aware_Compositional_Network_CVPR_2018_paper.pdf)]

#### *"Deep Group-shuffling Random Walk for Person Re-identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Shen_Deep_Group-Shuffling_Random_CVPR_2018_paper.pdf)]

#### *"Harmonious Attention Network for Person Re-Identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Li_Harmonious_Attention_Network_CVPR_2018_paper.pdf)]

#### *"Efficient and Deep Person Re-Identification using Multi-Level Similarity"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Guo_Efficient_and_Deep_CVPR_2018_paper.pdf)]

#### *"Pose Transferrable Person Re-Identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_Pose_Transferrable_Person_CVPR_2018_paper.pdf)]

#### *"Adversarially Occluded Samples for Person Re-identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Huang_Adversarially_Occluded_Samples_CVPR_2018_paper.pdf)]

#### *"Camera Style Adaptation for Person Re-identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhong_Camera_Style_Adaptation_CVPR_2018_paper.pdf)]

#### *"Dual Attention Matching Network for Context-Aware Feature Sequence based Person Re-Identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Si_Dual_Attention_Matching_CVPR_2018_paper.pdf)]

#### *"Easy Identification from Better Constraints: Multi-Shot Person Re-Identification from Reference Constraints"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhou_Easy_Identification_From_CVPR_2018_paper.pdf)]

#### *"Eliminating Background-bias for Robust Person Re-identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Tian_Eliminating_Background-Bias_for_CVPR_2018_paper.pdf)]

#### *"Features for Multi-Target Multi-Camera Tracking and Re-Identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Ristani_Features_for_Multi-Target_CVPR_2018_paper.pdf)]

#### *"Multi-shot Pedestrian Re-identification via Sequential Decision Making"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_Multi-Shot_Pedestrian_Re-Identification_CVPR_2018_paper.pdf)]

#### *"End-to-End Deep Kronecker-Product Matching for Person Re-identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Shen_End-to-End_Deep_Kronecker-Product_CVPR_2018_paper.pdf)]

#### *"Deep Spatial Feature Reconstruction for Partial Person Re-identification: Alignment-free Approach"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/He_Deep_Spatial_Feature_CVPR_2018_paper.pdf)]

#### *"Resource Aware Person Re-identification across Multiple Resolutions"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Resource_Aware_Person_CVPR_2018_paper.pdf)]

#### *"Group Consistent Similarity Learning via Deep CRF for Person Re-Identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_Group_Consistent_Similarity_CVPR_2018_paper.pdf)]

### [ICCV2017]

#### *"A Two Stream Siamese Convolutional Neural Network For Person Re-Identification"* 
- [[paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Chung_A_Two_Stream_ICCV_2017_paper.pdf)]

#### *"Learning View-Invariant Features for Person Identification in Temporally Synchronized Videos Taken by Wearable Cameras"* 
- [[paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Zheng_Learning_View-Invariant_Features_ICCV_2017_paper.pdf)]

#### *"Deeply-Learned Part-Aligned Representations for Person Re-Identification"* 
- [[paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Zhao_Deeply-Learned_Part-Aligned_Representations_ICCV_2017_paper.pdf)]

#### *"Pose-driven Deep Convolutional Model for Person Re-identification"* 
- [[paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Su_Pose-Driven_Deep_Convolutional_ICCV_2017_paper.pdf)]

#### *"Jointly Attentive Spatial-Temporal Pooling Networks for Video-based Person Re-Identification"* 
- [[paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Xu_Jointly_Attentive_Spatial-Temporal_ICCV_2017_paper.pdf)]

#### *"Multi-scale Deep Learning Architectures for Person Re-identification"* 
- [[paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Qian_Multi-Scale_Deep_Learning_ICCV_2017_paper.pdf)]

### [CVPR2017]

#### *"Learning Deep Context-Aware Features Over Body and Latent Parts for Person Re-Identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Li_Learning_Deep_Context-Aware_CVPR_2017_paper.pdf)]

#### *"Beyond Triplet Loss: A Deep Quadruplet Network for Person Re-Identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Chen_Beyond_Triplet_Loss_CVPR_2017_paper.pdf)]

#### *"Spindle Net: Person Re-Identification With Human Body Region Guided Feature Decomposition and Fusion"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Zhao_Spindle_Net_Person_CVPR_2017_paper.pdf)]

#### *"Re-Ranking Person Re-Identification With k-Reciprocal Encoding"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Zhong_Re-Ranking_Person_Re-Identification_CVPR_2017_paper.pdf)]

#### *"Scalable Person Re-Identification on Supervised Smoothed Manifold"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Bai_Scalable_Person_Re-Identification_CVPR_2017_paper.pdf)]

#### *"Point to Set Similarity Based Deep Feature Learning for Person Re-Identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Zhou_Point_to_Set_CVPR_2017_paper.pdf)]

#### *"Fast Person Re-Identification via Cross-Camera Semantic Binary Transformation"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Chen_Fast_Person_Re-Identification_CVPR_2017_paper.pdf)]

#### *"See the Forest for the Trees: Joint Spatial and Temporal Recurrent Neural Networks for Video-Based Person Re-Identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Zhou_See_the_Forest_CVPR_2017_paper.pdf)]

#### *"Consistent-Aware Deep Learning for Person Re-Identification in a Camera Network"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Lin_Consistent-Aware_Deep_Learning_CVPR_2017_paper.pdf)]



---

## Person Search

### [ECCV2018]

#### *"RCAA: Relational Context-Aware Agents for Person Search"* 
- [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Xiaojun_Chang_RCAA_Relational_Context-Aware_ECCV_2018_paper.pdf)]

#### *"Person Search in Videos with One Portrait Through Visual and Temporal Links"* 
- [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Qingqiu_Huang_Person_Search_in_ECCV_2018_paper.pdf)]

#### *"Person Search by Multi-Scale Matching"* 
- [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Xu_Lan_Person_Search_by_ECCV_2018_paper.pdf)]

#### *"Person Search via A Mask-Guided Two-Stream CNN Model"* 
- [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Di_Chen_Person_Search_via_ECCV_2018_paper.pdf)]

### [ICCV2017]

#### *"Neural Person Search Machines"* 
- [[paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Liu_Neural_Person_Search_ICCV_2017_paper.pdf)]

### [CVPR2017]

#### *"Person Search with Natural Language Description"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Li_Person_Search_With_CVPR_2017_paper.pdf)]


---

## Others

### [ECCV2018]

#### *"Integrating Egocentric Videos in Top-view Surveillance Videos: Joint Identification and Temporal Alignment"* 
- [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Shervin_Ardeshir_Integrating_Egocentric_Videos_ECCV_2018_paper.pdf)]

#### *"Reinforced Temporal Attention and Split-Rate Transfer for Depth-Based Person Re-Identification"* 
- [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Nikolaos_Karianakis_Reinforced_Temporal_Attention_ECCV_2018_paper.pdf)]

#### *"Adversarial Open-World Person Re-Identification"* 
- [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Xiang_Li_Adversarial_Open-World_Person_ECCV_2018_paper.pdf)]

### [CVPR2018]

#### *"Viewpoint-aware Attentive Multi-view Inference for Vehicle Re-identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhou_Viewpoint-Aware_Attentive_Multi-View_CVPR_2018_paper.pdf)]

#### *"Exploiting Transitivity for Learning Person Re-identification Models on a Budget"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Roy_Exploiting_Transitivity_for_CVPR_2018_paper.pdf)]


### [ICCV2017] 

#### *"Orientation Invariant Feature Embedding and Spatial Temporal Regularization for Vehicle Re-identification"* 
- [[paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Wang_Orientation_Invariant_Feature_ICCV_2017_paper.pdf)]

#### *"RGB-Infrared Cross-Modality Person Re-Identification"* 
- [[paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Wu_RGB-Infrared_Cross-Modality_Person_ICCV_2017_paper.pdf)]

### [CVPR2017] 

#### *"Joint Detection and Identification Feature Learning for Person Search"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Xiao_Joint_Detection_and_CVPR_2017_paper.pdf)]

#### *"Multiple People Tracking by Lifted Multicut and Person Re-Identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Tang_Multiple_People_Tracking_CVPR_2017_paper.pdf)]

#### *"Pose-Aware Person Recognition"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Kumar_Pose-Aware_Person_Recognition_CVPR_2017_paper.pdf)]




---


## Datasets

### [CVPR2018] 

#### *"Person Transfer GAN to Bridge Domain Gap for Person Re-Identification"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wei_Person_Transfer_GAN_CVPR_2018_paper.pdf)]
- Rank-1 (Market1501) : 38.6(source domain : DukeMTMC)

### [CVPR2017] 

#### *"Person Re-Identification in the Wild"* 
- [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Zheng_Person_Re-Identification_in_CVPR_2017_paper.pdf)]

### [[Market-1501 Leaderboard](https://jingdongwang2017.github.io/Projects/ReID/Datasets/result_market1501.html)]

### [[Collection](http://robustsystems.coe.neu.edu/sites/robustsystems.coe.neu.edu/files/systems/projectpages/reiddataset.html)]




---

## Reference 

https://github.com/handong1587/handong1587.github.io/blob/master/_posts/deep_learning/2015-10-09-re-id.md





#### *""* [[paper]()]








