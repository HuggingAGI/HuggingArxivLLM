# MEDFORM: 多癌症分析中CT成像与临床数值数据对比学习的基础模型

发布时间：2025年01月22日

`其他

理由：这篇论文主要讨论的是医学领域的多模态预训练策略，特别是针对CT图像和临床数据的处理和分析。虽然涉及到了预训练模型的使用，但其核心内容与LLM（大型语言模型）无关，也不涉及Agent、RAG或LLM理论。因此，将其分类为“其他”更为合适。` `癌症诊断`

> MEDFORM: A Foundation Model for Contrastive Learning of CT Imaging and Clinical Numeric Data in Multi-Cancer Analysis

# 摘要

> # 摘要
CT和临床数值数据是癌症评估的关键模态，但构建大规模多模态训练数据集以开发医学基础模型仍面临挑战，主要源于多切片CT数据的复杂结构和专家标注的高昂成本。本研究提出MEDFORM，一种多模态预训练策略，通过临床数据的互补信息指导CT图像表示学习，助力医学基础模型开发。MEDFORM利用多实例学习（MIL）高效处理CT切片，并采用双重预训练策略：先基于SimCLR自监督学习预训练CT切片特征提取器，再通过跨模态对比学习对齐CT与临床模态。模型在肺癌（141,171切片）、乳腺癌（8,100切片）和结直肠癌（10,393切片）上预训练，实验证明该策略显著提升癌症分类性能，并在少样本学习中表现稳健。代码已开源：https://github.com/DigitalHealthcareLab/25MultiModalFoundationModel.git。

> Computed tomography (CT) and clinical numeric data are essential modalities for cancer evaluation, but building large-scale multimodal training datasets for developing medical foundation models remains challenging due to the structural complexity of multi-slice CT data and high cost of expert annotation. In this study, we propose MEDFORM, a multimodal pre-training strategy that guides CT image representation learning using complementary information from clinical data for medical foundation model development. MEDFORM efficiently processes CT slice through multiple instance learning (MIL) and adopts a dual pre-training strategy: first pretraining the CT slice feature extractor using SimCLR-based self-supervised learning, then aligning CT and clinical modalities through cross-modal contrastive learning. Our model was pre-trained on three different cancer types: lung cancer (141,171 slices), breast cancer (8,100 slices), colorectal cancer (10,393 slices). The experimental results demonstrated that this dual pre-training strategy improves cancer classification performance and maintains robust performance in few-shot learning scenarios. Code available at https://github.com/DigitalHealthcareLab/25MultiModalFoundationModel.git

[Arxiv](https://arxiv.org/abs/2501.13277)