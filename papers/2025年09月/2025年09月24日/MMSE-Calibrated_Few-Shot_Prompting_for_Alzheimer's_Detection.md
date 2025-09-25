# 基于MMSE校准的少样本提示：阿尔茨海默病检测

发布时间：2025年09月24日

`LLM应用` `医疗健康`

> MMSE-Calibrated Few-Shot Prompting for Alzheimer's Detection

# 摘要

> 提示大型语言模型是一种免训练方法，可直接从语音转录本中检测阿尔茨海默病。借助ADReSS数据集，我们重新探究零样本提示，并采用类别平衡协议（结合嵌套交错与严格模式）研究少样本提示，每个类别最多纳入20个示例。我们评估了两种变体，均实现了提示方法的最新性能。(i) MMSE代理提示：每个少样本示例通过确定性映射将概率锚定到简易精神状态检查（MMSE）等级，支持AUC计算；其准确率达0.82，AUC为0.86 (ii) 推理增强提示：少样本示例池由多模态LLM（GPT-5）生成，该模型以Cookie Theft图像、转录本和MMSE为输入，输出推理过程及与MMSE对齐的概率；评估仍仅基于转录本，准确率达0.82，AUC为0.83。据我们所知，这是ADReSS研究中首次将导出概率锚定到MMSE，并通过多模态构建提升可解释性。

> Prompting large language models is a training-free method for detecting Alzheimer's disease from speech transcripts. Using the ADReSS dataset, we revisit zero-shot prompting and study few-shot prompting with a class-balanced protocol using nested interleave and a strict schema, sweeping up to 20 examples per class. We evaluate two variants achieving state-of-the-art prompting results. (i) MMSE-Proxy Prompting: each few-shot example carries a probability anchored to Mini-Mental State Examination bands via a deterministic mapping, enabling AUC computing; this reaches 0.82 accuracy and 0.86 AUC (ii) Reasoning-augmented Prompting: few-shot examples pool is generated with a multimodal LLM (GPT-5) that takes as input the Cookie Theft image, transcript, and MMSE to output a reasoning and MMSE-aligned probability; evaluation remains transcript-only and reaches 0.82 accuracy and 0.83 AUC. To our knowledge, this is the first ADReSS study to anchor elicited probabilities to MMSE and to use multimodal construction to improve interpretability.

[Arxiv](https://arxiv.org/abs/2509.19926)