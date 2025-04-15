# LLM 的遗忘机制揭示了当前基准测试中比预期更显著的 coreset 效应

发布时间：2025年04月14日

`LLM理论` `模型治理`

> LLM Unlearning Reveals a Stronger-Than-Expected Coreset Effect in Current Benchmarks

# 摘要

> 大型语言模型的遗忘机制已成为确保模型安全性和可控行为的关键挑战。通过移除预训练模型中不受欢迎的数据影响，同时保持其整体实用性，这一机制在模型治理中发挥着重要作用。近期，研究者们致力于开发如WMDP和MUSE等遗忘基准测试，这些基准为标准化的遗忘性能评估和方法比较提供了重要工具。然而，我们在这些基准测试中首次发现了核心集效应这一新颖现象。具体而言，我们发现即使使用原始遗忘集的极小子集（例如仅5%的遗忘样本，甚至随机选择），也能有效维持大型语言模型的遗忘效果。这一发现表明，在这些基准测试中，大型语言模型的遗忘机制可以在极低数据量的情况下出人意料地轻松实现。无论采用哪种遗忘方法（如NPO和RMU等常用方法），这种核心集效应依然表现强劲。这一效应在各种数据选择方法中都表现出强大的鲁棒性，从随机选择到更复杂的启发式方法。通过基于关键词的视角，我们揭示了核心集效应的本质：仅从遗忘集中提取的关键词对遗忘效果有显著贡献，表明当前的遗忘机制主要依赖于一个紧凑的高影响力标记集，而非整个数据集。我们进一步从模式连通性和对越狱攻击的鲁棒性等维度验证了核心集遗忘模型的可靠性。相关代码可在GitHub仓库中获取。

> Large language model unlearning has become a critical challenge in ensuring safety and controlled model behavior by removing undesired data-model influences from the pretrained model while preserving general utility. Significant recent efforts have been dedicated to developing LLM unlearning benchmarks such as WMDP (Weapons of Mass Destruction Proxy) and MUSE (Machine Unlearning Six-way Evaluation), facilitating standardized unlearning performance assessment and method comparison. Despite their usefulness, we uncover for the first time a novel coreset effect within these benchmarks. Specifically, we find that LLM unlearning achieved with the original (full) forget set can be effectively maintained using a significantly smaller subset (functioning as a "coreset"), e.g., as little as 5% of the forget set, even when selected at random. This suggests that LLM unlearning in these benchmarks can be performed surprisingly easily, even in an extremely low-data regime. We demonstrate that this coreset effect remains strong, regardless of the LLM unlearning method used, such as NPO (Negative Preference Optimization) and RMU (Representation Misdirection Unlearning), the popular ones in these benchmarks. The surprisingly strong coreset effect is also robust across various data selection methods, ranging from random selection to more sophisticated heuristic approaches. We explain the coreset effect in LLM unlearning through a keyword-based perspective, showing that keywords extracted from the forget set alone contribute significantly to unlearning effectiveness and indicating that current unlearning is driven by a compact set of high-impact tokens rather than the entire dataset. We further justify the faithfulness of coreset-unlearned models along additional dimensions, such as mode connectivity and robustness to jailbreaking attacks. Codes are available at https://github.com/OPTML-Group/MU-Coreset.

[Arxiv](https://arxiv.org/abs/2504.10185)