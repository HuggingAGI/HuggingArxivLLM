# <翻译失败>

发布时间：2025年01月30日

`LLM应用

**理由**: 这篇论文主要讨论了如何通过微调大型视觉-语言模型（VLMs）来提升其在安全关键场景下的视觉感知与推理能力。论文提出了一个新的数据集（MIS数据集）并展示了使用该数据集微调模型的效果。这属于将大型语言模型（LLM）应用于特定任务（安全关键场景下的视觉推理）的范畴，因此分类为LLM应用。` `安全关键领域` `视觉感知`

> Rethinking Bottlenecks in Safety Fine-Tuning of Vision Language Models

# 摘要

> 大型视觉-语言模型（VLMs）在众多任务中表现出色，但在安全关键领域的应用却面临巨大挑战。现有的安全微调方法，主要针对文本或多模态内容，难以应对复杂案例，或破坏了有用性与无害性之间的平衡。我们的评估揭示了一个安全推理的短板：这些方法缺乏安全视觉推理能力，导致瓶颈。为弥补这一不足并提升安全关键场景下的视觉感知与推理能力，我们提出了一个创新数据集，将多图像输入与安全链式思维（CoT）标签结合，作为细粒度推理逻辑，以提升模型性能。具体而言，我们推出了多图像安全（MIS）数据集，这是一个专为多图像安全场景设计的指令跟随数据集，包含训练和测试集。实验表明，使用MIS微调InternVL2.5-8B在需要安全相关视觉推理的复杂多图像任务中，显著优于强大的开源模型和基于API的模型。此方法不仅提供了卓越的安全性能，还保持了通用能力，无需任何妥协。具体来说，使用MIS微调在五个通用基准测试中平均准确率提升了0.83%，并在多个安全基准测试中大幅降低了攻击成功率（ASR）。数据和模型已发布在：\href{https://dripnowhy.github.io/MIS/}{	exttt{https://dripnowhy.github.io/MIS/}}

> Large Vision-Language Models (VLMs) have achieved remarkable performance across a wide range of tasks. However, their deployment in safety-critical domains poses significant challenges. Existing safety fine-tuning methods, which focus on textual or multimodal content, fall short in addressing challenging cases or disrupt the balance between helpfulness and harmlessness. Our evaluation highlights a safety reasoning gap: these methods lack safety visual reasoning ability, leading to such bottlenecks. To address this limitation and enhance both visual perception and reasoning in safety-critical contexts, we propose a novel dataset that integrates multi-image inputs with safety Chain-of-Thought (CoT) labels as fine-grained reasoning logic to improve model performance. Specifically, we introduce the Multi-Image Safety (MIS) dataset, an instruction-following dataset tailored for multi-image safety scenarios, consisting of training and test splits. Our experiments demonstrate that fine-tuning InternVL2.5-8B with MIS significantly outperforms both powerful open-source models and API-based models in challenging multi-image tasks requiring safety-related visual reasoning. This approach not only delivers exceptional safety performance but also preserves general capabilities without any trade-offs. Specifically, fine-tuning with MIS increases average accuracy by 0.83% across five general benchmarks and reduces the Attack Success Rate (ASR) on multiple safety benchmarks by a large margin. Data and Models are released under: \href{https://dripnowhy.github.io/MIS/}{\texttt{https://dripnowhy.github.io/MIS/}}

[Arxiv](https://arxiv.org/abs/2501.18533)