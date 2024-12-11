# 一种用于预测透明细胞肾细胞癌治疗结果的多模态集成式方法

发布时间：2024年12月09日

`其他` `癌症预后`

> A multimodal ensemble approach for clear cell renal cell carcinoma treatment outcome prediction

# 摘要

> 目的：可靠的透明细胞肾细胞癌（ccRCC）癌症预后模型能够强化个性化治疗。我们构建了一种多模态集成模型（MMEM），它融合了预处理临床数据、多组学数据以及组织病理学全切片图像（WSI）数据，用于预测ccRCC患者的总生存期（OS）和无病生存期（DFS）。方法：我们对来自癌症基因组图谱肾透明细胞癌（TCGA-KIRC）数据集的226名患者进行了分析，其中涵盖OS、DFS随访数据以及五种数据模态：临床数据、WSIs和三个多组学数据集（mRNA、miRNA和DNA甲基化）。分别为OS和DFS构建了独立的生存模型。针对临床和多组学数据，运用具有正向特征选择的Cox比例风险（CPH）模型。通过ResNet和三个通用基础模型从WSIs中提取特征。基于深度学习的CPH模型利用编码的WSI特征来预测生存期。依据训练表现将所有模型的风险评分加以整合。结果：采用一致性指数（C-index）和AUROC来评估性能。基于临床特征的CPH模型在OS和DFS任务中权重最高。在基于WSI的模型中，通用基础模型（UNI）表现最优。最终的MMEM模型超越了单模态模型，达成了0.820（OS）和0.833（DFS）的C指数，以及0.831（3年患者死亡）和0.862（癌症复发）的AUROC值。使用预测风险中位数对高危和低危组进行分层，对数秩检验表明，与单模态模型相比，OS和DFS的性能均有提升。结论：MMEM是首个针对ccRCC患者的多模态模型，整合了五种数据模态。其在预后能力上优于单模态模型，若能通过独立验证，有望助力ccRCC患者的管理。

> Purpose: A reliable cancer prognosis model for clear cell renal cell carcinoma (ccRCC) can enhance personalized treatment. We developed a multi-modal ensemble model (MMEM) that integrates pretreatment clinical data, multi-omics data, and histopathology whole slide image (WSI) data to predict overall survival (OS) and disease-free survival (DFS) for ccRCC patients. Methods: We analyzed 226 patients from The Cancer Genome Atlas Kidney Renal Clear Cell Carcinoma (TCGA-KIRC) dataset, which includes OS, DFS follow-up data, and five data modalities: clinical data, WSIs, and three multi-omics datasets (mRNA, miRNA, and DNA methylation). Separate survival models were built for OS and DFS. Cox-proportional hazards (CPH) model with forward feature selection is used for clinical and multi-omics data. Features from WSIs were extracted using ResNet and three general-purpose foundation models. A deep learning-based CPH model predicted survival using encoded WSI features. Risk scores from all models were combined based on training performance. Results: Performance was assessed using concordance index (C-index) and AUROC. The clinical feature-based CPH model received the highest weight for both OS and DFS tasks. Among WSI-based models, the general-purpose foundation model (UNI) achieved the best performance. The final MMEM model surpassed single-modality models, achieving C-indices of 0.820 (OS) and 0.833 (DFS), and AUROC values of 0.831 (3-year patient death) and 0.862 (cancer recurrence). Using predicted risk medians to stratify high- and low-risk groups, log-rank tests showed improved performance in both OS and DFS compared to single-modality models. Conclusion: MMEM is the first multi-modal model for ccRCC patients, integrating five data modalities. It outperformed single-modality models in prognostic ability and has the potential to assist in ccRCC patient management if independently validated.

[Arxiv](https://arxiv.org/abs/2412.07136)