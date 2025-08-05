# 原始数据的重要性：利用内部数据增强优化视觉-语言模型中的提示微调

发布时间：2025年08月04日

`LLM应用

理由：这篇论文探讨了基于CLIP的提示微调方法，提出了一种新的数据增强策略，AugPT，用于提升模型性能和泛化能力。虽然涉及图像处理，但核心在于优化提示微调技术，属于模型应用层面的改进，因此归类为LLM应用。` `计算机视觉` `图像处理`

> Raw Data Matters: Enhancing Prompt Tuning by Internal Augmentation on Vision-Language Models

# 摘要

> 在基于CLIP的提示微调中，通过引入更多数据作为额外知识来提升微调效果已被证实为一种有效手段。然而，现有的数据增强策略多依赖外部知识（如大型语言模型或预结构化知识库），这不仅增加了数据处理成本，还忽视了图像模态特征的进一步挖掘。为此，我们提出了一种名为Augmentation-driven Prompt Tuning（AugPT）的自包含蒸馏式提示微调方法，仅通过原始数据集的内部增强即可更好地挖掘已知特征。具体而言，AugPT采用自监督增强技术处理训练集中的未标记图像，并引入基于共识测试的创新门控机制，借助预训练的提示微调主干模型自动筛选噪声样本，从而进一步提升增强视图的质量。通过大量实验验证，AugPT无需借助额外外部知识即可同时实现模型性能与泛化能力的提升。AugPT的代码已开源，访问地址为：https://github.com/JREion/AugPT。

> For CLIP-based prompt tuning, introducing more data as additional knowledge for enhancing fine-tuning process is proved to be an effective approach. Existing data amplification strategies for prompt tuning typically rely on external knowledge (e.g., large language models or pre-structured knowledge bases), resulting in higher costs for data collection and processing, while generally ignoring further utilization of features in image modality. To address this, we propose Augmentation-driven Prompt Tuning (AugPT), a self-contained distillation-based prompt tuning approach using only internal augmentation on raw dataset to better exploit known features. Specifically, AugPT employs self-supervised augmentation on unlabeled images in the training set, and introduces a novel gating mechanism based on consensus test, reusing the pre-trained prompt tuning backbone model to spontaneously filter noisy samples, further enhancing the quality of augmented views. Extensive experiments validate that AugPT simultaneously enhances model performance and generalization capability without using appended external knowledge. The code of AugPT is available at: https://github.com/JREion/AugPT .

[Arxiv](https://arxiv.org/abs/2508.02671)