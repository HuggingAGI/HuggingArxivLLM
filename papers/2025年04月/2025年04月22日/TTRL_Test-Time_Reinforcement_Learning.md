# # TTRL：测试时强化学习新方法

发布时间：2025年04月22日

`LLM理论` `人工智能`

> TTRL: Test-Time Reinforcement Learning

# 摘要

> 本文研究了在大型语言模型（LLMs）中，针对推理任务，使用无明确标签数据进行的强化学习（RL）。问题的核心挑战在于推理过程中奖励估计，而没有访问到真实信息。尽管这种设置看似难以捉摸，但我们发现测试时间缩放（TTS）中的常见方法，如多数投票，能够产生令人惊讶的有效奖励，这些奖励适用于驱动RL训练。在这项工作中，我们引入了测试时间强化学习（TTRL），这是一种利用RL在无标签数据上训练LLMs的新方法。TTRL通过利用预训练模型中的先验知识，实现了LLMs的自我进化。我们的实验表明，TTRL在各种任务和模型上都持续提升了性能。值得注意的是，仅使用无标签的测试数据，TTRL就将Qwen-2.5-Math-7B在AIME 2024任务中的pass@1性能提升了约159%。此外，尽管TTRL仅由Maj@N指标监督，但它已经表现出持续超越初始模型上限的性能，并接近直接在带有真实标签的测试数据上训练的模型的性能。我们的实验结果验证了TTRL在各种任务中的普遍有效性，并突显了其在更广泛任务和领域中的潜在应用。GitHub链接：https://github.com/PRIME-RL/TTRL

> This paper investigates Reinforcement Learning (RL) on data without explicit labels for reasoning tasks in Large Language Models (LLMs). The core challenge of the problem is reward estimation during inference while not having access to ground-truth information. While this setting appears elusive, we find that common practices in Test-Time Scaling (TTS), such as majority voting, yield surprisingly effective rewards suitable for driving RL training. In this work, we introduce Test-Time Reinforcement Learning (TTRL), a novel method for training LLMs using RL on unlabeled data. TTRL enables self-evolution of LLMs by utilizing the priors in the pre-trained models. Our experiments demonstrate that TTRL consistently improves performance across a variety of tasks and models. Notably, TTRL boosts the pass@1 performance of Qwen-2.5-Math-7B by approximately 159% on the AIME 2024 with only unlabeled test data. Furthermore, although TTRL is only supervised by the Maj@N metric, TTRL has demonstrated performance to consistently surpass the upper limit of the initial model, and approach the performance of models trained directly on test data with ground-truth labels. Our experimental findings validate the general effectiveness of TTRL across various tasks, and highlight TTRL's potential for broader tasks and domains. GitHub: https://github.com/PRIME-RL/TTRL

[Arxiv](https://arxiv.org/abs/2504.16084)