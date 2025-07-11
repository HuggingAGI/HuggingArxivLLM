# # 多模态大型语言模型在对抗模态冲突中的鲁棒性研究
多模态大型语言模型在对抗模态冲突中的鲁棒性研究

发布时间：2025年07月09日

`LLM应用` `人工智能` `计算机视觉`

> Robust Multimodal Large Language Models Against Modality Conflict

# 摘要

> 尽管多模态大语言模型（MLLMs）在视觉语言任务中表现卓越，但它们在现实场景中容易产生幻觉。本文从模态冲突的独特视角深入探究了这一现象。与现有研究主要关注模型输出与输入之间的冲突不同，我们聚焦于不同模态输入之间固有的冲突，这些冲突使MLLMs陷入两难境地，并直接引发幻觉。我们正式定义了模态冲突的概念，并构建了一个名为多模态模态冲突（MMMC）的数据集，以模拟视觉语言任务中的这一现象。为了解决模态冲突带来的幻觉问题，我们提出了三种创新方法：基于提示工程、监督微调和强化学习的方法。通过在MMMC数据集上进行的全面实验，我们系统分析了这些方法的优缺点。研究结果表明，强化学习方法在缓解模态冲突导致的幻觉方面表现最为出色，而监督微调方法则展现出稳定且极具潜力的性能。我们的研究不仅揭示了导致幻觉却常被忽视的模态冲突问题，还为提升MLLMs的鲁棒性提供了重要启示。

> Despite the impressive capabilities of multimodal large language models (MLLMs) in vision-language tasks, they are prone to hallucinations in real-world scenarios. This paper investigates the hallucination phenomenon in MLLMs from the perspective of modality conflict. Unlike existing works focusing on the conflicts between model responses and inputs, we study the inherent conflicts in inputs from different modalities that place MLLMs in a dilemma and directly lead to hallucinations. We formally define the modality conflict and construct a dataset named Multimodal Modality Conflict (MMMC) to simulate this phenomenon in vision-language tasks. Three methods based on prompt engineering, supervised fine-tuning, and reinforcement learning are proposed to alleviate the hallucination caused by modality conflict. Extensive experiments are conducted on the MMMC dataset to analyze the merits and demerits of these methods. Our results show that the reinforcement learning method achieves the best performance in mitigating the hallucination under modality conflict, while the supervised fine-tuning method shows promising and stable performance. Our work sheds light on the unnoticed modality conflict that leads to hallucinations and provides more insights into the robustness of MLLMs.

[Arxiv](https://arxiv.org/abs/2507.07151)