# 激励推理：提升大型语言模型的高级指令遵循能力

发布时间：2025年06月02日

`LLM理论` `机器学习`

> Incentivizing Reasoning for Advanced Instruction-Following of Large Language Models

# 摘要

> 现有大型语言模型（LLMs）在处理复杂指令时面临挑战，尤其是在多约束并存且以并行、链式和分支结构组织的情况下。虽然思维链（CoT）这一直观解决方案有望提升LLMs的能力，但基础版的CoT由于其简单的指令改写推理模式，对性能产生了负面影响。它未能揭示约束的组成，以识别不同层次类型和维度之间的关系。为此，我们提出了一种系统方法，通过在推理阶段激励计算扩展来增强LLMs处理复杂指令的能力。首先，我们从现有分类法下的复杂指令分解出发，提出了一种可复现的数据获取方法。其次，我们利用具有可验证规则中心奖励信号的强化学习（RL），专门培养指令遵循的推理能力。我们通过样本级对比来实现更优质的CoT执行，从而解决复杂指令下推理浅显、非本质的问题。我们还利用专家行为克隆，促进从快速思考的LLMs到熟练推理者的稳定分布转移。在七个综合基准上的广泛评估验证了所提方法的有效性，其中1.5B参数的LLM实现了11.74%的性能提升，与8B参数的LLM表现相当。代码和数据可在https://github.com/yuleiqin/RAIF获取。

> Existing large language models (LLMs) face challenges of following complex instructions, especially when multiple constraints are present and organized in paralleling, chaining, and branching structures. One intuitive solution, namely chain-of-thought (CoT), is expected to universally improve capabilities of LLMs. However, we find that the vanilla CoT exerts a negative impact on performance due to its superficial reasoning pattern of simply paraphrasing the instructions. It fails to peel back the compositions of constraints for identifying their relationship across hierarchies of types and dimensions. To this end, we propose a systematic method to boost LLMs in dealing with complex instructions via incentivizing reasoning for test-time compute scaling. First, we stem from the decomposition of complex instructions under existing taxonomies and propose a reproducible data acquisition method. Second, we exploit reinforcement learning (RL) with verifiable rule-centric reward signals to cultivate reasoning specifically for instruction following. We address the shallow, non-essential nature of reasoning under complex instructions via sample-wise contrast for superior CoT enforcement. We also exploit behavior cloning of experts to facilitate steady distribution shift from fast-thinking LLMs to skillful reasoners. Extensive evaluations on seven comprehensive benchmarks confirm the validity of the proposed method, where a 1.5B LLM achieves 11.74% gains with performance comparable to a 8B LLM. Codes and data are available at https://github.com/yuleiqin/RAIF.

[Arxiv](https://arxiv.org/abs/2506.01413)