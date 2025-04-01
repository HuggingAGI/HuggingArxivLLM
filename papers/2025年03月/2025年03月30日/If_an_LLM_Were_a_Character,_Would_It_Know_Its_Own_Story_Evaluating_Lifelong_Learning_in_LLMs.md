# 如果大型语言模型是一个虚构角色，它会像角色一样了解自己的“故事”吗？——评估大型语言模型的终身学习能力

发布时间：2025年03月30日

`LLM理论` `对话系统`

> If an LLM Were a Character, Would It Know Its Own Story? Evaluating Lifelong Learning in LLMs

# 摘要

> 大型语言模型（LLMs）能够进行类人对话，但与人类不同，由于叠加特性，它们是无状态的。然而，在多轮多角色交互过程中，LLMs开始展现出一致的、类似角色的行为，暗示了一种涌现式的终身学习能力。现有的基准测试往往未能捕捉这些动态，主要关注于静态的开放性评估。为了解决这一差距，我们引入了LIFESTATE-BENCH，这是一个旨在评估LLMs中终身学习能力的基准测试。它包含两个 episodic 数据集：《哈姆雷特》和一个合成脚本集合，内容丰富，包含叙述结构和角色互动。我们的事实核查评估考察了模型在参数化和非参数化方法下自我意识、 episodic 记忆检索和关系追踪的能力。在 Llama3.1-8B、GPT-4-turbo 和 DeepSeek R1 等模型上的实验表明，非参数化方法在管理有状态学习方面显著优于参数化方法。然而，随着交互的延长，所有模型都表现出灾难性遗忘的挑战，突显了在终身学习领域进一步发展的必要性。

> Large language models (LLMs) can carry out human-like dialogue, but unlike humans, they are stateless due to the superposition property. However, during multi-turn, multi-agent interactions, LLMs begin to exhibit consistent, character-like behaviors, hinting at a form of emergent lifelong learning. Despite this, existing benchmarks often fail to capture these dynamics, primarily focusing on static, open-ended evaluations. To address this gap, we introduce LIFESTATE-BENCH, a benchmark designed to assess lifelong learning in LLMs. It features two episodic datasets: Hamlet and a synthetic script collection, rich in narrative structure and character interactions. Our fact checking evaluation probes models' self-awareness, episodic memory retrieval, and relationship tracking, across both parametric and non-parametric approaches. Experiments on models like Llama3.1-8B, GPT-4-turbo, and DeepSeek R1, we demonstrate that nonparametric methods significantly outperform parametric ones in managing stateful learning. However, all models exhibit challenges with catastrophic forgetting as interactions extend, highlighting the need for further advancements in lifelong learning.

[Arxiv](https://arxiv.org/abs/2503.23514)