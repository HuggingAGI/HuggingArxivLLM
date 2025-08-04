# 误导性报告的风险：揭示多模态临床AI中的文本偏见

发布时间：2025年07月31日

`LLM应用` `人工智能`

> On the Risk of Misleading Reports: Diagnosing Textual Biases in Multimodal Clinical AI

# 摘要

> 临床决策往往需要结合医学图像和临床报告进行综合分析。尽管视觉语言模型（VLMs）能为此类任务提供统一的分析框架，但它们常常会对某一种模态表现出强烈偏好，忽视关键的视觉线索而侧重于文本信息。在此研究中，我们引入了选择性模态转换（SMS），这是一种基于扰动的方法，用于量化二分类任务中模型对每种模态的依赖程度。通过系统地在具有相反标签的样本之间交换图像或文本，我们揭示了模态特异性的偏见。我们在两个具有不同模态的医学影像数据集上评估了六个开源VLMs——其中四个是通用模型，另外两个是针对医学数据进行了微调：MIMIC-CXR（胸部X光片）和FairVLMed（扫描激光眼底成像）。通过评估模型在未扰动和扰动环境下的性能及其校准情况，我们发现模型对文本输入存在显著依赖，即使存在互补的视觉信息，这种依赖仍然存在。我们还进行了一项基于注意力的定性分析，进一步证实了图像内容常被文本细节所掩盖。我们的研究结果强调了设计和评估真正整合视觉和文本线索的多模态医学模型的重要性，而不是单纯依赖单一模态信号。


> Clinical decision-making relies on the integrated analysis of medical images and the associated clinical reports. While Vision-Language Models (VLMs) can offer a unified framework for such tasks, they can exhibit strong biases toward one modality, frequently overlooking critical visual cues in favor of textual information. In this work, we introduce Selective Modality Shifting (SMS), a perturbation-based approach to quantify a model's reliance on each modality in binary classification tasks. By systematically swapping images or text between samples with opposing labels, we expose modality-specific biases. We assess six open-source VLMs-four generalist models and two fine-tuned for medical data-on two medical imaging datasets with distinct modalities: MIMIC-CXR (chest X-ray) and FairVLMed (scanning laser ophthalmoscopy). By assessing model performance and the calibration of every model in both unperturbed and perturbed settings, we reveal a marked dependency on text input, which persists despite the presence of complementary visual information. We also perform a qualitative attention-based analysis which further confirms that image content is often overshadowed by text details. Our findings highlight the importance of designing and evaluating multimodal medical models that genuinely integrate visual and textual cues, rather than relying on single-modality signals.

[Arxiv](https://arxiv.org/abs/2508.00171)