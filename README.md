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




 (**NeurIPS** 2023) [[paper]]() [[code]]()



