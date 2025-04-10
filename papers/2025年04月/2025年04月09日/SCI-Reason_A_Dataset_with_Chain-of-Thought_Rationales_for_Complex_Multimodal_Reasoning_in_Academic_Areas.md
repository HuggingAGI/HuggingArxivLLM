# 面向学术领域复杂多模态推理的链式思维推理数据集 SCI-Reason

发布时间：2025年04月09日

`LLM应用` `学术领域` `问答系统`

> SCI-Reason: A Dataset with Chain-of-Thought Rationales for Complex Multimodal Reasoning in Academic Areas

# 摘要

> 大型语言模型（LLMs）和大型多模态模型（LMMs）在许多任务中展现出了卓越的问题解决能力，但在学术领域处理复杂图像推理的能力仍有待深入研究。为此，我们推出了专注于学术领域复杂多模态推理的SCI-Reason数据集。该数据集包含从PubMed提取的12,066张图像和12,626对问答，每对问答还附有高效的推理链，用于提升推理特性。通过评估8个知名模型，我们发现表现最佳的Claude-3.7-Sonnet仅达到55.19%的准确率。错误分析表明，模型失败主要源于多步推理链的断裂，而非视觉特征提取错误。这凸显了当前多模态模型在处理真实学术场景下的复杂图像分析任务时的局限性。实验表明，SCI-Reason不仅提升了推理能力，还在VQA任务中展现了跨领域泛化能力。此外，我们还探讨了模型推理能力在未来研究中的应用潜力。

> Large Language Models (LLMs) and Large Multimodal Models (LMMs) demonstrate impressive problem-solving skills in many tasks and domains. However, their ability to reason with complex images in academic domains has not been systematically investigated. To bridge this gap, we present SCI-Reason, a dataset for complex multimodel reasoning in academic areas. SCI-Reason aims to test and improve the reasoning ability of large multimodal models using real complex images in academic domains. The dataset contains 12,066 images and 12,626 question-answer pairs extracted from PubMed, divided into training, validation and test splits. Each question-answer pair also contains an accurate and efficient inference chain as a guide to improving the inference properties of the dataset. With SCI-Reason, we performed a comprehensive evaluation of 8 well-known models. The best performing model, Claude-3.7-Sonnet, only achieved an accuracy of 55.19%. Error analysis shows that more than half of the model failures are due to breakdowns in multi-step inference chains rather than errors in primary visual feature extraction. This finding underscores the inherent limitations in reasoning capabilities exhibited by current multimodal models when processing complex image analysis tasks within authentic academic contexts. Experiments on open-source models show that SCI-Reason not only enhances reasoning ability but also demonstrates cross-domain generalization in VQA tasks. We also explore future applications of model inference capabilities in this domain, highlighting its potential for future research.

[Arxiv](https://arxiv.org/abs/2504.06637)