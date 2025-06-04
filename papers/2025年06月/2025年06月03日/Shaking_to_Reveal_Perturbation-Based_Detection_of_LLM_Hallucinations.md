# 摇一摇，看真相：LLM幻觉的扰动检测法

发布时间：2025年06月03日

`LLM应用

摘要讨论了大型语言模型（LLMs）在问答任务中的幻觉问题，并提出了一种新的自评估框架来改进幻觉检测。这种方法属于LLM的应用层面，因为它专注于如何改进模型在特定任务中的性能和可靠性。` `问答系统`

> Shaking to Reveal: Perturbation-Based Detection of LLM Hallucinations

# 摘要

> 幻觉是大型语言模型（LLMs）在现实世界问答任务中可靠应用的主要障碍。目前广泛采用的自评估检测方法，依赖于模型自身的输出置信度来判断答案的事实准确性。然而，这种方法假设模型的输出分布能够准确反映真实数据分布，这一假设在实际应用中并不总能成立。随着模型各层中偏差的累积，最终输出可能偏离潜在的推理过程，导致输出级别的置信度成为幻觉检测中不可靠的信号。为此，我们提出了样本特定提示（SSP），这是一种通过分析中间表示的扰动敏感性来改进自评估的新框架。这些中间表示受模型偏差的影响较小，能够更真实地反映模型潜在的推理过程。具体而言，SSP为每个输入动态生成噪声提示，并利用轻量级编码器来放大扰动引起的表示变化。随后，通过对比距离度量量化这些差异，从而区分真实与幻觉回答。通过利用中间表示在扰动下的动态行为，SSP实现了更可靠的自评估。大量实验结果表明，SSP在多个幻觉检测基准上显著优于现有方法。

> Hallucination remains a key obstacle to the reliable deployment of large language models (LLMs) in real-world question answering tasks. A widely adopted strategy to detect hallucination, known as self-assessment, relies on the model's own output confidence to estimate the factual accuracy of its answers. However, this strategy assumes that the model's output distribution closely reflects the true data distribution, which may not always hold in practice. As bias accumulates through the model's layers, the final output can diverge from the underlying reasoning process, making output-level confidence an unreliable signal for hallucination detection. In this work, we propose Sample-Specific Prompting (SSP), a new framework that improves self-assessment by analyzing perturbation sensitivity at intermediate representations. These representations, being less influenced by model bias, offer a more faithful view of the model's latent reasoning process. Specifically, SSP dynamically generates noise prompts for each input and employs a lightweight encoder to amplify the changes in representations caused by the perturbation. A contrastive distance metric is then used to quantify these differences and separate truthful from hallucinated responses. By leveraging the dynamic behavior of intermediate representations under perturbation, SSP enables more reliable self-assessment. Extensive experiments demonstrate that SSP significantly outperforms prior methods across a range of hallucination detection benchmarks.

[Arxiv](https://arxiv.org/abs/2506.02696)