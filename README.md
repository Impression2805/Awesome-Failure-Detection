# Awesome Failure Detection / Reliable Prediction

Failure Detection is a machine learning problem, which aims to detect out-of-distribution (OOD) and misclassified samples based on reliable confidence estimation. This topic is important for risk-sensitive applications (e.g., autonomous driving, clinical decision making, and is gathering much attention in the research community.

Here, we provide a list of papers that studies OOD detection and misclassification detection (MisD).

## Misclassification Detection / Selective Classification / Failure Prediction
- OpenMix: Exploring Outlier Samples for Misclassification Detection (**CVPR** 2023) [[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhu_OpenMix_Exploring_Outlier_Samples_for_Misclassification_Detection_CVPR_2023_paper.pdf) [[code]](https://github.com/Impression2805/OpenMix)
- Failure Detection for Motion Prediction of Autonomous Driving: An Uncertainty Perspective (**ICRA** 2023) [[paper]](https://arxiv.org/ftp/arxiv/papers/2301/2301.04421.pdf)
- A Call to Reflect on Evaluation Practices for Failure Detection in Image Classification (**ICLR** 2023) [[paper]](https://openreview.net/pdf?id=YnkGMIh0gvX) [[code]](https://github.com/IML-DKFZ/fd-shifts)
- What can we learn from the selective prediction and uncertainty estimation performance of 523 imagenet classifiers (**ICLR** 2023) [[paper]](https://arxiv.org/pdf/2302.11874.pdf) [[code]](https://github.com/IdoGalil/benchmarking-uncertainty-estimation-performance)
- Towards Better Selective Classification  (**ICLR** 2023) [[paper]](https://openreview.net/pdf?id=5gDz_yTcst) [[code]](https://github.com/BorealisAI/towards-better-sel-cls)
- AUC-based Selective Classification (**AISTATS** 2023) [[paper]](https://proceedings.mlr.press/v206/pugnana23a/pugnana23a.pdf)
- Failure Detection in Medical Image Classification: A Reality Check and Benchmarking Testbed (**TMLR** 2022) [[paper]](https://openreview.net/pdf?id=VBHuLfnOMf) [[code]](https://github.com/melanibe/failure_detection_benchmark)
- Rethinking Confidence Calibration for Failure Prediction (**ECCV** 2022) [[paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136850512.pdf) [[code]](https://github.com/Impression2805/FMFP)
- Improving the Reliability for Confidence Estimation (**ECCV** 2022) [[paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136870385.pdf)
- Trust, but Verify: Using Self-Supervised Probing to Improve Trustworthiness (**ECCV** 2022) [[paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136730362.pdf)
- Learning to predict trustworthiness with steep slope loss (**NeurIPS** 2021) [[paper]](https://arxiv.org/pdf/2110.00054.pdf) [[code]](https://github.com/luoyan407/predict_trustworthiness)
- Confidence-Aware Learning for Deep Neural Networks (**ICML** 2020) [[paper]](http://proceedings.mlr.press/v119/moon20a/moon20a.pdf) [[code]](https://github.com/daintlab/confidence-aware-learning)
- Self-Adaptive Training: beyond Empirical Risk Minimization (**NeurIPS** 2020) [[paper]](https://arxiv.org/pdf/2002.10319.pdf) [[code]](https://github.com/LayneH/self-adaptive-training)
- Selectivenet: A deep neural network with an integrated reject option (**ICML** 2019) [[paper]](http://proceedings.mlr.press/v97/geifman19a/geifman19a.pdf)
- Addressing Failure Prediction by Learning Model Confidence (**NeurIPS** 2019) [[paper]](https://proceedings.neurips.cc/paper/2019/file/757f843a169cc678064d9530d12a1881-Paper.pdf) [[code]](https://github.com/valeoai/ConfidNet)
- Deep Gamblers: Learning to Abstain with Portfolio Theory (**NeurIPS** 2019) [[paper]](https://arxiv.org/pdf/1907.00208.pdf) [[code]](https://github.com/Z-T-WANG/NIPS2019DeepGamblers)
- To Trust Or Not To Trust A Classifier (**NeurIPS** 2018) [[paper]](https://proceedings.neurips.cc/paper_files/paper/2018/file/7180cffd6a8e829dacfc2a31b3f72ece-Paper.pdf) [[code]](https://github.com/google/TrustScore)
- Selective classification for deep neural networks (**NeurIPS** 2017) [[paper]](https://proceedings.neurips.cc/paper/2017/file/4a8423d5e91fda00bb7e46540e2b0cf1-Paper.pdf)
- A Baseline for Detecting Misclassified and Out-of-Distribution Examples in Neural Networks (**ICLR** 2017) [[paper]](https://arxiv.org/pdf/1610.02136.pdf)
- An Optimum Character Recognition System Using Decision Functions (**IRE Transactions on Electronic Computers** 1957) [[paper]](https://gwern.net/doc/ai/highleyman/1957-chow.pdf)


## OOD Detection
### 2023
- Decoupling MaxLogit for Out-of-Distribution Detection (**CVPR** 2023) [[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Decoupling_MaxLogit_for_Out-of-Distribution_Detection_CVPR_2023_paper.pdf)
- Block Selection Method for Using Feature Norm in Out-of-Distribution Detection (**CVPR** 2023) [[paper]](https://arxiv.org/pdf/2212.02295.pdf) [[code]](https://github.com/gist-ailab/block-selection-for-OOD-detection)
- LINe: Out-of-Distribution Detection by Leveraging Important Neurons (**CVPR** 2023) [[paper]](https://arxiv.org/pdf/2303.13995.pdf) [[code]](https://github.com/YongHyun-Ahn/LINe-Out-of-Distribution-Detection-by-Leveraging-Important-Neurons)
- Uncertainty-Aware Optimal Transport for Semantically Coherent Out-of-Distribution Detection (**CVPR** 2023) [[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Lu_Uncertainty-Aware_Optimal_Transport_for_Semantically_Coherent_Out-of-Distribution_Detection_CVPR_2023_paper.pdf) [[code]](https://github.com/LuFan31/ET-OOD)
- Rethinking Out-of-Distribution (OOD) Detection: Masked Image Modeling Is All You Need  (**CVPR** 2023) [[paper]](https://arxiv.org/pdf/2302.02615.pdf) [[code]](https://github.com/JulietLJY/MOOD)
- Balanced Energy Regularization Loss for Out-of-Distribution Detection (**CVPR** 2023) [[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Choi_Balanced_Energy_Regularization_Loss_for_Out-of-Distribution_Detection_CVPR_2023_paper.pdf)
- Detection of Out-of-Distribution Samples Using Binary Neuron Activation Patterns (**CVPR** 2023) [[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Olber_Detection_of_Out-of-Distribution_Samples_Using_Binary_Neuron_Activation_Patterns_CVPR_2023_paper.pdf) [[code]](https://github.com/safednn-group/nap-ood)
- GEN: Pushing the Limits of Softmax-Based Out-of-Distribution Detection (**CVPR** 2023) [[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Liu_GEN_Pushing_the_Limits_of_Softmax-Based_Out-of-Distribution_Detection_CVPR_2023_paper.pdf) [[code]](https://github.com/XixiLiu95/GEN)
- Unleashing Mask: Explore the Intrinsic Out-of-Distribution Detection Capability (**ICML** 2023) [[code]](https://github.com/ZFancy/Unleashing-Mask)
- Detecting Out-of-distribution Data through In-distribution Class Prior (**ICML** 2023)
- Packed-Ensembles for Efficient Uncertainty Estimation (**ICLR** 2023) [[paper]](https://openreview.net/pdf?id=XXTyv1zD9zD) [[code]](https://github.com/ENSTA-U2IS/torch-uncertainty)
- A framework for benchmarking Class-out-of-distribution detection and its application to ImageNet (**ICLR** 2023) [[paper]](https://openreview.net/pdf?id=Iuubb9W6Jtk) [[code]](https://github.com/mdabbah/COOD_benchmarking)
- Out-of-Distribution Detection based on In-Distribution Data Patterns Memorization with Modern Hopfield Energy (**ICLR** 2023) [[paper]](https://openreview.net/pdf?id=KkazG4lgKL) [[code]](https://github.com/zjs975584714/SHE_ood_detection)
- Extremely Simple Activation Shaping for Out-of-Distribution Detection (**ICLR** 2023) [[paper]](https://openreview.net/pdf?id=ndYXTEL6cZz) [[code]](https://andrijazz.github.io/ash/)
- The Tilted Variational Autoencoder: Improving Out-of-Distribution Detection (**ICLR** 2023) [[paper]](https://openreview.net/pdf?id=YlGsTZODyjz) 
- Out-of-distribution Detection with Implicit Outlier Transformation (**ICLR** 2023) [[paper]](https://openreview.net/pdf?id=hdghx6wbGuD) [[code]](https://github.com/QizhouWang/DOE)
- Energy-based Out-of-Distribution Detection for Graph Neural Networks (**ICLR** 2023) [[paper]](https://openreview.net/pdf?id=zoz7Ze4STUL) [[code]](https://github.com/qitianwu/GraphOOD-GNNSafe)
- How to Exploit Hyperspherical Embeddings for Out-of-Distribution Detection? (**ICLR** 2023) [[paper]](https://openreview.net/pdf?id=aEFaE0W5pAd) [[code]](https://github.com/deeplearning-wisc/cider) 
- Harnessing Out-Of-Distribution Examples via Augmenting Content and Style (**ICLR** 2023) [[paper]](https://openreview.net/pdf?id=boNyg20-JDm)
- Fake It Until You Make It : Towards Accurate Near-Distribution Novelty Detection (**ICLR** 2023) [[paper]](https://openreview.net/pdf?id=QWQM0ZwZdRS) [[code]](https://github.com/rohban-lab/FITYMI)
- Non-parametric Outlier Synthesis (**ICLR** 2023) [[paper]](https://openreview.net/pdf?id=JHklpEZqduQ) [[code]](https://github.com/deeplearning-wisc/npos)
- Out-of-Distribution Detection and Selective Generation for Conditional Language Models (**ICLR** 2023) [[paper]](https://openreview.net/pdf?id=kJUS5nD0vPB)
- Turning the Curse of Heterogeneity in Federated Learning into a Blessing for Out-of-Distribution Detection (**ICLR** 2023) [[paper]](https://openreview.net/pdf?id=mMNimwRb7Gr) [[code]](https://github.com/illidanlab/FOSTER)

### 2022
- Breaking Down Out-of-Distribution Detection: Many Methods Based on OOD Training Data Estimate a Combination of the Same Core Quantities (**ICML** 2022) [[paper]](https://proceedings.mlr.press/v162/bitterwolf22a/bitterwolf22a.pdf) [[code]](https://github.com/j-cb/Breaking_Down_OOD_Detection)
- POEM: Out-of-Distribution Detection with Posterior Sampling (**ICML** 2022) [[paper]](https://proceedings.mlr.press/v162/ming22a/ming22a.pdf) [[code]](https://github.com/deeplearning-wisc/poem)
- Partial and Asymmetric Contrastive Learning for Out-of-Distribution Detection in Long-Tailed Recognition (**ICML** 2022) [[paper]](https://proceedings.mlr.press/v162/wang22aq/wang22aq.pdf) [[code]](https://github.com/amazon-science/long-tailed-ood-detection)
- Scaling Out-of-Distribution Detection for Real-World Settings (**ICML** 2022) [[paper]](https://proceedings.mlr.press/v162/hendrycks22a/hendrycks22a.pdf) [[code]](https://github.com/hendrycks/anomaly-seg)
- Mitigating Neural Network Overconfidence with Logit Normalization (**ICML** 2022) [[paper]](https://arxiv.org/pdf/2205.09310.pdf) [[code]](https://github.com/hongxin001/logitnorm_ood)
- Out-of-Distribution Detection with Deep Nearest Neighbors (**ICML** 2022) [[paper]](https://proceedings.mlr.press/v162/sun22d/sun22d.pdf) [[code]](https://github.com/deeplearning-wisc/knn-ood)
- Training OOD Detectors in their Natural Habitats (**ICML** 2022) [[paper]](https://proceedings.mlr.press/v162/katz-samuels22a/katz-samuels22a.pdf) [[code]](https://github.com/jkatzsam/woods_ood)
- Out-of-Distribution Detection via Conditional Kernel Independence Model (**NeurIPS** 2022) [[paper]](https://openreview.net/pdf?id=rTTh1RIn6E) [[code]](https://github.com/OODHSIC/conditional-i)
- Your Out-of-Distribution Detection Method is Not Robust! (**NeurIPS** 2022) [[paper]](https://openreview.net/pdf?id=YUEP3ZmkL1) [[code]](https://github.com/rohban-lab/ATD)
- Boosting Out-of-distribution Detection with Typical Features (**NeurIPS** 2022) [[paper]](https://openreview.net/pdf?id=4maAiUt0A4) [[code]](https://github.com/alibaba/easyrobust)
- RankFeat: Rank-1 Feature Removal for Out-of-distribution Detection (**NeurIPS** 2022) [[paper]](https://openreview.net/pdf?id=-deKNiSOXLG)
- Provably Adversarially Robust Detection of Out-of-Distribution Data (Almost) for Free (**NeurIPS** 2022) [[paper]](https://openreview.net/pdf?id=9ZWgrozGP0) [[code]](https://github.com/AlexMeinke/Provable-OOD-Detection)
- Watermarking for Out-of-distribution Detection (**NeurIPS** 2022) [[paper]](https://openreview.net/pdf?id=6rhl2k1SUGs) [[code]](https://github.com/QizhouWang/watermarking) 
- Is Out-of-Distribution Detection Learnable? (**NeurIPS** 2022) [[paper]](https://openreview.net/pdf?id=sde_7ZzGXOE)
- RegMixup: Mixup as a Regularizer Can Surprisingly Improve Accuracy & Out-of-Distribution Robustness (**NeurIPS** 2022) [[paper]](https://openreview.net/pdf?id=5j6fWcPccO) [[code]](https://github.com/FrancescoPinto/RegMixup)
- Out-of-Distribution Detection with An Adaptive Likelihood Ratio on Informative Hierarchical VAE (**NeurIPS** 2022) [[paper]](https://openreview.net/pdf?id=vMQ1V_z0TxU)
- GraphDE: A Generative Framework for Debiased Learning and Out-of-Distribution Detection on Graphs (**NeurIPS** 2022) [[paper]](https://openreview.net/pdf?id=mSiPuHIP7t8) [[code]](https://github.com/Emiyalzn/GraphDE)
- Density-driven Regularization for Out-of-distribution Detection (**NeurIPS** 2022) [[paper]](https://openreview.net/pdf?id=aZQJMVx8fk)
- Delving into Out-of-Distribution Detection with Vision-Language Representations (**NeurIPS** 2022) [[paper]](https://openreview.net/pdf?id=KnCS9390Va) [[code]](https://github.com/deeplearning-wisc/MCM)
- Beyond Mahalanobis Distance for Textual OOD Detection (**NeurIPS** 2022) [[paper]](https://openreview.net/pdf?id=ReB7CCByD6U)
- SIREN: Shaping Representations for Detecting Out-of-Distribution Objects (**NeurIPS** 2022) [[paper]](https://openreview.net/pdf?id=8E8tgnYlmN) [[code]](https://github.com/deeplearning-wisc/siren)
- Out-of-distribution Detection with Boundary Aware Learning (**ECCV** 2022) [[paper]](https://arxiv.org/pdf/2112.11648.pdf)
- Out-of-Distribution Detection with Semantic Mismatch under Masking (**ECCV** 2022) [[paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136840369.pdf) [[code]](https://github.com/cure-lab/MOODCat)
- Data Invariants to Understand Unsupervised Out-of-Distribution Detection (**ECCV** 2022) [[paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136910129.pdf)
- Out-of-Distribution Identification: Let Detector Tell Which I Am Not Sure (**ECCV** 2022) [[paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136700631.pdf)
- Deep Hybrid Models for Out-of-Distribution Detection (**CVPR** 2022) [[paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Cao_Deep_Hybrid_Models_for_Out-of-Distribution_Detection_CVPR_2022_paper.pdf)
- Rethinking Reconstruction Autoencoder-Based Out-of-Distribution Detection (**CVPR** 2022) [[paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhou_Rethinking_Reconstruction_Autoencoder-Based_Out-of-Distribution_Detection_CVPR_2022_paper.pdf)
- ViM: Out-of-Distribution With Virtual-Logit Matching (**CVPR** 2022) [[paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_ViM_Out-of-Distribution_With_Virtual-Logit_Matching_CVPR_2022_paper.pdf) [[code]](https://github.com/haoqiwang/vim)
- Neural Mean Discrepancy for Efficient Out-of-Distribution Detection (**CVPR** 2022) [[paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Dong_Neural_Mean_Discrepancy_for_Efficient_Out-of-Distribution_Detection_CVPR_2022_paper.pdf)
- Unknown-Aware Object Detection: Learning What You Don’t Know from Videos in the Wild (**CVPR** 2022) [[paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Du_Unknown-Aware_Object_Detection_Learning_What_You_Dont_Know_From_Videos_CVPR_2022_paper.pdf) [[code]](https://github.com/deeplearning-wisc/stud)
- Revisiting flow generative models for Out-of-distribution detection (**ICLR** 2022) [[paper]](https://openreview.net/pdf?id=6y2KBh-0Fd9)
- Igeood: An Information Geometry Approach to Out-of-Distribution Detection (**ICLR** 2022) [[paper]](https://openreview.net/pdf?id=mfwdY3U_9ea)
- A Statistical Framework for Efficient Out of Distribution Detection in Deep Neural Networks (**ICLR** 2022) [[paper]](https://openreview.net/pdf?id=Oy9WeuZD51)
- VOS: Learning What You Don't Know by Virtual Outlier Synthesis (**ICLR** 2022) [[paper]](https://openreview.net/pdf?id=TW7d65uYu5M) [[code]](https://github.com/deeplearning-wisc/vos)

### 2021
- Understanding Failures in Out-of-Distribution Detection with Deep Generative Models (**ICML** 2021) [[paper]](http://proceedings.mlr.press/v139/zhang21g/zhang21g.pdf)
- Exploring the Limits of Out-of-Distribution Detection (**NeurIPS** 2021) [[paper]](https://openreview.net/pdf?id=j5NrN8ffXC)
- STEP: Out-of-Distribution Detection in the Presence of Limited In-Distribution Labeled Data (**NeurIPS** 2021) [[paper]](https://openreview.net/pdf?id=p9dySshcS0q)
- Locally Most Powerful Bayesian Test for Out-of-Distribution Detection Using Deep Generative Models (**NeurIPS** 2021) [[paper]](https://openreview.net/pdf?id=-nLW4nhdkO)
- Single Layer Predictive Normalized Maximum Likelihood for Out-of-Distribution Detection (**NeurIPS** 2021) [[paper]](https://openreview.net/pdf?id=ympqhd5gE9)
- ReAct: Out-of-distribution Detection With Rectified Activations (**NeurIPS** 2021) [[paper]](https://openreview.net/pdf?id=IBVBtz_sRSm) [[code]](https://github.com/deeplearning-wisc/react)
- Entropy Maximization and Meta Classification for Out-of-Distribution Detection in Semantic Segmentation (**ICCV** 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Chan_Entropy_Maximization_and_Meta_Classification_for_Out-of-Distribution_Detection_in_Semantic_ICCV_2021_paper.pdf)
- Semantically Coherent Out-of-Distribution Detection (**ICCV** 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Yang_Semantically_Coherent_Out-of-Distribution_Detection_ICCV_2021_paper.pdf) [[code]](https://jingkang50.github.io/projects/scood)
- Triggering Failures: Out-of-Distribution Detection by Learning From Local Adversarial Attacks in Semantic Segmentation (**ICCV** 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Besnier_Triggering_Failures_Out-of-Distribution_Detection_by_Learning_From_Local_Adversarial_Attacks_ICCV_2021_paper.pdf) [[code]](https://github.com/valeoai/obsnet)
- MOOD: Multi-Level Out-of-Distribution Detection (**CVPR** 2021) [[paper]]() [[code]]()
- MOS: Towards Scaling Out-of-Distribution Detection for Large Semantic Space (**CVPR** 2021) [[paper]]() [[code]]()
- Out-of-Distribution Detection Using Union of 1-Dimensional Subspaces (**CVPR** 2021) [[paper]]() [[code]]()











 (**ICML** 2021) [[paper]]() [[code]]()
 (**NeurIPS** 2021) [[paper]]() [[code]]()
 (**ICLR** 2021) [[paper]]() [[code]]()
 (**ICCV** 2021) [[paper]]() [[code]]()
 (**CVPR** 2021) [[paper]]() [[code]]()



