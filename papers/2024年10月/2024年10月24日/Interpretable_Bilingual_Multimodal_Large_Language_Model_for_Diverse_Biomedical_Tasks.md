# 面向多样化生物医学任务的可解释双语多模态大语言模型

发布时间：2024年10月24日

`LLM应用

理由：这篇论文主要讨论了医学多模态大语言模型（MLLMs）的开发和应用，特别是如何增强这些模型在医学图像和文本任务中的表现。论文提出了一个新的模型MedRegA，并展示了其在多种医学视觉语言任务中的优异表现。这些内容主要涉及大语言模型在医学领域的应用，因此应归类为LLM应用。` `人工智能`

> Interpretable Bilingual Multimodal Large Language Model for Diverse Biomedical Tasks

# 摘要

> # 摘要
多个医学多模态大语言模型（MLLMs）已被开发，用于处理跨多种医学模态的视觉图像和文本指令任务，取得了显著成果。目前大多数医学通用模型是区域无关的，将整个图像视为整体表示。然而，它们在生成句子时难以识别具体关注区域。为了模仿医生从整体图像审查到特定区域深入评估的行为，我们旨在增强医学MLLMs在整个医学扫描中理解解剖区域的能力。为此，我们首先制定了以区域为中心的任务，并构建了大规模数据集MedRegInstruct，将区域信息纳入训练。结合其他医学多模态语料库，我们提出了区域感知的医学MLLM——MedRegA，这是首个双语通用医学AI系统，能够同时处理广泛的模态中的图像级和区域级医学视觉语言任务。MedRegA不仅完成了三个以区域为中心的任务，还在8种模态中的视觉问答、报告生成和医学图像分类中表现最佳，展示了显著的多样性。实验表明，我们的模型不仅在双语环境中表现出色，还能识别和检测多模态医学扫描中的结构，提升了医学MLLMs的可解释性和用户交互性。项目页面：https://medrega.github.io。

> Several medical Multimodal Large Languange Models (MLLMs) have been developed to address tasks involving visual images with textual instructions across various medical modalities, achieving impressive results. Most current medical generalist models are region-agnostic, treating the entire image as a holistic representation. However, they struggle to identify which specific regions they are focusing on when generating a sentence. To mimic the behavior of doctors, who typically begin by reviewing the entire image before concentrating on specific regions for a thorough evaluation, we aim to enhance the capability of medical MLLMs in understanding anatomical regions within entire medical scans. To achieve it, we first formulate Region-Centric tasks and construct a large-scale dataset, MedRegInstruct, to incorporate regional information into training. Combining our collected dataset with other medical multimodal corpora for training, we propose a Region-Aware medical MLLM, MedRegA, which is the first bilingual generalist medical AI system to simultaneously handle image-level and region-level medical vision-language tasks across a broad range of modalities. Our MedRegA not only enables three region-centric tasks, but also achieves the best performance for visual question answering, report generation and medical image classification over 8 modalities, showcasing significant versatility. Experiments demonstrate that our model can not only accomplish powerful performance across various medical vision-language tasks in bilingual settings, but also recognize and detect structures in multimodal medical scans, boosting the interpretability and user interactivity of medical MLLMs. Our project page is https://medrega.github.io.

[Arxiv](https://arxiv.org/abs/2410.18387)