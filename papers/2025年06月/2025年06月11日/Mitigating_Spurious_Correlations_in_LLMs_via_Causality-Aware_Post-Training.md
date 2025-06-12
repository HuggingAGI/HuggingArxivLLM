# 利用因果感知后训练缓解大语言模型中的虚假相关性

发布时间：2025年06月11日

`LLM理论` `因果推理`

> Mitigating Spurious Correlations in LLMs via Causality-Aware Post-Training

# 摘要

> 尽管大型语言模型 (LLMs) 在语言建模方面展现出了令人惊叹的能力，但近期研究表明，它们在处理分布外 (OOD) 样本时往往表现不佳，这主要归因于预训练过程中获取的错误关联。我们提出了一种因果感知的后训练方法 (CAPT)，通过将有偏预测分解为	extit{事件估计}和	extit{事件干预}两个无偏步骤，成功减少了 LLMs 的预训练偏见，同时避免了额外微调带来的偏见，从而显著提升了模型的泛化能力。在正式因果推理基准 CLadder 和逻辑推理数据集 PrOntoQA 上的实验结果表明，仅使用 100 个分布内 (ID) 样本进行 CAPT 微调的 30 亿规模语言模型，在 ID 和 OOD 任务上均能超越传统的 SFT 方法和更大规模的 LLMs，充分证明了 CAPT 的有效性及样本效率。

> While large language models (LLMs) have demonstrated remarkable capabilities in language modeling, recent studies reveal that they often fail on out-of-distribution (OOD) samples due to spurious correlations acquired during pre-training. Here, we aim to mitigate such spurious correlations through causality-aware post-training (CAPT). By decomposing a biased prediction into two unbiased steps, known as \textit{event estimation} and \textit{event intervention}, we reduce LLMs' pre-training biases without incurring additional fine-tuning biases, thus enhancing the model's generalization ability. Experiments on the formal causal inference benchmark CLadder and the logical reasoning dataset PrOntoQA show that 3B-scale language models fine-tuned with CAPT can outperform both traditional SFT and larger LLMs on in-distribution (ID) and OOD tasks using only 100 ID fine-tuning samples, demonstrating the effectiveness and sample efficiency of CAPT.

[Arxiv](https://arxiv.org/abs/2506.09433)