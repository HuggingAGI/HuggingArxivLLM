# # 搜索与优化：LLMs的自主检索增强推理
在思考过程中实现搜索与优化：LLMs的自主检索增强推理能力

发布时间：2025年05月16日

`LLM应用` `问答系统`

> Search and Refine During Think: Autonomous Retrieval-Augmented Reasoning of LLMs

# 摘要

> 大型语言模型虽然展现了强大的推理能力，但其知识储备的局限性也不容忽视。检索增强推理通过允许模型查询外部资源来弥补这一不足，但现有方法常因检索到不相关或有噪声的信息而影响推理的准确性。本文提出了一种全新的强化学习后训练框架——AutoRefine，它采用“搜索与思考过程中的精炼”范式。AutoRefine在连续的搜索调用之间加入了明确的知识精炼步骤，使模型能够逐步过滤、提炼和组织证据，从而生成更精准的答案。此外，我们引入了特定于检索的奖励机制，并结合答案正确性的奖励，通过组相对策略优化来提升性能。实验结果表明，AutoRefine在单跳和多跳问答基准测试中表现优异，尤其在复杂、多跳推理场景中更是显著优于现有方法。详细分析显示，AutoRefine不仅能够频繁进行高质量的搜索，还能有效地综合证据，展现出强大的推理能力。

> Large language models have demonstrated impressive reasoning capabilities but are inherently limited by their knowledge reservoir. Retrieval-augmented reasoning mitigates this limitation by allowing LLMs to query external resources, but existing methods often retrieve irrelevant or noisy information, hindering accurate reasoning. In this paper, we propose AutoRefine, a reinforcement learning post-training framework that adopts a new ``search-and-refine-during-think'' paradigm. AutoRefine introduces explicit knowledge refinement steps between successive search calls, enabling the model to iteratively filter, distill, and organize evidence before generating an answer. Furthermore, we incorporate tailored retrieval-specific rewards alongside answer correctness rewards using group relative policy optimization. Experiments on single-hop and multi-hop QA benchmarks demonstrate that AutoRefine significantly outperforms existing approaches, particularly in complex, multi-hop reasoning scenarios. Detailed analysis shows that AutoRefine issues frequent, higher-quality searches and synthesizes evidence effectively.

[Arxiv](https://arxiv.org/abs/2505.11277)