# 利用细化代理的混合体提升大型语言模型中的物理推理能力

发布时间：2024年12月01日

`Agent` `科学推理`

> Improving Physics Reasoning in Large Language Models Using Mixture of Refinement Agents

# 摘要

> 大型语言模型（LLMs）在各类推理任务中表现出色。然而，在科学推理，尤其是物理学方面，它们面临严峻挑战，因为这不仅需要数学推理，还得有事实和概念的理解。处理复杂物理问题时，LLMs 一般会碰到三个关键问题：对问题理解有误、概念运用不当和计算出错。虽然每个问题都能单独处理，但需要一种通用办法能同时解决这三个问题。为此，我们推出了细化代理混合物（MoRA），这是一种创新的代理细化框架，通过纠正上述错误来反复优化 LLM 生成的基础方案，大幅提升了开源 LLMs 的性能。我们的方法旨在借助 GPT-4o 作为错误识别器来引导这些细化代理，从而缩小开源 LLMs 与 GPT-4o 的差距。我们在 SciEval 和 MMLU 子集以及我们自己的物理数据集（PhysicsQA）上对该方法进行了评估。MoRA 显著提高了 Llama-3-70B 和 Gemma-2-27B 在这些数据集上的表现，最终答案准确率最多提高了 16%。

> Large Language Models (LLMs) demonstrate remarkable capabilities in various reasoning tasks. However, they encounter significant challenges when it comes to scientific reasoning, particularly in physics, which requires not only mathematical reasoning but also factual and conceptual understanding. When addressing complex physics problems, LLMs typically face three key issues: problem miscomprehension, incorrect concept application, and computational errors. While each of these problems can be addressed individually, there is a need for a generalized approach that can tackle all three issues simultaneously. To address this, we introduce Mixture of Refinement Agents (MoRA), a novel agentic refinement framework that iteratively refines the LLM generated base solution by correcting the aforementioned errors, resulting in a significant performance improvement for open-source LLMs. Our approach aims to bridge the gap between opensource LLMs and GPT-4o by utilizing the latter as error identifier to guide these refinement agents. We evaluate our approach on the SciEval and MMLU subsets along with our own physics dataset (PhysicsQA). MoRA significantly improves the performance of Llama-3-70B and Gemma-2-27B on these datasets, achieving up to a 16% increase in final answer accuracy.

[Arxiv](https://arxiv.org/abs/2412.00821)