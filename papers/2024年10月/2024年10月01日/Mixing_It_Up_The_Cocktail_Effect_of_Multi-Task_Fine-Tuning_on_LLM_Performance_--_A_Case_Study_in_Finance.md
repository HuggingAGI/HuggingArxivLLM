# 混合之道：多任务微调对LLM性能的鸡尾酒效应——以金融领域为例

发布时间：2024年10月01日

`LLM应用

理由：这篇论文主要讨论了大型语言模型（LLMs）在金融领域的应用，特别是通过多任务微调策略来提升模型在特定领域任务中的表现。论文详细分析了微调策略对模型性能的影响，并展示了如何通过多任务微调使小型模型在金融基准测试中超越更大的模型。这些内容都属于LLM在实际应用中的优化和性能提升，因此应归类为LLM应用。` `语言模型`

> Mixing It Up: The Cocktail Effect of Multi-Task Fine-Tuning on LLM Performance -- A Case Study in Finance

# 摘要

> 大型语言模型（LLMs）在金融等特定领域的应用迅速扩展。通常，特定领域的LLMs通过其在相关下游任务中的表现进行评估。本文详细分析了针对此类任务的LLMs微调策略。有趣的是，我们发现，在特定领域场景下，仅针对目标任务进行微调并非最佳策略。相反，多任务微调——即在多个相关任务上训练模型——能显著提升性能。我们展示了这种方法如何使小型模型（如Phi-3-Mini）在金融基准测试中超越更大的GPT-4-o模型，达到最先进水平。通过大规模实验，我们训练了200多个模型，并实证了多任务微调的优势。此外，我们探索了通用指令数据的正则化作用，发现其能有效减少性能下降。数学数据的加入也提升了数值推理能力，并成功迁移到金融任务中。最后，我们指出，尽管下游任务微调能提升任务性能，但未必能显著增强领域知识或复杂推理能力。

> The application of large language models (LLMs) in domain-specific contexts, including finance, has expanded rapidly. Domain-specific LLMs are typically evaluated based on their performance in various downstream tasks relevant to the domain. In this work, we present a detailed analysis of fine-tuning LLMs for such tasks. Somewhat counterintuitively, we find that in domain-specific cases, fine-tuning exclusively on the target task is not always the most effective strategy. Instead, multi-task fine-tuning - where models are trained on a cocktail of related tasks - can significantly enhance performance. We demonstrate how this approach enables a small model, such as Phi-3-Mini, to achieve state-of-the-art results, even surpassing the much larger GPT-4-o model on financial benchmarks. Our study involves a large-scale experiment, training over 200 models using several widely adopted LLMs as baselines, and empirically confirms the benefits of multi-task fine-tuning. Additionally, we explore the use of general instruction data as a form of regularization, suggesting that it helps minimize performance degradation. We also investigate the inclusion of mathematical data, finding improvements in numerical reasoning that transfer effectively to financial tasks. Finally, we note that while fine-tuning for downstream tasks leads to targeted improvements in task performance, it does not necessarily result in broader gains in domain knowledge or complex domain reasoning abilities.

[Arxiv](https://arxiv.org/abs/2410.01109)