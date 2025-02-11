# 10亿参数的LLM能否超越4050亿参数的LLM？重新思考计算最优的测试时间缩放

发布时间：2025年02月10日

`LLM应用

摘要主要讨论了测试时缩放（TTS）方法在提升大型语言模型（LLMs）性能中的应用，特别是在不同政策模型、PRMs和问题难度下的优化策略。论文通过实验证明了TTS策略在特定任务中的有效性，并展示了小规模模型在优化后的策略下能够超越更大规模的模型。这些研究属于LLM的应用层面，因此归类为LLM应用。` `人工智能` `计算机科学`

> Can 1B LLM Surpass 405B LLM? Rethinking Compute-Optimal Test-Time Scaling

# 摘要

> 测试时缩放（TTS）是一种通过推理阶段的额外计算来提升大型语言模型（LLMs）性能的重要方法。然而，目前的研究尚未系统性地分析政策模型、过程奖励模型（PRMs）以及问题难度对TTS的影响，这一分析的缺失限制了我们对TTS方法的理解及其实际应用。本文专注于两个核心问题：（1）如何在不同政策模型、PRMs和问题难度水平之间优化测试时计算的缩放方法？（2）延长计算能在多大程度上提升LLMs在复杂任务中的性能，较小规模的模型是否能通过此方法超越更大规模的模型？通过在MATH-500和具有挑战性的AIME24任务上的全面实验，我们得出以下观察结果：（1）计算最优的TTS策略高度依赖于所选的政策模型、PRM和问题难度。（2）采用我们的计算最优TTS策略，极小型政策模型的表现能够超越更大规模的模型。例如，在MATH-500任务中，10亿参数的LLM能够超越4050亿参数的LLM。此外，在MATH-500和AIME24任务上，0.5B的LLM超越了GPT-4o，3B的LLM超过了405B的LLM，而7B的LLM则击败了o1和DeepSeek-R1，同时保持了更高的推理效率。这些发现凸显了根据任务和模型的具体特性调整TTS策略的重要性，并表明TTS是一种有潜力提升LLMs推理能力的方法。


> Test-Time Scaling (TTS) is an important method for improving the performance of Large Language Models (LLMs) by using additional computation during the inference phase. However, current studies do not systematically analyze how policy models, Process Reward Models (PRMs), and problem difficulty influence TTS. This lack of analysis limits the understanding and practical use of TTS methods. In this paper, we focus on two core questions: (1) What is the optimal approach to scale test-time computation across different policy models, PRMs, and problem difficulty levels? (2) To what extent can extended computation improve the performance of LLMs on complex tasks, and can smaller language models outperform larger ones through this approach? Through comprehensive experiments on MATH-500 and challenging AIME24 tasks, we have the following observations: (1) The compute-optimal TTS strategy is highly dependent on the choice of policy model, PRM, and problem difficulty. (2) With our compute-optimal TTS strategy, extremely small policy models can outperform larger models. For example, a 1B LLM can exceed a 405B LLM on MATH-500. Moreover, on both MATH-500 and AIME24, a 0.5B LLM outperforms GPT-4o, a 3B LLM surpasses a 405B LLM, and a 7B LLM beats o1 and DeepSeek-R1, while with higher inference efficiency. These findings show the significance of adapting TTS strategies to the specific characteristics of each task and model and indicate that TTS is a promising approach for enhancing the reasoning abilities of LLMs.

[Arxiv](https://arxiv.org/abs/2502.06703)