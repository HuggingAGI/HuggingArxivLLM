# 反思、重试、奖励：强化学习驱动的大型语言模型迭代优化

发布时间：2025年05月30日

`LLM理论

摘要讨论了通过自我反思和强化学习来提升大型语言模型的性能，提出了一种新的训练方法，属于对模型训练和优化的理论探索。`

> Reflect, Retry, Reward: Self-Improving LLMs via Reinforcement Learning

# 摘要

> # 摘要
我们提出了一种通过自我反思和强化学习提升大型语言模型性能的方法。通过激励模型在回答错误时生成更优质的自我反思，我们证明，即使生成合成数据不可行且仅有二元反馈可用，模型解决复杂可验证任务的能力仍可得到显著提升。我们的方法分为两个阶段：首先，当模型未能完成给定任务时，它会生成一段自我反思性的评论，分析其之前的尝试；其次，模型在上下文中再次尝试任务。如果后续尝试成功，则奖励在自我反思阶段生成的tokens。实验结果表明，我们的方法在多种模型架构上均带来了显著的性能提升，数学方程写作任务的改进高达34.7%，函数调用任务的改进达18.1%。值得注意的是，较小规模的微调模型（15亿至70亿参数）的表现优于同系列中大10倍的模型。因此，我们的新范式为开发更实用、更可靠的自改进语言模型提供了一条令人兴奋的路径，使其能够在有限外部反馈的情况下应对具有挑战性的任务。


> We explore a method for improving the performance of large language models through self-reflection and reinforcement learning. By incentivizing the model to generate better self-reflections when it answers incorrectly, we demonstrate that a model's ability to solve complex, verifiable tasks can be enhanced even when generating synthetic data is infeasible and only binary feedback is available. Our framework operates in two stages: first, upon failing a given task, the model generates a self-reflective commentary analyzing its previous attempt; second, the model is given another attempt at the task with the self-reflection in context. If the subsequent attempt succeeds, the tokens generated during the self-reflection phase are rewarded. Our experimental results show substantial performance gains across a variety of model architectures, as high as 34.7% improvement at math equation writing and 18.1% improvement at function calling. Notably, smaller fine-tuned models (1.5 billion to 7 billion parameters) outperform models in the same family that are 10 times larger. Our novel paradigm is thus an exciting pathway to more useful and reliable language models that can self-improve on challenging tasks with limited external feedback.

[Arxiv](https://arxiv.org/abs/2505.24726)