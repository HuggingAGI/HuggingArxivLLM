# ToM-RL：强化学习助力小型LLMs理解心智理论

发布时间：2025年04月02日

`LLM应用` `人工智能` `社交认知`

> ToM-RL: Reinforcement Learning Unlocks Theory of Mind in Small LLMs

# 摘要

> 近年来，基于规则的强化学习（RL）在大型语言模型（LLMs）的后训练阶段应用中取得了显著进展，尤其是在数学和逻辑推理等结构化推理任务中提升了模型的能力。然而，RL在社会推理，特别是心理理论（ToM，即推断他人心理状态的能力）方面的有效性，仍待进一步探索。本研究展示了RL方法如何有效解锁小型LLM（0.5B到7B参数）的ToM推理能力。通过使用一个包含3200个涵盖多种场景的问题的数据集，我们的RL训练的70亿参数模型在Hi-ToM基准上达到了84.50%的准确率，超越了GPT-4o和DeepSeek-v3等模型，尽管参数量远少于这些模型。较小规模的模型（≤3B参数）在推理能力上出现下降，而较大规模的模型（7B参数）通过持续追踪信念保持了稳定的推理表现。此外，我们的基于RL的模型在更高级的、分布外的ToM问题、新颖的文本表达以及未见过的数据集上展现了强大的泛化能力。这些发现凸显了RL在增强LLMs社交认知推理方面的潜力，弥合了结构化问题解决与精细社交推理之间的差距。

> Recent advancements in rule-based reinforcement learning (RL), applied during the post-training phase of large language models (LLMs), have significantly enhanced their capabilities in structured reasoning tasks such as mathematics and logical inference. However, the effectiveness of RL in social reasoning, particularly in Theory of Mind (ToM), the ability to infer others' mental states, remains largely unexplored. In this study, we demonstrate that RL methods effectively unlock ToM reasoning capabilities even in small-scale LLMs (0.5B to 7B parameters). Using a modest dataset comprising 3200 questions across diverse scenarios, our RL-trained 7B model achieves 84.50\% accuracy on the Hi-ToM benchmark, surpassing models like GPT-4o and DeepSeek-v3 despite significantly fewer parameters. While smaller models ($\leq$3B parameters) suffer from reasoning collapse, larger models (7B parameters) maintain stable performance through consistent belief tracking. Additionally, our RL-based models demonstrate robust generalization to higher-order, out-of-distribution ToM problems, novel textual presentations, and previously unseen datasets. These findings highlight RL's potential to enhance social cognitive reasoning, bridging the gap between structured problem-solving and nuanced social inference in LLMs.

[Arxiv](https://arxiv.org/abs/2504.01698)