# 提升医学影像零样本学习：结合 CLIP 与先进方法优化胸部 X 光片分析

发布时间：2025年03月17日

`LLM应用

摘要中提到的MoCoCLIP模型结合了CLIP（一种对比语言-图像预训练模型，属于大型语言模型的应用）和动量对比（MoCo）技术，用于解决医学影像分析中的具体问题，属于大型语言模型在特定领域的应用。` `医学影像`

> Enhancing zero-shot learning in medical imaging: integrating clip with advanced techniques for improved chest x-ray analysis

# 摘要

> 面对海量医学影像数据，开发先进的AI方法辅助放射科医生通过胸部X光片（CXR）诊断胸部疾病显得尤为重要。然而，现有的深度学习模型通常依赖大量标注数据，而医学影像领域因标注过程耗时且需要专家参与，此类数据集十分稀缺。为此，我们扩展了现有方法，将对比语言-图像预训练（CLIP）与动量对比（MoCo）相结合，提出了MoCoCLIP模型。该方法有效解决了类别不平衡和无标签数据集的难题，显著提升了肺部疾病检测的性能。实验结果表明，在NIH ChestXray14数据集上，MoCoCLIP超越了现有的最先进模型CheXZero，相对提升了约6.5%。而在CheXpert数据集上，MoCoCLIP更展现了卓越的零样本学习性能，平均AUC达到0.750，优于CheXZero的0.746 AUC，充分证明了其在未见数据上的强大泛化能力。

> Due to the large volume of medical imaging data, advanced AI methodologies are needed to assist radiologists in diagnosing thoracic diseases from chest X-rays (CXRs). Existing deep learning models often require large, labeled datasets, which are scarce in medical imaging due to the time-consuming and expert-driven annotation process. In this paper, we extend the existing approach to enhance zero-shot learning in medical imaging by integrating Contrastive Language-Image Pre-training (CLIP) with Momentum Contrast (MoCo), resulting in our proposed model, MoCoCLIP. Our method addresses challenges posed by class-imbalanced and unlabeled datasets, enabling improved detection of pulmonary pathologies. Experimental results on the NIH ChestXray14 dataset demonstrate that MoCoCLIP outperforms the state-of-the-art CheXZero model, achieving relative improvement of approximately 6.5%. Furthermore, on the CheXpert dataset, MoCoCLIP demonstrates superior zero-shot performance, achieving an average AUC of 0.750 compared to CheXZero with 0.746 AUC, highlighting its enhanced generalization capabilities on unseen data.

[Arxiv](https://arxiv.org/abs/2503.13134)