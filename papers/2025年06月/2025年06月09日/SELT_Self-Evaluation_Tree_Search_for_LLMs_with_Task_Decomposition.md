# SELT：任务分解驱动的大型语言模型自评估树搜索

发布时间：2025年06月09日

`LLM理论

摘要分析：这篇论文探讨了大型语言模型在复杂推理任务中的不足，并提出了一种创新的框架SELT，利用改进的蒙特卡洛树搜索来强化推理。它详细描述了方法论的改进，属于对模型理论和机制的研究，因此归类为LLM理论。` `知识推理` `工具学习`

> SELT: Self-Evaluation Tree Search for LLMs with Task Decomposition

# 摘要

> 大型语言模型 (LLMs) 虽然在众多应用中表现出色，但在复杂推理任务中仍显不足。本研究推出 SELT（自我评估 LLM 树搜索），一种创新性框架，利用改进的蒙特卡洛树搜索 (MCTS) 强化 LLM 推理，无需借助外部奖励模型。通过重新定义上置信界评分以匹配 LLM 的自我评估机制，并将推理过程分解为节点上带有语义聚类的原子任务，SELT 实现了探索与利用的平衡，减少了冗余推理路径，有效抑制了幻觉现象。我们在知识型 MMLU 和工具学习数据集 Seal-Tools 等挑战性基准上验证了 SELT 的优势，结果显示其在答案准确性和推理稳定性方面显著超越传统方法。尤为重要的是，SELT 无需特定任务微调，展现出卓越的跨任务泛化能力。相关成果和代码已开源，详情请访问 https://github.com/fairyshine/SELT。

> While Large Language Models (LLMs) have achieved remarkable success in a wide range of applications, their performance often degrades in complex reasoning tasks. In this work, we introduce SELT (Self-Evaluation LLM Tree Search), a novel framework that leverages a modified Monte Carlo Tree Search (MCTS) to enhance LLM reasoning without relying on external reward models. By redefining the Upper Confidence Bound scoring to align with intrinsic self-evaluation capabilities of LLMs and decomposing the inference process into atomic subtasks augmented with semantic clustering at each node, SELT effectively balances exploration and exploitation, reduces redundant reasoning paths, and mitigates hallucination. We validate our approach on challenging benchmarks, including the knowledge-based MMLU and the Tool Learning dataset Seal-Tools, where SELT achieves significant improvements in answer accuracy and reasoning robustness compared to baseline methods. Notably, our framework operates without task-specific fine-tuning, demonstrating strong generalizability across diverse reasoning tasks. Relevant results and code are available at https://github.com/fairyshine/SELT .

[Arxiv](https://arxiv.org/abs/2506.07557)