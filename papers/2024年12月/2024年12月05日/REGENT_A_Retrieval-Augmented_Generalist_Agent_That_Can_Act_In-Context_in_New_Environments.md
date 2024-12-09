# REGENT：一种检索增强型的全能代理，能够在新环境中进行上下文内的行动

发布时间：2024年12月05日

`Agent` `人工智能` `机器人`

> REGENT: A Retrieval-Augmented Generalist Agent That Can Act In-Context in New Environments

# 摘要

> 构建能迅速适应新环境的全能型代理，是在数字和现实世界部署人工智能的关键挑战。当前扩大代理架构是构建全能型代理的最有效途径吗？我们提出了一种新方法，即在相对较小的数据集上预训练相对较小的策略，并通过上下文学习将其适配到未曾见过的环境中，无需任何微调。我们的核心思路是，检索为快速适应提供了有力的偏向。实际上，我们证明，哪怕是基于简单检索的 1 近邻代理，也为当下最先进的全能型代理提供了令人惊喜的强大基准。以此为起点，我们构建了一个半参数代理 REGENT，它在查询和检索到的邻居序列上训练基于变压器的策略。REGENT 能够通过检索增强和上下文学习推广到未曾见过的机器人和游戏环境，实现这一目标时，参数少 3 倍，预训练数据点少一个数量级，显著优于当下最先进的全能型代理。网站: https://kaustubhsridhar.github.io/regent-research

> Building generalist agents that can rapidly adapt to new environments is a key challenge for deploying AI in the digital and real worlds. Is scaling current agent architectures the most effective way to build generalist agents? We propose a novel approach to pre-train relatively small policies on relatively small datasets and adapt them to unseen environments via in-context learning, without any finetuning. Our key idea is that retrieval offers a powerful bias for fast adaptation. Indeed, we demonstrate that even a simple retrieval-based 1-nearest neighbor agent offers a surprisingly strong baseline for today's state-of-the-art generalist agents. From this starting point, we construct a semi-parametric agent, REGENT, that trains a transformer-based policy on sequences of queries and retrieved neighbors. REGENT can generalize to unseen robotics and game-playing environments via retrieval augmentation and in-context learning, achieving this with up to 3x fewer parameters and up to an order-of-magnitude fewer pre-training datapoints, significantly outperforming today's state-of-the-art generalist agents. Website: https://kaustubhsridhar.github.io/regent-research

[Arxiv](https://arxiv.org/abs/2412.04759)