# 攀登之路，智慧深琢：论学习推理中的噪声奖励

发布时间：2025年05月28日

`LLM理论

论文摘要：近期研究主要通过强化学习（RL）对大型语言模型（LLMs）进行后训练以提升推理能力，但这些研究通常局限于能被准确验证和奖励的任务，例如数学问题解答。相比之下，我们的研究聚焦于一个更具现实意义的因素——奖励噪声，探讨其对基于奖励模型的LLMs后训练的影响。研究发现，LLMs展现出对大量奖励噪声的强健性。例如，在数学任务中手动翻转40%的奖励函数输出，Qwen-2.5-7B模型仍能快速收敛，其数学任务性能从5%提升至72%，而使用无噪声奖励训练的模型准确率达到了75%。令人惊讶的是，仅通过奖励关键推理短语的出现（即推理模式奖励，RPR），如“首先，我需要...”而无需验证答案的正确性，模型仍能实现峰值下游性能（Qwen-2.5-7B模型准确率超过70%），与经过严格正确性验证和精准奖励训练的模型表现相当。认识到推理过程的重要性，我们将RPR与噪声奖励模型相结合。RPR帮助校准噪声奖励模型，缓解潜在的误判，并提升LLMs在开放性任务中的表现。这些发现不仅凸显了在预训练阶段提升模型基础能力的重要性，同时也为推进后训练技术提供了宝贵的见解。我们的代码和脚本可在https://github.com/trestad/Noisy-Rewards-in-Learning-to-Reason获取。` `人工智能`

> The Climb Carves Wisdom Deeper Than the Summit: On the Noisy Rewards in Learning to Reason

# 摘要

> 近期研究主要通过强化学习（RL）对大型语言模型（LLMs）进行后训练以提升推理能力，但这些研究通常局限于能被准确验证和奖励的任务，例如数学问题解答。相比之下，我们的研究聚焦于一个更具现实意义的因素——奖励噪声，探讨其对基于奖励模型的LLMs后训练的影响。研究发现，LLMs展现出对大量奖励噪声的强健性。例如，在数学任务中手动翻转40%的奖励函数输出，Qwen-2.5-7B模型仍能快速收敛，其数学任务性能从5%提升至72%，而使用无噪声奖励训练的模型准确率达到了75%。令人惊讶的是，仅通过奖励关键推理短语的出现（即推理模式奖励，RPR），如“首先，我需要...”而无需验证答案的正确性，模型仍能实现峰值下游性能（Qwen-2.5-7B模型准确率超过70%），与经过严格正确性验证和精准奖励训练的模型表现相当。认识到推理过程的重要性，我们将RPR与噪声奖励模型相结合。RPR帮助校准噪声奖励模型，缓解潜在的误判，并提升LLMs在开放性任务中的表现。这些发现不仅凸显了在预训练阶段提升模型基础能力的重要性，同时也为推进后训练技术提供了宝贵的见解。我们的代码和脚本可在https://github.com/trestad/Noisy-Rewards-in-Learning-to-Reason获取。

> Recent studies on post-training large language models (LLMs) for reasoning through reinforcement learning (RL) typically focus on tasks that can be accurately verified and rewarded, such as solving math problems. In contrast, our research investigates the impact of reward noise, a more practical consideration for real-world scenarios involving the post-training of LLMs using reward models. We found that LLMs demonstrate strong robustness to substantial reward noise. For example, manually flipping 40% of the reward function's outputs in math tasks still allows a Qwen-2.5-7B model to achieve rapid convergence, improving its performance on math tasks from 5% to 72%, compared to the 75% accuracy achieved by a model trained with noiseless rewards. Surprisingly, by only rewarding the appearance of key reasoning phrases (namely reasoning pattern reward, RPR), such as ``first, I need to''-without verifying the correctness of answers, the model achieved peak downstream performance (over 70% accuracy for Qwen-2.5-7B) comparable to models trained with strict correctness verification and accurate rewards. Recognizing the importance of the reasoning process over the final results, we combined RPR with noisy reward models. RPR helped calibrate the noisy reward models, mitigating potential false negatives and enhancing the LLM's performance on open-ended tasks. These findings suggest the importance of improving models' foundational abilities during the pre-training phase while providing insights for advancing post-training techniques. Our code and scripts are available at https://github.com/trestad/Noisy-Rewards-in-Learning-to-Reason.

[Arxiv](https://arxiv.org/abs/2505.22653)