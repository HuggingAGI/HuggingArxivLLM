# # 标题
CausalCLIPSeg: 释放CLIP在医学图像分割中的潜力，通过因果干预实现突破

发布时间：2025年03月20日

`LLM应用` `医学图像处理`

> CausalCLIPSeg: Unlocking CLIP's Potential in Referring Medical Image Segmentation with Causal Intervention

# 摘要

> 医学图像分割旨在根据文本描述勾勒病变区域。由于视觉与文本信息特性差异显著，二者对齐极具挑战性。受大规模预训练视觉-语言模型启发，我们提出了基于CLIP的端到端医学图像分割框架CausalCLIPSeg。尽管CLIP未接触医学数据，我们仍通过定制化跨模态解码方法，将其丰富语义空间迁移至医学领域，实现文本到像素的精准对齐。为缓解混杂偏见，避免模型学习无关伪关联，CausalCLIPSeg引入因果干预模块，可自动标注混杂因素并挖掘输入中的因果特征用于分割决策。我们还设计了对抗博弈机制，优化因果特征同时惩罚混杂因素。大量实验表明，我们提出的方法达到了当前最优水平。代码可从https://github.com/WUTCM-Lab/CausalCLIPSeg获取。

> Referring medical image segmentation targets delineating lesions indicated by textual descriptions. Aligning visual and textual cues is challenging due to their distinct data properties. Inspired by large-scale pre-trained vision-language models, we propose CausalCLIPSeg, an end-to-end framework for referring medical image segmentation that leverages CLIP. Despite not being trained on medical data, we enforce CLIP's rich semantic space onto the medical domain by a tailored cross-modal decoding method to achieve text-to-pixel alignment. Furthermore, to mitigate confounding bias that may cause the model to learn spurious correlations instead of meaningful causal relationships, CausalCLIPSeg introduces a causal intervention module which self-annotates confounders and excavates causal features from inputs for segmentation judgments. We also devise an adversarial min-max game to optimize causal features while penalizing confounding ones. Extensive experiments demonstrate the state-of-the-art performance of our proposed method. Code is available at https://github.com/WUTCM-Lab/CausalCLIPSeg.

[Arxiv](https://arxiv.org/abs/2503.15949)