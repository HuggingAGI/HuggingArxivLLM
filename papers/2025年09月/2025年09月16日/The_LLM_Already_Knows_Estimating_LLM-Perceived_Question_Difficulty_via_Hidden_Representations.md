# LLM早已洞悉：通过隐藏表示评估LLM感知的问题难度

发布时间：2025年09月16日

`LLM应用` `基础理论`

> The LLM Already Knows: Estimating LLM-Perceived Question Difficulty via Hidden Representations

# 摘要

> 评估大型语言模型（LLMs）对输入问题的感知难度，对于准确的性能评估和自适应推理至关重要。现有方法往往依赖重复响应采样、辅助模型或微调目标模型本身，不仅计算成本高昂，还可能影响通用性。本文提出一种全新的难度估计方法，仅利用目标LLM生成的隐藏表示即可实现。我们将token级生成过程建模为马尔可夫链，并定义值函数来估计给定隐藏状态下的预期输出质量。这使得仅基于初始隐藏状态就能高效准确地完成难度估计，且无需生成任何输出token。在文本和多模态任务上的大量实验表明，我们的方法在难度估计任务中始终优于现有基线。此外，我们将难度估计结果应用于指导自适应推理策略（包括自一致性（Self-Consistency）、Best-of-N和自优化（Self-Refine）），以更少的生成token实现了更高的推理效率。

> Estimating the difficulty of input questions as perceived by large language models (LLMs) is essential for accurate performance evaluation and adaptive inference. Existing methods typically rely on repeated response sampling, auxiliary models, or fine-tuning the target model itself, which may incur substantial computational costs or compromise generality. In this paper, we propose a novel approach for difficulty estimation that leverages only the hidden representations produced by the target LLM. We model the token-level generation process as a Markov chain and define a value function to estimate the expected output quality given any hidden state. This allows for efficient and accurate difficulty estimation based solely on the initial hidden state, without generating any output tokens. Extensive experiments across both textual and multimodal tasks demonstrate that our method consistently outperforms existing baselines in difficulty estimation. Moreover, we apply our difficulty estimates to guide adaptive reasoning strategies, including Self-Consistency, Best-of-N, and Self-Refine, achieving higher inference efficiency with fewer generated tokens.

[Arxiv](https://arxiv.org/abs/2509.12886)