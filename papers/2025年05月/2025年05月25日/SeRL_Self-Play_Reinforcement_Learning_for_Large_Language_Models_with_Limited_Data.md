# # **SeRL: 面向数据有限的大型语言模型的自对弈强化学习**  
针对数据有限的大型语言模型，我们提出了一种自对弈强化学习方法——SeRL。

发布时间：2025年05月25日

`LLM应用` `人工智能` `机器学习`

> SeRL: Self-Play Reinforcement Learning for Large Language Models with Limited Data

# 摘要

> 强化学习（RL）在提升大型语言模型（LLMs）推理能力方面表现出显著效果。然而，现有方法在训练过程中往往依赖高质量的指令和可验证的奖励，这在专业领域中获取起来颇具挑战。本文提出了一种基于自对弈的强化学习方法（SeRL），旨在利用有限的初始数据启动LLM的训练。具体而言，SeRL由两个互补模块组成：自指令生成和自奖励机制。自指令生成模块在每个训练步骤中根据现有数据生成额外指令，并采用稳健的在线过滤策略，确保指令的质量、多样性和难度。自奖励机制则引入了一种简单而有效的多数投票机制，用于估计额外指令的响应奖励，从而避免了对外部标注的依赖。最后，SeRL基于生成的数据进行传统的强化学习，促进迭代的自对弈学习。在多种推理基准测试和不同LLM架构上的广泛实验表明，提出的SeRL方法在性能上优于现有方法，并且与基于高质量数据和可验证奖励的性能相当。我们的代码可在GitHub上获取，链接为https://github.com/wantbook-book/SeRL。

> Recent advances have demonstrated the effectiveness of Reinforcement Learning (RL) in improving the reasoning capabilities of Large Language Models (LLMs). However, existing works inevitably rely on high-quality instructions and verifiable rewards for effective training, both of which are often difficult to obtain in specialized domains. In this paper, we propose Self-play Reinforcement Learning(SeRL) to bootstrap LLM training with limited initial data. Specifically, SeRL comprises two complementary modules: self-instruction and self-rewarding. The former module generates additional instructions based on the available data at each training step, employing robust online filtering strategies to ensure instruction quality, diversity, and difficulty. The latter module introduces a simple yet effective majority-voting mechanism to estimate response rewards for additional instructions, eliminating the need for external annotations. Finally, SeRL performs conventional RL based on the generated data, facilitating iterative self-play learning. Extensive experiments on various reasoning benchmarks and across different LLM backbones demonstrate that the proposed SeRL yields results superior to its counterparts and achieves performance on par with those obtained by high-quality data with verifiable rewards. Our code is available at https://github.com/wantbook-book/SeRL.

[Arxiv](https://arxiv.org/abs/2505.20347)